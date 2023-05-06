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


<p><img src="/docs/img/publis.png" width="40"> G. A. Sod, "A Survey of Several Finite Difference Methods for Systems of Nonlinear Hyperbolic Conservation Laws", J. Comput. Phys., vol. 27, pp. 1-31, <b>1978</b>.</p>


## Subsonic case

<p><img src="/docs/img/working_folder.png" width="40"> &nbsp; Working directory located <a href="https://github.com/hystrath/hyStrath/tree/OF-v2112/run/hyStrath/hy2Foam/sod_subso"> here</a></p>

<a id="1-case-setup-subso"></a>
### 1. CASE SETUP

<a id="11-mesh-subso"></a>
#### 1.1 Mesh
The mesh is one-dimensional (`empty` patches for walls in the <i>y</i> and <i>z</i> directions) and a resolution of 10 mesh points per meter is used along <i>x</i>. Zero-gradients boundary conditions are implemented at both ends of the tube.

#### 1.2 Case conditions

A one-dimensional subsonic Sod tube of length <i>L</i> = 10 m is considered with initial conditions for the left (L) and right (R) states chosen to match the normalised values presented in the following Table. These conditions should yield from left to right an expansion wave (E), a contact discontinuity (C) and a shock wave (S).

| **State** | **Normalised density** | **Normalised pressure** | **Mach number** |
|---|:---:|:---:|:---:|
| Left (L) | 1 | 1 | 0 |
| Right (R) | 0.125 | 0.1 | 0 |

The diaphragm located in the middle of the tube breaks at <i>t</i> = 0 s.

<a id="13-thermo-models-subso"></a>
#### 1.3 Thermo-chemical and transport models
This test case is using the following thermo-chemical and transport models:  

* calorically-perfect nitrogen gas  
* inviscid fluid
* no chemical reactions
* single-temperature model
* laminar flow

<a id="14-time-controls-subso"></a>
#### 1.4 Time controls
The constant time-step is set to 1 µs and the simulation is run until <i>t</i> = 5 ms.

<a id="15-time-flux-schemes-subso"></a>
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
<a id="2-running-subso"></a>
### 2. RUNNING 
The following commands will execute <i>blockMesh</i>, <i>checkMesh</i>, <i>setFields</i> and <i>hy2Foam</i> in serial

```sh
./Allclean  
./Allrun
``` 

&nbsp;
<a id="3-solution-subso"></a>
### 3. SOLUTION
Length, density, pressure, and temperature are normalised as follows:

<p style="text-align:center">
    `x^&#8727; = \frac{x}{L}`,
</p>

<p style="text-align:center">
    `ρ^&#8727; = \frac{ρ - ρ_R}{ρ_L - ρ_R}`,
</p>

<p style="text-align:center">
    `p^&#8727; = \frac{p - p_R}{p_L - p_R}`,
</p>

<p style="text-align:center">
    `T^&#8727; = \frac{T - T_R}{T_L - T_R}`.
</p>

On the following graphs, the tutorial case results for density, pressure, temperature and Mach are given by the red symbols.
<i>hy2Foam</i>'s solution for the Kurganov-Noelle-Petrova (KNP) scheme is also shown as a reference.

<p align="center">
<img src="/docs/img/tutos/dev/hy2foam/sod/dens-subso.png" width="400">  
</p>

<p align="center">
<img src="/docs/img/tutos/dev/hy2foam/sod/pres-subso.png" width="400">  
</p>

<p align="center">
<img src="/docs/img/tutos/dev/hy2foam/sod/temp-subso.png" width="400">  
</p>

<p align="center">
<img src="/docs/img/tutos/dev/hy2foam/sod/mach-subso.png" width="400">  
</p>

&nbsp;
<a id="4-regression-testing-subso"></a>
### 4. REGRESSION TESTING
Check that the results are matching the solution stored in <dirname>gnuplot/solution/</dirname>:

```sh
./Alltest
```   

<br>

---
## Supersonic case

<p><img src="/docs/img/working_folder.png" width="40"> &nbsp; Working directory located <a href="https://github.com/hystrath/hyStrath/tree/OF-v2112/run/hyStrath/hy2Foam/sod_superso"> here</a></p>

<a id="1-case-setup-superso"></a>
### 1. CASE SETUP

#### 1.1 Mesh
See [subsonic case](#11-mesh-subso).  

#### 1.2 Case conditions
The shock tube case introduced in the previous section is simulated again for a different set of initial left and right state conditions resulting in a supersonic flow:

| **State** | **Normalised density** | **Normalised pressure** | **Mach number** |
|---|:---:|:---:|:---:|
| Left (L) | 1 | 1 | 0 |
| Right (R) | 0.01 | 0.01 | 0 |

#### 1.3 Thermo-chemical and transport models
See [subsonic case](#13-thermo-models-subso).  

#### 1.4 Time controls
See [subsonic case](#14-time-controls-subso).  

#### 1.5 Time and flux schemes
See [subsonic case](#15-time-flux-schemes-subso).  

&nbsp;
<a id="2-running-superso"></a>
### 2. RUNNING 
The following commands will execute <i>blockMesh</i>, <i>checkMesh</i>, <i>setFields</i> and <i>hy2Foam</i> in serial

```sh
./Allclean  
./Allrun
``` 

&nbsp;
<a id="3-solution-superso"></a>
### 3. SOLUTION
Because the left and right temperatures are equal, the normalised temperature is computed as

<p style="text-align:center">
    `T^&#8727; = \frac{T - T_R}{T_R}`.
</p>

On the following graphs, the tutorial case results for density, pressure, temperature and Mach are given by the red symbols:

<p align="center">
<img src="/docs/img/tutos/dev/hy2foam/sod/dens-superso.png" width="400">  
</p>

<p align="center">
<img src="/docs/img/tutos/dev/hy2foam/sod/pres-superso.png" width="400">  
</p>

<p align="center">
<img src="/docs/img/tutos/dev/hy2foam/sod/temp-superso.png" width="400">  
</p>

<p align="center">
<img src="/docs/img/tutos/dev/hy2foam/sod/mach-superso.png" width="400">  
</p>


&nbsp;
<a id="4-regression-testing-superso"></a>
### 4. REGRESSION TESTING
Check that the results are matching the solution stored in <dirname>gnuplot/solution/</dirname>:

```sh
./Alltest
```   

<br>

---  

Contributor: Dr Vincent Casseau
