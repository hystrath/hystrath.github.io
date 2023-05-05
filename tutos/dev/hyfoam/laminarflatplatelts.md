---
layout: page
title: Tutorials
subtitle: CFD Module - Dev release
nav-short: true
---

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()"><i class='fa fa-times'></i></a>
  <header>TUTORIALS</header>
  <a href="https://hystrath.github.io/tutos/dev/hyfoam/toc/"><center><img src="/docs/img/logos/hyFoamLogo.png" width="50"></center></a>
  <a href="https://hystrath.github.io/tutos/dev/hyfoam/laminarflatplatelts" style="background-color:#FFCCCC"><b>Mach 2 laminar flat plate (LTS)</b></a>
  <a href="https://hystrath.github.io/tutos/dev/hyfoam/laminarflatplatelts/#1-case-setup" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px">&nbsp;&nbsp; 1. Case setup</a>
  <a href="https://hystrath.github.io/tutos/dev/hyfoam/laminarflatplatelts/#2-running" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px">&nbsp;&nbsp; 2. Running</a>
  <a href="https://hystrath.github.io/tutos/dev/hyfoam/laminarflatplatelts/#3-monitoring" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px">&nbsp;&nbsp; 3. Monitoring</a>
  <a href="https://hystrath.github.io/tutos/dev/hyfoam/laminarflatplatelts/#4-flow-visualisations-in-paraview" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px">&nbsp;&nbsp; 4. Flow visualisations</a>
  <a href="https://hystrath.github.io/tutos/dev/hyfoam/laminarflatplatelts/#5-post-processing" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px">&nbsp;&nbsp; 5. Post-processing</a>
  <a href="https://hystrath.github.io/tutos/dev/hyfoam/laminarflatplatelts/#6-solution" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px">&nbsp;&nbsp; 6. Solution</a>
  <a href="https://hystrath.github.io/tutos/dev/hyfoam/laminarflatplatelts/#7-regression-testing" style="background-color:#FFE6E6; padding-top:4px">&nbsp;&nbsp; 7. Regression testing</a>
  <a href="https://hystrath.github.io/tutos/dev/hyfoam/axisymmetrichb2"><b>Mach 9.59 HB2 configuration</b></a>
  <a href="https://hystrath.github.io/tutos/dev/hyfoam/lorrainscramjet"><b>Lorrain's scramjet</b></a>
  <a href="https://hystrath.github.io/tutos/dev/hy2foam/toc/#5-running-your-own-case"><b>Running your own case</b></a>
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
  <img src="/docs/img/logos/hyFoamLogo.png" width="200">
</p>

---

# Mach 2 laminar flat plate (LTS)

<p align="center">
Attached shock wave | Laminar flow  | Local Time Stepping
</p>

<p><img src="/docs/img/working_folder.png" width="40"> &nbsp; Working directory located <a href="https://github.com/hystrath/hyStrath/tree/OF-v2112/run/hyStrath/hyFoam/laminarFlatPlateLTS"> here</a></p>

<p><img src="/docs/img/publis.png" width="40"> &nbsp; J.-J. O.E. Hoste and V. Casseau, "Verification and Validation of <i>hyFoam</i> for Supersonic External Flows," TechReport-HS1, <b>05/2021</b> &nbsp; <a href="https://github.com/hystrath/hyStrath/blob/OF-v2112/doc/TechReport-HS1-hostecasseau.pdf" target="_blank" style="color:orange"> [PDF→]</a></p>

### 1. CASE SETUP

#### 1.1 Mesh

View of the structured mesh created using _blockMesh_   

<p align="center">
<img src="/docs/img/tutos/fleming/hyFoam/laminarFlatPlateLTS/mesh.png" width="400">
</p>

It is composed of 128,136 hexahedra and has a geometric progression ratio of 2 in both directions. 

#### 1.2 Case conditions

The 0.1-meter plate is maintained at a temperature of 600 K.  
The freestream conditions are given in <dirname>0/include/</dirname><dict>initialConditions</dict>:

