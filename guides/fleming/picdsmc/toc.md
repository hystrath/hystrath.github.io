---
layout: page
title: Guides
subtitle: Hybrid Modules - Fleming release
nav-short: true
---

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()"><i class='fa fa-times'></i></a>
  <header>GUIDE — HYBD</header>
  <a href="https://hystrath.github.io/guides/fleming/picdsmc/thermophysical/"><b>A. THERMOPHYSICAL</b></a>
  <a href="https://hystrath.github.io/guides/fleming/picdsmc/thermophysical/#1-species-thermophysical-properties" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Species properties</span></a>
  <a href="https://hystrath.github.io/guides/fleming/picdsmc/thermophysical/#2-addingremoving-energy-modes"  style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) +/- energy modes</span></a>

  <a href="https://hystrath.github.io/guides/fleming/picdsmc/collision-dynamics"><b>B. COLLISION DYNAMICS</b></a>
  <a href="https://hystrath.github.io/guides/fleming/picdsmc/collision-dynamics/#1-binary-collision-model"  style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Binary collision model</span></a>
  <a href="https://hystrath.github.io/guides/fleming/picdsmc/collision-dynamics/#2-collision-partner-selection"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Collision partner selection</span></a>

  <a href="https://hystrath.github.io/guides/fleming/picdsmc/boundary-conditions"><b>C. BOUNDARY CONDITIONS</b></a>
  <a href="https://hystrath.github.io/guides/fleming/picdsmc/boundary-conditions/#1-generalities"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Generalities</span></a>
  <a href="https://hystrath.github.io/guides/fleming/picdsmc/boundary-conditions/#2-inflow--outflow-boundary-conditions"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Inflow & Outflow</span></a>
  <a href="https://hystrath.github.io/guides/fleming/picdsmc/boundary-conditions/#3-wall-boundary-conditions"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Wall</span></a>
  <a href="https://hystrath.github.io/guides/fleming/picdsmc/boundary-conditions/#4-cyclic-boundary-conditions"  style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) Cyclic</span></a>
  
  <a href="https://hystrath.github.io/guides/fleming/picdsmc/initialisation/"><b>D. INITIALISATION</b></a>
  <a href="https://hystrath.github.io/guides/fleming/picdsmc/initialisation/#1-the-pdinitialisedict-dictionary"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) <i>pdInitialiseDict</i></span></a>
  <a href="https://hystrath.github.io/guides/fleming/picdsmc/initialisation/#2-parcel-vs-real-particles"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Parcel vs. particles</span></a>
  <a href="https://hystrath.github.io/guides/fleming/picdsmc/initialisation/#3-creating-the-0-folder"  style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Creating the <i>0/</i> folder</span></a>
  
  <a href="https://hystrath.github.io/guides/fleming/picdsmc/sampling/"><b>E. SAMPLING</b></a>
  <a href="https://hystrath.github.io/guides/fleming/picdsmc/sampling/#1-the-fieldpropertiesdict-dictionary"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) <i>fieldPropertiesDict</i></span></a>
  <a href="https://hystrath.github.io/guides/fleming/picdsmc/sampling/#2-steady-state-simulations"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Steady-state simulations</span></a>
  <a href="https://hystrath.github.io/guides/fleming/picdsmc/sampling/#3-transient-simulations" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Transient simulations</span></a>
  
  <a href="https://hystrath.github.io/guides/fleming/picdsmc/toc/#f-monitoring--post-processing"><b>F. MONITORING & POST-PROCESSING</b></a>
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
## [A. Thermophysical](https://hystrath.github.io/guides/fleming/picdsmc/thermophysical/)
### [1) Species thermophysical properties](https://hystrath.github.io/guides/fleming/picdsmc/thermophysical/#1-species-thermophysical-properties)
### [2) Adding/removing energy modes](https://hystrath.github.io/guides/fleming/picdsmc/thermophysical/#2-addingremoving-energy-modes)
+ **[2.1 Disabling/enabling the rotational mode of a molecule](https://hystrath.github.io/guides/fleming/picdsmc/thermophysical/#21-disablingenabling-the-rotational-mode-of-a-molecule)**  
+ **[2.2 Disabling/enabling the vibrational mode of a molecule](https://hystrath.github.io/guides/fleming/picdsmc/thermophysical/#22-disablingenabling-the-vibrational-mode-of-a-molecule)**  


<div class="paragraph"><p><br>
<br></p></div>

---  
## [B. Collision dynamics](https://hystrath.github.io/guides/fleming/picdsmc/collision-dynamics)
### [1) Binary collision model](https://hystrath.github.io/guides/fleming/picdsmc/collision-dynamics/#1-binary-collision-model)
### [2) Collision partner selection](https://hystrath.github.io/guides/fleming/picdsmc/collision-dynamics/#2-collision-partner-selection)


<div class="paragraph"><p><br>
<br></p></div>

--- 
## [C. Boundary conditions](https://hystrath.github.io/guides/fleming/picdsmc/boundary-conditions)     
### [1) Generalities](https://hystrath.github.io/guides/fleming/picdsmc/boundary-conditions/#1-generalities) 
### [2) Inflow & Outflow boundary conditions](https://hystrath.github.io/guides/fleming/picdsmc/boundary-conditions/#2-inflow--outflow-boundary-conditions) 
+ **[2.1 Supersonic inflow](https://hystrath.github.io/guides/fleming/picdsmc/boundary-conditions/#21-supersonic-inflow)**  
+ **[2.2 Vacuum outlet](https://hystrath.github.io/guides/fleming/picdsmc/boundary-conditions/#22-vacuum-outlet)**  

### [3) Wall boundary conditions](https://hystrath.github.io/guides/fleming/picdsmc/boundary-conditions/#3-wall-boundary-conditions)  
+ **[3.1 Specular wall](https://hystrath.github.io/guides/fleming/picdsmc/boundary-conditions/#31-specular-wall)**  
+ **[3.2 Diffuse wall](https://hystrath.github.io/guides/fleming/picdsmc/boundary-conditions/#32-diffuse-wall)**  
+ **[3.3 Diffuse-neutralising wall](https://hystrath.github.io/guides/fleming/picdsmc/boundary-conditions/#33-diffuse-neutralising-wall)**  

### [4) Cyclic boundary conditions](https://hystrath.github.io/guides/fleming/picdsmc/boundary-conditions/#4-cyclic-boundary-conditions) 

<div class="paragraph"><p><br>
<br></p></div>

---  
## [D. Initialisation](https://hystrath.github.io/guides/fleming/picdsmc/initialisation/)
### [1) The _pdInitialiseDict_ dictionary](https://hystrath.github.io/guides/fleming/picdsmc/initialisation/#1-the-pdinitialisedict-dictionary) 
### [2) Parcel vs. real particles](https://hystrath.github.io/guides/fleming/picdsmc/initialisation/#2-parcel-vs-real-particles) 
### [3) Creating the _0/_ folder](https://hystrath.github.io/guides/fleming/picdsmc/initialisation/#3-creating-the-0-folder)  
+ **[3.1 Simulators data](https://hystrath.github.io/guides/fleming/picdsmc/initialisation/#31-simulators-data)**  
+ **[3.2 Initial volume fields](https://hystrath.github.io/guides/fleming/picdsmc/initialisation/#32-initial-volume-fields)**

<div class="paragraph"><p><br>
<br></p></div>

---  
## [E. Sampling](https://hystrath.github.io/guides/fleming/picdsmc/sampling/)
### [1) The _fieldPropertiesDict_ dictionary](https://hystrath.github.io/guides/fleming/picdsmc/sampling/#1-the-fieldpropertiesdict-dictionary) 
### [2) Steady-state simulations](https://hystrath.github.io/guides/fleming/picdsmc/sampling/#2-steady-state-simulations)  
### [3) Transient simulations](https://hystrath.github.io/guides/fleming/picdsmc/sampling/#3-transient-simulations)  

<div class="paragraph"><p><br>
<br></p></div>

---  
## F. Monitoring & Post-processing

<div class="paragraph"><p><br>
<br></p></div>

