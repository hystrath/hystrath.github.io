---
layout: page
title: How-tos
subtitle: DSMC Module - Fleming release
nav-short: true
---

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()"><i class='fa fa-times'></i></a>
  <header>HOW-TOS — DSMC</header>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-thermophysical/"><b>A. THERMOPHYSICAL</b></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-thermophysical/#1-species-thermophysical-properties" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Species properties</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-thermophysical/#2-addingremoving-energy-modes"  style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) +/- energy modes</span></a>

  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-collision-dynamics"><b>B. COLLISION DYNAMICS</b></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-collision-dynamics/#1-collision-partner-selection"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Collision partner selection</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-collision-dynamics/#2-binary-collision"  style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Binary collision</span></a>

  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-chemistry/"><b>C. CHEMISTRY</b></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-chemistry/#1-chemical-reaction-models"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Chemical reaction models</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-chemistry/#2-dissociation-reaction"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Dissociation reaction</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-chemistry/#3-exchange-reaction"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Exchange reaction</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-chemistry/#4-combined-reactions"  style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) Combined reactions</span></a>

  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-boundary-conditions"><b>D. BOUNDARY CONDITIONS</b></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-boundary-conditions/#1-generalities"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Generalities</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-boundary-conditions/#2-inflow--outflow-boundary-conditions"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Inflow & Outflow</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-boundary-conditions/#3-wall-boundary-conditions"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Wall</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-boundary-conditions/#4-cyclic-boundary-conditions"  style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) Cyclic</span></a>
  
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-coordinate-system/"><b>E. COORDINATE SYSTEM</b></a>
  
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-initialisation/"><b>F. INITIALISATION</b></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-initialisation/#1-the-dsmcinitialisedict-dictionary"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) <i>dsmcInitialiseDict</i></span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-initialisation/#2-dsmc-parcel-vs-real-particles"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Parcel vs. particles</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-initialisation/#3-creating-the-0-folder"  style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Creating the <i>0/</i> folder</span></a>
  
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-sampling/"><b>G. SAMPLING</b></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-sampling/#1-the-fieldpropertiesdict-dictionary"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) <i>fieldPropertiesDict</i></span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-sampling/#2-steady-state-simulations"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Steady-state simulations</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-sampling/#3-transient-simulations" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Transient simulations</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-sampling/#4-mean-free-path-computation"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) MFP computation</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-sampling/#5-resume-sampling" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 5) Resume sampling</span></a>
  
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-load-balancing/"><b>H. LOAD BALANCING</b></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming/#i-adaptive-mesh-refinement"><b>I. ADAPTIVE MESH REFINEMENT</b></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming/#j-monitoring--post-processing"><b>J. MONITORING & POST-PROCESSING</b></a>
</div>

<span style="position: fixed;font-size:30px;cursor:pointer; margin:0px; top:60px;left:30px;" onclick="reopenNav()">&#9776;</span>

<script>
function openNav() {
  document.getElementById("mySidenav").style.width = "225px";
  document.getElementById("mySidenav").style.transition = "0s";
}

function closeNav() {
  document.getElementById("mySidenav").style.width = "0px";
}

function reopenNav() {
  document.getElementById("mySidenav").style.width = "225px";
  document.getElementById("mySidenav").style.transition = "0.5s";
}

openNav()
</script>

&nbsp;  

# Table of contents

---  
## [A. Thermophysical](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-thermophysical/)
### [1) Species thermophysical properties](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-thermophysical/#1-species-thermophysical-properties)
### [2) Adding/removing energy modes](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-thermophysical/#2-addingremoving-energy-modes)
+ **[2.1 Disabling/enabling the rotational mode of a molecule](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-thermophysical/#21-disablingenabling-the-rotational-mode-of-a-molecule)**  
+ **[2.2 Disabling/enabling the vibrational mode of a molecule](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-thermophysical/#22-disablingenabling-the-vibrational-mode-of-a-molecule)**  
+ **[2.3 Disabling/enabling the electronic mode of a particle](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-thermophysical/#23-disablingenabling-the-electronic-mode-of-a-particle)** 


<div class="paragraph"><p><br>
<br></p></div>

---  
## [B. Collision dynamics](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-collision-dynamics)
### [1) Collision partner selection](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-collision-dynamics/#1-collision-partner-selection)
### [2) Binary collision](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-collision-dynamics/#2-binary-collision)

<div class="paragraph"><p><br>
<br></p></div>

---  
## [C. Chemistry](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-chemistry/)
### [1) Chemical reaction models](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-chemistry/#1-chemical-reaction-models)
### [2) Dissociation reaction](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-chemistry/#2-dissociation-reaction)
### [3) Exchange reaction](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-chemistry/#3-exchange-reaction)
### [4) Combined reactions](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-chemistry/#4-combined-reactions)

<div class="paragraph"><p><br>
<br></p></div>

--- 
## [D. Boundary conditions](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-boundary-conditions)     
### [1) Generalities](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-boundary-conditions/#1-generalities) 
### [2) Inflow & Outflow boundary conditions](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-boundary-conditions/#2-inflow--outflow-boundary-conditions) 
+ **[2.1 Supersonic inflow](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-boundary-conditions/#21-supersonic-inflow)**  
+ **[2.2 Vacuum outlet](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-boundary-conditions/#22-vacuum-outlet)**  

### [3) Wall boundary conditions](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-boundary-conditions/#3-wall-boundary-conditions)  
+ **[3.1 Specular wall](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-boundary-conditions/#31-specular-wall)**  
+ **[3.2 Diffuse wall](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-boundary-conditions/#32-diffuse-wall)**  
+ **[3.3 Diffuse-specular wall](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-boundary-conditions/#33-diffuse-specular-wall)**  

### [4) Cyclic boundary conditions](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-boundary-conditions/#4-cyclic-boundary-conditions) 

<div class="paragraph"><p><br>
<br></p></div>

---  
## [E. Coordinate system](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-coordinate-system/)

<div class="paragraph"><p><br>
<br></p></div>

---  
## [F. Initialisation](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-initialisation/)
### [1) The _dsmcInitialiseDict_ dictionary](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-initialisation/#1-the-dsmcinitialisedict-dictionary) 
### [2) DSMC parcel vs. real particles](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-initialisation/#2-dsmc-parcel-vs-real-particles) 
### [3) Creating the _0/_ folder](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-initialisation/#3-creating-the-0-folder)  
+ **[3.1 Simulators data](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-initialisation/#31-simulators-data)**  
+ **[3.2 Initial volume fields](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-initialisation/#32-initial-volume-fields)**

<div class="paragraph"><p><br>
<br></p></div>

---  
## [G. Sampling](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-sampling/)
### [1) The _fieldPropertiesDict_ dictionary](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-sampling/#1-the-fieldpropertiesdict-dictionary) 
### [2) Steady-state simulations](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-sampling/#2-steady-state-simulations)  
### [3) Transient simulations](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-sampling/#3-transient-simulations)  
### [4) Mean free path computation](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-sampling/#4-mean-free-path-computation)  
### [5) Resume sampling](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-sampling/#5-resume-sampling)  

<div class="paragraph"><p><br>
<br></p></div>

---  
## [H. Load balancing](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-load-balancing/)


<div class="paragraph"><p><br>
<br></p></div>

---  
## I. Adaptive mesh refinement


<div class="paragraph"><p><br>
<br></p></div>

---  
## J. Monitoring & Post-processing

<div class="paragraph"><p><br>
<br></p></div>