<ul>
<li>Ma<sub>&#8734;</sub> = 2</li>
<li>Re<sub>&#8734;</sub> = 500</li>
<li><i>p</i><sub>&#8734;</sub> = 114.46 Pa</li>
<li><i>T</i><sub>&#8734;</sub> = 300 K</li>
<li><b><i>U</i></b><sub>&#8734;</sub> = (694.55 0 0) m/s</li>
<li><i>Y</i><sub>N<sub>2</sub>, &#8734;</sub> = 0.76708</li>
<li><i>Y</i><sub>O<sub>2</sub>, &#8734;</sub> = 0.23292</li>
</ul>

#### 1.3 Thermo-chemical and transport models

This test case is using the following thermo-chemical and transport models:
<ul>
<li>no vibrational nor electronic energy (calorically perfect gas)</li>
<li>no chemical reactions</li>
<li>thermal equilibrium</li>
<li>species viscosity: Blottner</li>
<li>species thermal conductivity: Eucken</li>
<li>no species diffusion</li>
<li>laminar flow</li>
</ul>

#### 1.4 Time controls

The initial time-step is set to 1 x 10<sup>-9</sup> s and the maximum CFL number is 0.5.
The simulation end time is equal to 5 x 10<sup>-5</sup> s. Local time stepping is used.

&nbsp;
### 2. RUNNING

The following commands will execute <i>blockMesh</i>, <i>checkMesh</i> and <i>hyFoam</i> in serial
 
```sh
./Allclean  
./Allrun
```

To run <i>hyFoam</i> in parallel (say on 8 CPUs), please first edit the <dictkey>numberOfSubdomains</dictkey> in the <dirname>system/</dirname><dict>decomposeParDict</dict> dictionary and type in

```sh
./Allclean  
./Allrun 8
``` 

&nbsp;
### 3. MONITORING

```sh
gnuplot gnuplot/monitorResiduals
```   

<p align="center">
<img src="/docs/img/tutos/fleming/hyFoam/laminarFlatPlateLTS/residuals.png" width="400">
</p>

&nbsp;
### 4. FLOW VISUALISATIONS IN PARAVIEW

<p align="center">
<img src="/docs/img/tutos/fleming/hyFoam/laminarFlatPlateLTS/fieldTt.gif" width="600">
<img style="margin-top:50px;" src="/docs/img/tutos/fleming/hyFoam/laminarFlatPlateLTS/fieldMach.gif" width="600">  
</p>

&nbsp;
### 5. POST-PROCESSING

```sh
gnuplot gnuplot/monitorCd   
gnuplot gnuplot/monitorIntegratedWallHeatFlux  
```

<p align="center">
<img src="/docs/img/tutos/fleming/hyFoam/laminarFlatPlateLTS/dragCoefficient.png" width="450">
<img style="margin-top:20px;" src="/docs/img/tutos/fleming/hyFoam/laminarFlatPlateLTS/integratedWallHeatFlux.png" width="450">
</p>

&nbsp;
### 6. SOLUTION

Sampling temperature, pressure, and velocity along a line normal to the plate and located at _x_ = 0.01 m away from the leading edge (_h_ is the boundary layer height, set to 4 mm)  

<p align="center">
<img src="/docs/img/tutos/fleming/hyFoam/laminarFlatPlateLTS/temperature.png" width="450">
<img style="margin-top:20px;" src="/docs/img/tutos/fleming/hyFoam/laminarFlatPlateLTS/pressure.png" width="450">  
<img style="margin-top:20px;" src="/docs/img/tutos/fleming/hyFoam/laminarFlatPlateLTS/velocity.png" width="450">
</p>

The small shift in normalised pressure is the result of having 2 distinct species (N2 and O2) as opposed to modelling air as being a single species.

&nbsp;
### 7. REGRESSION TESTING

Check that the results are matching the solution stored in <dirname>gnuplot/solution/</dirname> within a given tolerance:

```sh
./Alltest
``` 

<br>

---  

Contributors: Dr Jimmy-John O.E. Hoste, Dr Daniel E.R. Espinoza, Dr Vincent Casseau
