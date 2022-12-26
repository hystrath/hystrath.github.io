---
layout: page
title: Tutorials
subtitle: CFD Module - Fleming release
nav-short: true
---

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()"><i class='fa fa-times'></i></a>
  <header>TUTORIALS</header>
  <a href="https://hystrath.github.io/tutos/hy2foam/toc/"><center><img src="/docs/img/logos/hy2FoamLogo.png" width="60"></center></a>
  <a href="https://hystrath.github.io/tutos/hy2foam/heatbath"><b>Adiabatic heat bath</b></a>
  <a href="https://hystrath.github.io/tutos/hy2foam/bluntedcone"><b>Blunted cone</b></a>
  <a href="https://hystrath.github.io/tutos/hy2foam/ramcii" style="background-color:#FFCCCC"><b>RAM C-II spacecraft</b></a>
  <a href="https://hystrath.github.io/tutos/hy2foam/ramcii/#1-case-setup" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px">&nbsp;&nbsp; 1. Case setup</a>
  <a href="https://hystrath.github.io/tutos/hy2foam/ramcii/#2-running" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px">&nbsp;&nbsp; 2. Running</a>
  <a href="https://hystrath.github.io/tutos/hy2foam/ramcii/#3-flow-visualisations-in-paraview" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px">&nbsp;&nbsp; 3. Flow visualisations</a>
  <a href="https://hystrath.github.io/tutos/hy2foam/ramcii/#4-solution" style="background-color:#FFE6E6; padding-top:4px">&nbsp;&nbsp; 4. Solution</a>
  <a href="https://hystrath.github.io/tutos/hy2foam/toc/#4-nasa-msl-forebody"><b>NASA MSL forebody</b></a>
  <a href="https://hystrath.github.io/tutos/hy2foam/toc/#5-running-your-own-case"><b>Running your own case</b></a>
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

# RAM C-II spacecraft

<p align="center">
Axially-symmetric mesh | Weakly-ionised flow
</p>

<p><img src="/docs/img/working_folder.png" width="40"> &nbsp; Will soon be available</p>
<!--Working directory located <a href="https://github.com/hystrath/hyStrath/tree/master/run/hyStrath/hy2Foam/fireII/fireII_NRadia"> here</a>-->

<p><img src="/docs/img/publis.png" width="40"> &nbsp; See Section 5.3. <i>RAM-C Spacecraft</i> in <br> G. Yang, "Finite Element Simulation of Weakly Ionized Hypersonic Flows," Master's thesis, McGill University, Montreal (Canada), <b>2022</b> 
&nbsp; <a href="https://escholarship.mcgill.ca/downloads/bc386q61m?locale=en" target="_blank" style="color:orange"> [PDF→]</a></p>

### 1. CASE SETUP

#### 1.1 Geometry & Mesh

Geometry of the RAM C-II spacecraft

<p align="center">
  <img src="/docs/img/tutos/hy2Foam/tutorial-ramcii-geom.png" width="400">
</p>

Views of the structured mesh (entire domain and magnified view of the nose region) composed of 11,613 hexahedra with a first layer height equal to 1 x 10<sup>-5</sup> m.

<p align="center">
  <img src="/docs/img/tutos/hy2Foam/tutorial-ramcii-mesh2.png" width="100">
  <img src="/docs/img/tutos/hy2Foam/tutorial-ramcii-mesh1.png" width="500">
</p>

#### 1.2 Case conditions

The non-slip RAM C-II capsule's surface is maintained at a temperature of 1200 K. The freestream conditions are given in <dirname>0/include/</dirname><dict>initialConditions</dict>:
<ul>
<li>Ma<sub>&#8734;</sub> = 23.9</li>
<li>Kn<sub>ov</sub> = 0.0012</li>
<li>Re<sub>R<sub>n</sub></sub> = 0.975 x 10<sup>4</sup></li>
<li><i>p</i><sub>&#8734;</sub> = 19.719 Pa</li>
<li><i>T</i><sub>tr, &#8734;</sub> = 244 K</li>
<li><i>T</i><sub>ve, &#8734;</sub> = 244 K</li>
<li><b><i>U</i></b><sub>&#8734;</sub> = (7651 0 0) m/s</li>
<li><i>Y</i><sub>N<sub>2</sub>, &#8734;</sub> = 0.767</li>
<li><i>Y</i><sub>O<sub>2</sub>, &#8734;</sub> = 0.232</li>
</ul>


#### 1.3 Thermo-chemical and transport models

This test case is using the following thermo-chemical and transport models:  

* thermally-perfect gas (including electronic energy contribution)
* 7-species gas, Park 1993 chemistry dataset
* two-temperature model
  + V—T energy transfer: Landau-Teller, tabulated Millikan-White coefficients, Park's correction
  + H—e energy transfer: Appleton-Bray
  + chemistry-vibration coupling: Park TTv model
* species viscosity: Blottner
* species thermal conductivity: Eucken
* mixing rule: Wilke
* species diffusion: Lewis number = 1.4
* laminar flow


#### 1.4 Time controls

The initial time-step is set to 1 x 10<sup>-10</sup> s and the maximum CFL number is 0.2.
The simulation is run until convergence.

&nbsp;
### 2. RUNNING 

The following commands will execute <i>fluentMeshToFoam</i>, <i>checkMesh</i> and <i>hy2Foam</i> in serial

```sh
./Allclean  
./Allrun
``` 

To run <i>hy2Foam</i> in parallel (say on 8 CPUs), please first edit the <dictkey>numberOfSubdomains</dictkey> in the <dirname>system/</dirname><dict>decomposeParDict</dict> dictionary and type in

```sh
./Allclean  
./Allrun 8
``` 

&nbsp;
### 3. FLOW VISUALISATIONS IN PARAVIEW

<p align="center">
<img src="/docs/img/tutos/hy2Foam/tutorial-ramcii-umag.png" width="400">  
</p>

<p align="center">
<img src="/docs/img/tutos/hy2Foam/tutorial-ramcii-Ttr.png" width="400">  
</p>

&nbsp;
### 4. SOLUTION

On the following graphs, the tutorial case results are given by the red solid lines:

<p align="center">
<img src="/docs/img/tutos/hy2Foam/tutorial-ramcii-surfne.png" width="500">
</p>

<br>

---

<p><img src="/docs/img/publis.png" width="40"> Additional references</p>
<p>L. C. Scalabrin, "Numerical Simulation of Weakly Ionized Hypersonic Flow over Reentry Capsules," PhD thesis, University of Michigan, Ann Arbor (US), <b>2007</b> &nbsp; <a href="http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.453.3057&rep=rep1&type=pdf" target="_blank" style="color:orange"> [PDF→]</a></p>
<p>E. Farbar, I. D. Boyd, M. Kim, and A. Martin, "Investigation of the Effects of Electron Translational Nonequilibrium on Numerical Predictions of Hypersonic Flow Fields," <i>42nd AIAA Thermophysics Conference</i> (Honolulu, Hawaii, US, 27-30 June 2011), AIAA Paper 2011-3136, <b>2011</b> &nbsp; <a href="https://arc.aiaa.org/doi/10.2514/6.2011-3136" style="color:red"> [AIAA Portal→]</a></p>

<br>

---  

Contributors: Dr Vincent Casseau and Gan Yang
