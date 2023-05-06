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
  <a href="https://hystrath.github.io/tutos/dev/hy2foam/sod/#subsonic-case" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><center><u>Subsonic case</u></center></a>
  <a href="https://hystrath.github.io/tutos/dev/hy2foam/sod/#1-case-setup-subso" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px">&nbsp;&nbsp; 1. Case setup</a>
  <a href="https://hystrath.github.io/tutos/dev/hy2foam/sod/#2-running-subso" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px">&nbsp;&nbsp; 2. Running</a>
  <a href="https://hystrath.github.io/tutos/dev/hy2foam/sod/#3-solution-subso" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px">&nbsp;&nbsp; 3. Solution</a>
  <a href="https://hystrath.github.io/tutos/dev/hy2foam/sod/#4-regression-testing-subso" style="background-color:#FFE6E6; padding-top:4px">&nbsp;&nbsp; 4. Regression testing</a>
  <a href="https://hystrath.github.io/tutos/dev/hy2foam/sod/#supersonic-case" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><center><u>Supersonic case</u></center></a>
  <a href="https://hystrath.github.io/tutos/dev/hy2foam/sod/#1-case-setup-superso" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px">&nbsp;&nbsp; 1. Case setup</a>
  <a href="https://hystrath.github.io/tutos/dev/hy2foam/sod/#2-running-superso" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px">&nbsp;&nbsp; 2. Running</a>
  <a href="https://hystrath.github.io/tutos/dev/hy2foam/sod/#3-solution-superso" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px">&nbsp;&nbsp; 3. Solution</a>
  <a href="https://hystrath.github.io/tutos/dev/hy2foam/sod/#4-regression-testing-superso" style="background-color:#FFE6E6; padding-top:4px">&nbsp;&nbsp; 4. Regression testing</a>
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


## Subsonic case

<p><img src="/docs/img/working_folder.png" width="40"> &nbsp; Working directory located <a href="https://github.com/hystrath/hyStrath/tree/OF-v2112/run/hyStrath/hy2Foam/sod_subso"> here</a></p>

### 1. CASE SETUP
{: 1-case-setup-subso}

#### 1.1 Mesh
View of the structured _gmsh_ mesh provided in the <dirname>constant/backup-polyMesh</dirname> folder (each 5th line is represented in each direction). It is aligned with the bow shock, has 120,000 hexahedra, and the first layer height is equal to 2 x 10<sup>-6</sup> m.

#### 1.2 Case conditions

A one-dimensional subsonic Sod tube of length <i>L</i> = 10 m is considered with initial conditions for the left (L) and right (R) states chosen to match the normalised values presented in the following Table. These conditions should yield from left to right an expansion wave (E), a contact discontinuity (C) and a shock wave (S).

| **State** | **Normalised density** | **Normalised pressure** | **Mach number** |
|---|:---:|:---:|:---:|
| Left (L) | 1 | 1 | 0 |
| Right (R) | 0.125 | 0.1 | 0 |

The diaphragm located in the middle of the tube breaks at <i>t</i> = 0 s.


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

The constant time-step is set to 1 x 10<sup>-6</sup> s and the simulation is run until <i>t</i> = 5 ms.

#### 1.5 Time and flux schemes

The temporal and flux schemes used are the first-order implicit Euler time scheme and the AUSM<sup>+</sup>-up flux scheme, respectively.
The AUSM<sup>+</sup>-up model coefficients are given below.

```c++
fluxScheme            AUSM+up;

fluxSchemeCoefficients
{
    AUSM+upCoefficients
    {
        MachInf          1.0;
        
        alpha         0.1875;
        beta           0.125;
        sigma            1.0;
        Kp              0.25;
        Ku              0.75;
    }
}
```

&nbsp;
### 2. RUNNING 
{: 2-running-subso}

The following commands will execute <i>blockMesh</i>, <i>checkMesh</i>, <i>setFields</i> and <i>hy2Foam</i> in serial

```sh
./Allclean  
./Allrun
``` 

