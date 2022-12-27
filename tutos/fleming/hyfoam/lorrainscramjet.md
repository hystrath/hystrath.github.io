---
layout: page
title: Tutorials
subtitle: CFD Module - Fleming release
nav-short: true
---

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()"><i class='fa fa-times'></i></a>
  <header>TUTORIALS</header>
  <a href="https://hystrath.github.io/tutos/fleming/hyfoam/toc/"><center><img src="/docs/img/logos/hyFoamLogo.png" width="50"></center></a>
  <a href="https://hystrath.github.io/tutos/fleming/hyfoam/laminarflatplatelts"><b>Mach 2 laminar flat plate (LTS)</b></a>
  <a href="https://hystrath.github.io/tutos/fleming/hyfoam/axisymmetrichb2"><b>Mach 9.59 HB2 configuration</b></a>
  <a href="https://hystrath.github.io/tutos/fleming/hyfoam/lorrainscramjet" style="background-color:#FFCCCC"><b>Lorrain's scramjet</b></a>
  <a href="https://hystrath.github.io/tutos/fleming/hyfoam/lorrainscramjet/#stage-1---fuel-off" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><center><u>Stage 1 - Fuel-off</u></center></a>
  <a href="https://hystrath.github.io/tutos/fleming/hyfoam/lorrainscramjet/#1-case-setup" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px">&nbsp;&nbsp;&nbsp;&nbsp; 1. Case setup</a>
  <a href="https://hystrath.github.io/tutos/fleming/hyfoam/lorrainscramjet/#2-running" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px">&nbsp;&nbsp;&nbsp;&nbsp; 2. Running</a>
  <a href="https://hystrath.github.io/tutos/fleming/hyfoam/lorrainscramjet/#3-flow-visualisations-in-paraview" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px">&nbsp;&nbsp;&nbsp;&nbsp; 3. Flow visualisations</a>
  <a href="https://hystrath.github.io/tutos/fleming/hyfoam/lorrainscramjet/#4-solution" style="background-color:#FFE6E6; padding-top:4px">&nbsp;&nbsp;&nbsp;&nbsp; 4. Solution</a>
<!--  <a href="https://hystrath.github.io/tutos/fleming/hyfoam/lorrainscramjet/#stage-2---frozen">&nbsp;&nbsp; Stage 2 - Frozen</a>-->
<!--  <a href="https://hystrath.github.io/tutos/fleming/hyfoam/lorrainscramjet/#stage-3---reacting-flow-field">&nbsp;&nbsp; Stage 2 - Reacting flow-field</a>-->
  <a href="https://hystrath.github.io/tutos/fleming/hy2foam/toc/#5-running-your-own-case"><b>Running your own case</b></a>
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

# Lorrain's scramjet

<p align="center">
Scramjet flow-field | RAS turbulence modelling  
</p>

<p><img src="/docs/img/working_folder.png" width="40"> &nbsp; Working directory located <a href="https://github.com/hystrath/hyStrath/tree/master/run/hyStrath/hyFoam/LorrainStageI"> here</a></p>

<p><img src="/docs/img/publis.png" width="40"> &nbsp; J.-J. O.E. Hoste, V. Casseau, M. Fossati, I. J. Taylor, and R. Gollan, "Numerical Modeling and Simulation of Supersonic Reacting Flows in Propulsion Systems by Open-Source Solvers," <i>21st AIAA International Space Planes and Hypersonic Systems and Technologies Conference</i> (Xiamen, China, 6-9 March 2017), AIAA Paper 2017-2411, <b>2017</b> &nbsp; <a href="http://eprints.gla.ac.uk/140369/1/140369.pdf" target="_blank" style="color:orange"> [PDF Preprint→]</a></p>


## Stage 1 - Fuel-off

### 1. CASE SETUP

#### 1.1 Geometry & Mesh

Lorrain's scamjet geometry

<p align="center">
  <img src="/docs/img/tutos/fleming/hyFoam/tutorial-hyfoam-lorrainscramjet-geom.png" width="700">
</p>

The mesh is composed of 322080 hexahedra, and the maximum first cell distance to physical walls is less than 5 x 10<sup>-6</sup> m ensuring that the first cell is located inside the viscous sublayer.

#### 1.2 Case conditions

The inflow (in) conditions of the <i>fuel-off</i> Lorrain scramjet case are:
<ul>
<li>Ma<sub>in</sub> = 7.32</li>
<!--<li>Re<sub>inflow</sub> = 2.1 x 10<sup>6</sup> m<sup>-1</sup></li>-->
<li><i>p</i><sub>in</sub> = 4100 Pa</li>
<li><i>T</i><sub>in</sub> = 370 K</li>
<li><b><i>U</i></b><sub>in</sub> = (2830 0 0) m/s</li>
<li><i>X</i><sub>N<sub>2</sub>, in</sub> = 0.79</li>
<li><i>X</i><sub>O<sub>2</sub>, in</sub> = 0.21</li>
<li><i>X</i><sub>H<sub>2</sub>, in</sub> = 0.0</li>
</ul>

