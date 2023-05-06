---
layout: page
title: Tutorials
subtitle: CFD Module - Dev release
nav-short: true
---

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()"><i class='fa fa-times'></i></a>
  <header>TUTORIALS</header>
  <a href="https://hystrath.github.io/tutos/dev/hy2foam/toc/"><center><img src="/docs/img/logos/hy2FoamLogo.png" width="60"></center></a>
  <a href="https://hystrath.github.io/tutos/dev/hy2foam/heatbath"><b>Adiabatic heat bath</b></a>
  <a href="https://hystrath.github.io/tutos/dev/hy2foam/sod" style="background-color:#FFCCCC"><b>Sod's shock tube</b></a>
  <a href="https://hystrath.github.io/tutos/dev/hy2foam/sod/#1-subsonic-case" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><center><u>Subsonic case</u></center></a>
  <a href="https://hystrath.github.io/tutos/dev/hy2foam/sod/#11-case-setup" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px">&nbsp;&nbsp; 1. Case setup</a>
  <a href="https://hystrath.github.io/tutos/dev/hy2foam/sod/#12-running" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px">&nbsp;&nbsp; 2. Running</a>
  <a href="https://hystrath.github.io/tutos/dev/hy2foam/sod/#13-solution" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px">&nbsp;&nbsp; 3. Solution</a>
  <a href="https://hystrath.github.io/tutos/dev/hy2foam/sod/#14-regression-testing" style="background-color:#FFE6E6; padding-top:4px">&nbsp;&nbsp; 4. Regression testing</a>
  <a href="https://hystrath.github.io/tutos/dev/hy2foam/sod/#2-subsonic-case" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><center><u>Supersonic case</u></center></a>
  <a href="https://hystrath.github.io/tutos/dev/hy2foam/sod/#21-case-setup" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px">&nbsp;&nbsp; 1. Case setup</a>
  <a href="https://hystrath.github.io/tutos/dev/hy2foam/sod/#22-running" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px">&nbsp;&nbsp; 2. Running</a>
  <a href="https://hystrath.github.io/tutos/dev/hy2foam/sod/#23-solution" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px">&nbsp;&nbsp; 3. Solution</a>
  <a href="https://hystrath.github.io/tutos/dev/hy2foam/sod/#24-regression-testing" style="background-color:#FFE6E6; padding-top:4px">&nbsp;&nbsp; 4. Regression testing</a>
  <a href="https://hystrath.github.io/tutos/dev/hy2foam/bluntedcone"><b>Blunted cone</b></a>
  <a href="https://hystrath.github.io/tutos/dev/hy2foam/ramcii/"><b>RAM C-II spacecraft</b></a>
  <a href="https://hystrath.github.io/tutos/dev/hy2foam/toc/#5-nasa-msl-forebody"><b>NASA MSL forebody</b></a>
  <a href="https://hystrath.github.io/tutos/dev/hy2foam/toc/#6-running-your-own-case"><b>Running your own case</b></a>
</div>

<span style="position: fixed;font-size:30px;cursor:pointer; margin:0px; top:60px;left:30px;" onclick="reopenNav()">&#9776;</span>

<script>
function openNav() {
  document.getElementById("mySidenav").style.width = "210px";
  document.getElementById("mySidenav").style.transition = "0s";
}

function closeNav() {
  document.getElementById("mySidenav").style.width = "0px";
  localStorage.removeItem('show_sidenav');
}

function reopenNav() {
  document.getElementById("mySidenav").style.width = "210px";
  document.getElementById("mySidenav").style.transition = "0.5s";
  localStorage.setItem("show_sidenav", true);
}

if (localStorage.getItem("show_sidenav")) openNav()
</script>
  
<p align="center">
  <img src="/docs/img/logos/hy2FoamLogo.png" width="210">
</p>

---

# Sod's shock tube

<p align="center">
One-dimensional | AUSM<sup>+</sup>-up flux scheme  
</p>

<p><img src="/docs/img/working_folder.png" width="40"> &nbsp; Working directory located <a href="https://github.com/hystrath/hyStrath/tree/OF-v2112/run/hyStrath/hy2Foam/sod"> here</a></p>


## Subsonic case

### 1. CASE SETUP

#### 1.1 Mesh
View of the structured _gmsh_ mesh provided in the <dirname>constant/backup-polyMesh</dirname> folder (each 5th line is represented in each direction). It is aligned with the bow shock, has 120,000 hexahedra, and the first layer height is equal to 2 x 10<sup>-6</sup> m.

#### 1.2 Case conditions

The blunted cone is a fully-diffuse surface set at a temperature of 297.2 K. The inert fluid is N<sub>2</sub> and the freestream conditions are given in <dirname>0/include/</dirname><dict>initialConditions</dict>:
<ul>
<li>Ma<sub>&#8734;</sub> = 11.3</li>
<li>Kn<sub>ov</sub> = 0.002</li>
<li><i>p</i><sub>&#8734;</sub> = 21.9 Pa</li>
<li><i>T</i><sub>tr, &#8734;</sub> = 144.4 K</li>
<li><i>T</i><sub>v, &#8734;</sub> = 144.4 K</li>
<li><b><i>U</i></b><sub>&#8734;</sub> = (2764.5 0 0) m/s</li>
</ul>

Smoluchowski temperature jump and Maxwell velocity slip boundary conditions are used.

#### 1.3 Thermo-chemical and transport models

This test case is using the following thermo-chemical and transport models:  

* thermally-perfect gas (excluding the electronic energy contribution)
* no chemical reactions
* two-temperature model
  + V—T energy transfer: Landau-Teller, tabulated Millikan-White coefficients, Park's correction
* species viscosity: power law
* species thermal conductivity: Eucken
* laminar flow

#### 1.4 Time controls

The initial time-step is set to 1 x 10<sup>-10</sup> s and the maximum CFL number is 0.5.
The simulation end time is equal to 0.0002 s.

#### 1.5 Time and flux schemes

The initial time-step is set to 1 x 10<sup>-10</sup> s and the maximum CFL number is 0.5.
The simulation end time is equal to 0.0002 s.

&nbsp;
### 2. RUNNING 

The following commands will execute <i>blockMesh</i>, <i>checkMesh</i> and <i>hy2Foam</i> in serial

```sh
./Allclean  
./Allrun
``` 

&nbsp;
### 3. SOLUTION

On the following graphs, the tutorial case results are given by the black solid lines:

<!--<p align="center">-->
<!--<img src="https://www.mdpi.com/aerospace/aerospace-03-00045/article_deploy/html/images/aerospace-03-00045-g002.png" width="800">-->
<!--</p>-->

<!--Stagnation line data (a–c) and surface coefficients (d–f) along the blunted cone:<br>-->
<!--(a) normalised temperature, (b) normalised mass density, (c) normalised velocity, (d) pressure coefficient, (e) friction coefficient, and (f) Stanton number.-->

&nbsp;
### 4. REGRESSION TESTING

Check that the results are matching the solution stored in <dirname>gnuplot/solution/</dirname>:

```sh
./Alltest
```   

<br>

## Supersonic case

### 1. CASE SETUP

&nbsp;
### 2. RUNNING 

&nbsp;
### 3. SOLUTION


&nbsp;
### 4. REGRESSION TESTING

Check that the results are matching the solution stored in <dirname>gnuplot/solution/</dirname>:

```sh
./Alltest
```   

<br>

---  

Contributor: Dr Vincent Casseau