&nbsp;
### 3. SOLUTION
{: 3-solution-subso}

Length, density, pressure, and temperature are normalised as follows:

<p style="text-align:center">
    `x^\* = \frac{x}{L}`
</p>

<p style="text-align:center">
    `ρ^* = \frac{ρ - ρ_R}{ρ_L - ρ_R}`,
</p>

<p style="text-align:center">
    `p^* = \frac{p - p_R}{p_L - p_R}`,
</p>

<p style="text-align:center">
    `T^* = \frac{T - T_R}{T_L - T_R}`.
</p>

On the following graphs, the tutorial case results are given by the black solid lines:

<p align="center">
<img src="/docs/img/tutos/dev/hy2Foam/sod/dens-subso.png" width="400">  
</p>

<p align="center">
<img src="/docs/img/tutos/dev/hy2Foam/sod/pres-subso.png" width="400">  
</p>

<p align="center">
<img src="/docs/img/tutos/dev/hy2Foam/sod/temp-subso.png" width="400">  
</p>

<p align="center">
<img src="/docs/img/tutos/dev/hy2Foam/sod/mach-subso.png" width="400">  
</p>

<!--Stagnation line data (a–c) and surface coefficients (d–f) along the blunted cone:<br>-->
<!--(a) normalised temperature, (b) normalised mass density, (c) normalised velocity, (d) pressure coefficient, (e) friction coefficient, and (f) Stanton number.-->

&nbsp;
### 4. REGRESSION TESTING
{: 4-regression-testing-subso}

Check that the results are matching the solution stored in <dirname>gnuplot/solution/</dirname>:

```sh
./Alltest
```   

<br>

---
## Supersonic case

<p><img src="/docs/img/working_folder.png" width="40"> &nbsp; Working directory located <a href="https://github.com/hystrath/hyStrath/tree/OF-v2112/run/hyStrath/hy2Foam/sod_superso"> here</a></p>

### 1. CASE SETUP
{: 1-case-setup-superso}

#### 1.1 Mesh
View of the structured _gmsh_ mesh provided in the <dirname>constant/backup-polyMesh</dirname> folder (each 5th line is represented in each direction). It is aligned with the bow shock, has 120,000 hexahedra, and the first layer height is equal to 2 x 10<sup>-6</sup> m.

#### 1.2 Case conditions

The shock tube case introduced in the previous section is simulated again for a different set of initial left and right state conditions resulting in a supersonic flow:

| **State** | **Normalised density** | **Normalised pressure** | **Mach number** |
|---|:---:|:---:|:---:|
| Left (L) | 1 | 1 | 0 |
| Right (R) | 0.01 | 0.01 | 0 |

&nbsp;
### 2. RUNNING 
{: 2-running-superso}

The following commands will execute <i>blockMesh</i>, <i>checkMesh</i>, <i>setFields</i> and <i>hy2Foam</i> in serial

```sh
./Allclean  
./Allrun
``` 

&nbsp;
### 3. SOLUTION
{: 3-solution-superso}

Because the left and right temperatures are equal, the normalised temperature is computed as

<p style="text-align:center">
    `T^* = \frac{T - T_R}{T_R}`.
</p>

On the following graphs, the tutorial case results are given by the black solid lines:

<p align="center">
<img src="/docs/img/tutos/dev/hy2Foam/sod/dens-superso.png" width="400">  
</p>

<p align="center">
<img src="/docs/img/tutos/dev/hy2Foam/sod/pres-superso.png" width="400">  
</p>

<p align="center">
<img src="/docs/img/tutos/dev/hy2Foam/sod/temp-superso.png" width="400">  
</p>

<p align="center">
<img src="/docs/img/tutos/dev/hy2Foam/sod/mach-superso.png" width="400">  
</p>


&nbsp;
### 4. REGRESSION TESTING
{: 4-regression-testing-superso}

Check that the results are matching the solution stored in <dirname>gnuplot/solution/</dirname>:

```sh
./Alltest
```   

<br>

---  

Contributor: Dr Vincent Casseau