The no-slip isothermal walls are maintained at a temperature of 300 K.

#### 1.3 Thermo-chemical and transport models

This test case is using the following thermo-chemical and transport models: 
 
* thermally-perfect gas (excluding the electronic energy contribution)
* no chemical reactions
* thermal equilibrium
* species viscosity & thermal conductivity: CEA2
* mixing rule: Wilke
* no species diffusion
* turbulent model: k-omega SST


#### 1.4 Time controls

The initial time-step is set to 1 x 10<sup>-10</sup> s and the maximum CFL number is 0.1.
The simulation end time is equal to 0.0013 s. 

&nbsp;
### 2. RUNNING 

The following commands will copy the mesh from <dirname>constant/backup-polyMesh</dirname> to <dirname>constant/polyMesh</dirname>, create the latest time folder <dirname>0.00127</dirname>, and execute <i>hyFoam</i> in serial

```sh
./Allclean  
./Allrun
```  

To run <i>hyFoam</i> in parallel (say on 4 CPUs), please first edit the <dictkey>numberOfSubdomains</dictkey> in the <dirname>system/</dirname><dict>decomposeParDict</dict> dictionary and type in

```sh
./Allclean  
./Allrun 4
``` 

&nbsp;
### 3. FLOW VISUALISATIONS IN PARAVIEW 

Contour plots of pressure for _hyFoam_ and Eilmer show a similar shock structure

<p align="center">
  <img src="/docs/img/tutos/fleming/hyFoam/tutorial-hyfoam-lorrainscramjet-pressure.png" width="700">
</p>

Shock induced boundary layer separation with contours of velocity and turbulent kinetic energy for both solvers

<p align="center">
  <img src="/docs/img/tutos/fleming/hyFoam/tutorial-hyfoam-lorrainscramjet-siblsep.png" width="700">
</p>

A comparison between the experimental Schlieren and CFD results (gradient of density) for the fuel-off conditions (scales do not match perfectly).

<p align="center">
  <img src="/docs/img/tutos/fleming/hyFoam/tutorial-hyfoam-lorrainscramjet-schlieren.png" width="500">
</p>


&nbsp;
### 4. SOLUTION

Static pressure along a streamline starting 1.5 mm from the combustor's entrance wall

<p align="center">
  <img src="/docs/img/tutos/fleming/hyFoam/tutorial-hyfoam-lorrainscramjet-pressurestreamline.png" width="500">
</p>

Temperature and velocity profiles at the entrance of the combustor section for Eilmer and _hyFoam_

<p align="center">
  <img src="/docs/img/tutos/fleming/hyFoam/tutorial-hyfoam-lorrainscramjet-tempvel.png" width="500">
</p>

Pressure coefficient along the wall

<p align="center">
  <img src="/docs/img/tutos/fleming/hyFoam/tutorial-hyfoam-lorrainscramjet-cp.png" width="500">
</p>

Close-up view of the pressure coefficient in the combustor section

<p align="center">
  <img src="/docs/img/tutos/fleming/hyFoam/tutorial-hyfoam-lorrainscramjet-cpcombustor.png" width="500">
</p>

<!--<br>-->

<!------->

<!--## Stage 2 - Frozen-->

<!--<br>-->

<!------->

<!--## Stage 3 - Reacting flow-field-->

<br>

---

<p><img src="/docs/img/publis.png" width="40"> Additional references</p>
<p><b><i>Eilmer3</i></b> is a research and educational simulation code for 2D and 3D gas dynamics designed by Dr Peter Jacobs, Dr Rowan Gollan, Dr Daniel Potter and others (University of Queensland, Australia) &nbsp; <a href="http://cfcfd.mechmining.uq.edu.au/docs/tools/eilmer/" target="_blank" style="color:orange"> [Eilmer3 Website→]</a></p>
<p><b><i>Eilmer3</i></b>, <b><i>Eilmer4</i></b> &nbsp; | &nbsp; J.-J. O.E. Hoste, "Scramjet Combustion Modeling using Eddy Dissipation Model," PhD thesis, University of Strathclyde, Glasgow (UK), <b>2018</b> &nbsp; <a href="https://github.com/hystrath/hyStrath/blob/master/doc/PhDthesis-jimmyjohnhoste.pdf" target="_blank" style="color:orange"> [PDF→]</a></p>
<p><b><i>rhoCentralFoam</i></b>, <b><i>Eilmer3</i></b>, <b><i>hyFoam</i></b> &nbsp; | &nbsp; D. Puorto, "Suitability of rhoCentralFoam for Scramjet Internal Flows," Master's thesis, University of Naples Federico II, Naples (Italy), <b>2017</b></p>

<br>

---  

Contributors: Dr Jimmy-John O.E. Hoste, Daniela Puorto, Dr Vincent Casseau
