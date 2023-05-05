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
  <a href="https://hystrath.github.io/tutos/dev/hyfoam/laminarflatplatelts"><b>Mach 2 laminar flat plate (LTS)</b></a>
  <a href="https://hystrath.github.io/tutos/dev/hyfoam/axisymmetrichb2" style="background-color:#FFCCCC"><b>Mach 9.59 HB2 configuration</b></a>
  <a href="https://hystrath.github.io/tutos/dev/hyfoam/axisymmetrichb2/#1-case-setup" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px">&nbsp;&nbsp; 1. Case setup</a>
  <a href="https://hystrath.github.io/tutos/dev/hyfoam/axisymmetrichb2/#2-running" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px">&nbsp;&nbsp; 2. Running</a>
  <a href="https://hystrath.github.io/tutos/dev/hyfoam/axisymmetrichb2/#3-monitoring" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px">&nbsp;&nbsp; 3. Monitoring</a>
  <a href="https://hystrath.github.io/tutos/dev/hyfoam/axisymmetrichb2/#4-flow-visualisations-in-paraview" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px">&nbsp;&nbsp; 4. Flow visualisations</a>
  <a href="https://hystrath.github.io/tutos/dev/hyfoam/axisymmetrichb2/#5-post-processing" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px">&nbsp;&nbsp; 5. Post-processing</a>
  <a href="https://hystrath.github.io/tutos/dev/hyfoam/axisymmetrichb2/#6-solution" style="background-color:#FFE6E6; padding-top:4px">&nbsp;&nbsp; 6. Solution</a>
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

# Mach 9.59 HB2 configuration  

<p align="center">
Axially-symmetric flow-field | Cold hypersonics
</p>

<p><img src="/docs/img/working_folder.png" width="40"> &nbsp; Working directory located <a href="https://github.com/hystrath/hyStrath/tree/master/run/hyStrath/hyFoam/axisymmetric-HB2"> here</a></p>

<p><img src="/docs/img/publis.png" width="40"> &nbsp; J.-J. O.E. Hoste and V. Casseau, "Verification and Validation of <i>hyFoam</i> for Supersonic External Flows," TechReport-HS1, <b>05/2021</b> &nbsp; <a href="https://github.com/hystrath/hyStrath/blob/master/doc/TechReport-HS1-hostecasseau.pdf" target="_blank" style="color:orange"> [PDF→]</a></p>

### 1. CASE SETUP

#### 1.1 Geometry & Mesh

Geometry of the HB-2 flare (_D_ is equal 0.1 m)

<p align="center">
<img src="/docs/img/tutos/fleming/hyFoam/axisymmetricHB2/HB2_geom.png" width="500">  
</p>

Views of the 2-D axisymmetric mesh (entire domain and magnified view of the nose region) modelled as a wedge

<p align="center">
<img src="/docs/img/tutos/fleming/hyFoam/axisymmetricHB2/meshFull.png" width="400">  
<img style="margin-top:50px;" src="/docs/img/tutos/fleming/hyFoam/axisymmetricHB2/meshNose.png" width="370">
</p>

The structured mesh is aligned with the bow shock in the nose region, has 141,100 cells, and the first layer height is equal to 1 x 10<sup>-5</sup> m.

#### 1.2 Case conditions

The HB2 no-slip isothermal wall is maintained at a temperature of 300 K.
The fluid is _Air_ and modelled as a single inert species.
The freestream conditions are given in <dirname>0/include/</dirname><dict>initialConditions</dict>:
<ul>
<li>Ma<sub>&#8734;</sub> = 9.59</li>
<li>Re<sub>&#8734;</sub> = 2.1 x 10<sup>6</sup> m<sup>-1</sup></li>
<li><i>p</i><sub>&#8734;</sub> = 75 Pa</li>
<li><i>T</i><sub>&#8734;</sub> = 52 K</li>
<li><b><i>U</i></b><sub>&#8734;</sub> = (1386.2 0 0) m/s</li>
</ul>

#### 1.3 Thermo-chemical and transport models

This test case is using the following thermo-chemical and transport models:

* calorically perfect gas
* species viscosity: Sutherland
* species thermal conductivity: Eucken<
* laminar flow

#### 1.4 Time controls

The initial time-step is set to 1 x 10<sup>-7</sup> s and the maximum CFL number is 0.5.
The simulation end time is equal to 0.0155 s. 

&nbsp;
### 2. RUNNING

The following commands will copy the mesh from <dirname>constant/backup-polyMesh</dirname> to <dirname>constant/polyMesh</dirname>, create the latest time folder <dirname>0.016</dirname>, and execute <i>hyFoam</i> in serial
  
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

&nbsp;
### 4. FLOW VISUALISATIONS IN PARAVIEW 

<p align="center">
<img src="/docs/img/tutos/fleming/hyFoam/axisymmetricHB2/fieldMach.png" width="600">
<img style="margin-top:50px;" src="/docs/img/tutos/fleming/hyFoam/axisymmetricHB2/fieldTt.png" width="600">
</p>

&nbsp;
### 5. POST-PROCESSING

```sh
gnuplot gnuplot/monitorCd
gnuplot gnuplot/monitorIntegratedWallHeatFlux
```  

&nbsp;
### 6. SOLUTION

Wall heat flux along the HB2 surface (_L_ is the body length that is equal to 0.49 m)

<p align="center">
<img src="/docs/img/tutos/fleming/hyFoam/axisymmetricHB2/wallHeatFlux.png" width="550">
</p>


<br>

---  

Contributors: Dr Jimmy-John O.E. Hoste, Dr Daniel E.R. Espinoza, Dr Vincent Casseau
