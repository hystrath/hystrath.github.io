---
layout: page
title: Tutorials
subtitle: CFD Module - Fleming release
nav-short: true
---

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()"><i class='fa fa-times'></i></a>
  <header>TUTORIALS</header>
  <a href="https://hystrath.github.io/tutos-hy2foam"><center><img src="/docs/img/logos/hy2FoamLogo.png" width="60"></center></a>
  <a href="https://hystrath.github.io/tutos-hy2foam-heatbath" style="background-color:#FFCCCC"><b>Adiabatic heat bath</b></a>
  <a href="https://hystrath.github.io/tutos-hy2foam-heatbath/#1-case-setup" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px">&nbsp;&nbsp; 1. Case setup</a>
  <a href="https://hystrath.github.io/tutos-hy2foam-heatbath/#2-running" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px">&nbsp;&nbsp; 2. Running</a>
  <a href="https://hystrath.github.io/tutos-hy2foam-heatbath/#3-solution" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px">&nbsp;&nbsp; 3. Solution</a>
  <a href="https://hystrath.github.io/tutos-hy2foam-heatbath/#4-regression-testing" style="background-color:#FFE6E6; padding-top:4px">&nbsp;&nbsp; 4. Regression testing</a>
  <a href="https://hystrath.github.io/tutos-hy2foam-bluntedcone"><b>Blunted cone</b></a>
  <a href="https://hystrath.github.io/tutos-hy2foam-ramcii/"><b>RAM C-II spacecraft</b></a>
  <a href="https://hystrath.github.io/tutos-hy2foam/#4-nasa-msl-forebody"><b>NASA MSL forebody</b></a>
  <a href="https://hystrath.github.io/tutos-hy2foam/#5-running-your-own-case"><b>Running your own case</b></a>
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

# Adiabatic heat bath

<p align="center">
Zero-dimensional | Thermal non-equilibrium | Chemistry-vibration coupling  
</p>

<p><img src="/docs/img/working_folder.png" width="40"> &nbsp; Working directory located <a href="https://github.com/hystrath/hyStrath/tree/master/run/hyStrath/hy2Foam/heatBath"> here</a>.</p>

<p><img src="/docs/img/publis.png" width="40"> &nbsp; See Section 3.4. <i>Relaxation of a Chemically-Reacting Mixture</i> in <br> V. Casseau, R. C. Palharini, T. J. Scanlon, and R. E. Brown, "A Two-Temperature Open-Source CFD Model for Hypersonic Reacting Flows, Part One: Zero-Dimensional Analysis," <i>Aerospace</i>, vol. 3, no. 4, p. 34, <b>2016</b> &nbsp; <a href="http://www.mdpi.com/2226-4310/3/4/34/html" target="_blank" style="color:orange"> [Full HTML→]</a></p>  

### 1. CASE SETUP

#### 1.1 Mesh
The heat bath is composed of a single cubic cell of length 1 x 10<sup>-5</sup> m.  
All boundary patches are set to be of `empty` type.

#### 1.2 Initial conditions

The initial conditions are given in <dirname>0/include/</dirname><dict>initialConditions</dict>:
<ul>
<li><i>p</i><sup>0</sup> = 41,419.4 Pa</li>
<li><i>T</i><sup>0</sup><sub>tr</sub> = 30,000 K</li>
<li><i>T</i><sup>0</sup><sub>v</sub> = 1000 K</li>
<li><b><i>U</i></b><sup>0</sup> = (0 0 0) m/s</li>
<li><i>X</i><sup>0</sup><sub>N<sub>2</sub></sub> = 0.5</li>
<li><i>X</i><sup>0</sup><sub>N</sub> = 0.5</li>
</ul>

#### 1.3 Thermo-chemical models

This test case is using the following thermo-chemical models:  

* thermally-perfect gas (excluding the electronic energy contribution)
* 1 irreversible reaction (Park 1993)
* two-temperature model
  + V—T energy transfer: Landau-Teller, tabulated Millikan-White coefficients, Park's correction
  + chemistry-vibration coupling: Park TTv, preferential model

#### 1.4 Time controls

The time-step is constant and set to 1 x 10<sup>-9</sup> s and the simulation stops after 10,000 iterations.

&nbsp;
### 2. RUNNING
 
The following commands will execute <i>blockMesh</i>, <i>checkMesh</i> and <i>hy2Foam</i> in serial
 
```sh
./Allclean  
./Allrun
```

&nbsp;
### 3. SOLUTION

On the following graphs, the tutorial case results are given by the solid lines:

<p align="center">
  <img src="https://www.mdpi.com/aerospace/aerospace-03-00034/article_deploy/html/images/aerospace-03-00034-g007.png" width="400">
</p>

Influence of the chemistry-vibration model and chemical rate constants on a chemically-reacting N2−N heat bath: (a) temperature versus time, and (b) normalised number density versus time

&nbsp;
### 4. REGRESSION TESTING

Check that the results are matching the solution stored in <dirname>gnuplot/solution/</dirname>:
```sh
./Alltest
```  

<br>

---  

Contributor: Dr Vincent Casseau
