---
layout: page
title: How-tos
subtitle: CFD Module - Dev release
nav-short: true
---

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()"><i class='fa fa-times'></i></a>
  <header>HOW-TOS — CFD</header>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-thermophysical/"><b>A. THERMOPHYSICAL</b></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-thermophysical/#1-species-thermophysical-properties" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Species thermo props</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-thermophysical/#2-addingremoving-energy-modes" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) +/- energy modes</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-thermophysical/#3-choosing-a-thermodem-dictionary" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) <i>thermoDEM</i> dictionary</span></a>

  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-transport/"><b>B. TRANSPORT</b></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-transport/#1-species-shear-viscosity-and-thermal-conductivity" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Species transport props</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-transport/#2-mixing-rules" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Mixing rules</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-transport/#3-mass-diffusion" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Mass diffusion</span></a>

  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-chemistry/"><b>C. CHEMISTRY</b></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-chemistry/#1-multi-species-flow" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Multi-species flow</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-chemistry/#2-non-reacting-flow" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Non-reacting flow</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-chemistry/#3-chemically-reacting-flow" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Chemically-reacting flow</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-chemistry/#4-to-go-further-chemistry-vibration-coupling" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) To go further</span></a>
  
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-nonequilibrium/"><b>D. NONEQUILIBRIUM</b></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-nonequilibrium/#1-thermal-equilibrium" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Thermal equilibrium</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-nonequilibrium/#2-thermal-non-equilibrium" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Thermal non-equilibrium</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-nonequilibrium/#3-mean-free-path-and-breakdown-parameter" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) MFP & Breakdown</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-nonequilibrium/#4-chemistry-vibration-coupling" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) Chem.-vib. coupling</span></a>
  
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-turbulence/"><b>E. TURBULENCE</b></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-turbulence/#1-laminar-flow-simulation" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Laminar</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-turbulence/#2-turbulent-flow-simulation" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Turbulent</span></a>
  
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-mhd/"><b>F. MHD</b></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-mhd/#1-enablingdisabling-mhd" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Enabling/disabling MHD</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-mhd/#2-mhd-models" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) MHD models</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-mhd/#3-electrical-conductivity-models" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Electrical conductivity</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-mhd/#4-hall-parameter" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) Hall parameter</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-mhd/#5-creation-of-an-initial-magnetic-field-and-electric-potential" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 5) Initial <i>B</i> & electric pot.</span></a>


  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-initial-conditions/"><b>G. INITIAL CONDITIONS</b></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-initial-conditions/#1-the-include-sub-folder" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) The <i>include/</i> sub-folder</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-initial-conditions/#2-species-mass-or-molar-fractions" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Mass or molar fractions</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-initial-conditions/#3-temperature-fields" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Temperature fields</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-initial-conditions/#4-velocity-field" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) Velocity field</span></a>
  
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-advanced/"><b>H. ADVANCED</b></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-advanced/#1-local-time-stepping" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Local time stepping</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-advanced/#2-on-the-fly-dictionary-editing" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) On-the-fly editing</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-advanced/#3-bounding-the-temperature-field" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Bounding the temperature</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-advanced/#4-the-hylight-switch" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) The <i>hyLight</i> switch</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-advanced/#5-adaptive-mesh-refinement" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 5) Adaptive mesh refinement</span></a>
  
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-monitoring-post-processing"><b>I. MONITORING & POST-PROCESSING</b></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-monitoring-post-processing/#1-monitoring" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Monitoring</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-monitoring-post-processing/#2-post-processing" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Post-processing</span></a>
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

These how-tos are based on the working folder located [here](https://github.com/vincentcasseau/hyStrath/tree/master/run/hyStrath/hy2Foam/genericCase).  

# Table of contents

---  
## [A. Thermophysical](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-thermophysical/)
### [1) Species thermophysical properties](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-thermophysical/#1-species-thermophysical-properties)
### [2) Adding/removing energy modes](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-thermophysical/#2-addingremoving-energy-modes)
+ **[2.1 Disabling/enabling the vibrational mode of a molecule](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-thermophysical/#21-disablingenabling-the-vibrational-mode-of-a-molecule)**  
+ **[2.2 Disabling/enabling the electronic mode of a particle](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-thermophysical/#22-disablingenabling-the-electronic-mode-of-a-particle)**  

### [3) Choosing a thermoDEM dictionary](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-thermophysical/#3-choosing-a-thermodem-dictionary)

<br>

---  
## [B. Transport](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-transport/)
### [1) Species transport properties](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-transport/#1-species-shear-viscosity-and-thermal-conductivity)
+ **[1.1 Inviscid simulation](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-transport/#11-inviscid-simulation)**  
+ **[1.2 Viscous simulation with constant shear viscosity and thermal conductivity](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-transport/#12-viscous-simulation-with-constant-shear-viscosity-and-thermal-conductivity)**  
+ **[1.3 Other transport models](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-transport/#13-other-transport-models)**  
+ **[1.4 Print species shear viscosity and thermal conductivity](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-transport/#14-print-species-shear-viscosity-and-thermal-conductivity)**  

### [2) Mixing rules](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-transport/#2-mixing-rules)  

### [3) Mass diffusion](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-transport/#3-mass-diffusion)  
+ **[3.1 Disable multi-species diffusion](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-transport/#31-disable-multi-species-diffusion)**  
+ **[3.2 Lewis number model](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-transport/#32-lewis-number-model)**  
+ **[3.3 Fick's law and binary diffusion models](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-transport/#33-ficks-law-and-binary-diffusion-models)**  
+ **[3.4 SCEBD model](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-transport/#34-scebd-model)**  
+ **[3.5 Additional features (to Fick and SCEBD models)](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-transport/#35-additional-features-to-fick-and-scebd-models)**  

<br>

---  
## [C. Chemistry](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-chemistry/)
### [1) Multi-species flow](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-chemistry/#1-multi-species-flow)
+ **[1.1 The _chemDicts/_ folder](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-chemistry/#11-the-chemdicts-folder)**  
+ **[1.2 Adding/deleting species](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-chemistry/#12-addingdeleting-species)** 
+ **[1.3 Printing species quantities](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-chemistry/#13-printing-species-quantities)**  

### [2) Non-reacting flow](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-chemistry/#2-non-reacting-flow)

### [3) Chemically-reacting flow](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-chemistry/#3-chemically-reacting-flow)
+ **[3.1 Enable chemistry](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-chemistry/#31-enable-chemistry)**  
+ **[3.2 Implement a chemical reaction](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-chemistry/#32-implementing-a-chemical-reaction)**  
      - [3.2.1 Forward reaction](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-chemistry/#321-forward-reaction)  
      - [3.2.2 Reverse reaction](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-chemistry/#322-reverse-reaction)  
      - [3.2.3 Third-body interaction](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-chemistry/#323-third-body-interaction)  
+ **[3.3 Increase robustness](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-chemistry/#33--increase-robustness)**  

### [4) To go further: chemistry-vibration coupling](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-chemistry/#4-to-go-further-chemistry-vibration-coupling)

<br>

--- 
## [D. Nonequilibrium](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-nonequilibrium/)
### [1) Thermal equilibrium](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-nonequilibrium/#1-thermal-equilibrium)

### [2) Thermal non-equilibrium](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-nonequilibrium/#2-thermal-non-equilibrium)
+ **[2.1 Single vibro-electronic energy pool](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-nonequilibrium/#21-single-vibro-electronic-energy-pool)**  
+ **[2.2 Multiple vibro-electronic energy pools](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-nonequilibrium/#22-multiple-vibro-electronic-energy-pools)** 

### [3) Mean free path and breakdown parameter](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-nonequilibrium/#3-mean-free-path-and-breakdown-parameter)  
+ **[3.1 Mean free path](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-nonequilibrium/#31-mean-free-path)**    
+ **[3.2 Knudsen number](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-nonequilibrium/#32-knudsen-number)**  
      - [3.2.1 Overall Knudsen number](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-nonequilibrium/#321-overall-knudsen-number)  
      - [3.2.2 Breakdown parameter: gradient-length Knudsen number](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-nonequilibrium/#322-breakdown-parameter-gradient-length-knudsen-number)  

### [4) Chemistry-vibration coupling](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-nonequilibrium/#4-chemistry-vibration-coupling)  
+ **[4.1 Park TTv model](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-nonequilibrium/#41-park-ttv-model)**  
      - [4.1.1 General settings](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-nonequilibrium/#411-general-settings)  
      - [4.1.2 Reactions dictionary](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-nonequilibrium/#412-reactions-dictionary)  
+ **[4.2 Coupled vibration-dissociation-vibration (CVDV) model](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-nonequilibrium/#42-coupled-vibration-dissociation-vibration-cvdv-model)**       

<br>

---  
## [E. Turbulence](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-turbulence/)
### [1) Laminar flow simulation](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-turbulence/#1-laminar-flow-simulation) 
 
### [2) Turbulent flow simulation](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-turbulence/#2-turbulent-flow-simulation) 

<br>

---  
## [F. MHD](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-mhd/)

### [1) Enabling/disabling MHD](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-mhd/#1-enablingdisabling-mhd)

### [2) MHD models](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-mhd/#2-mhd-models)  
+ **[2.1 Low magnetic Reynolds number model](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-mhd/#21-low-magnetic-reynolds-number-model)**  

### [3) Electrical conductivity models](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-mhd/#3-electrical-conductivity-models)  
+ **[3.1 Constant electrical conductivity](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-mhd/#31-constant-electrical-conductivity)**  
+ **[3.2 Bush](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-mhd/#32-bush)**  
+ **[3.3 Chapman-Cowling](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-mhd/#33-chapman-cowling)**  
+ **[3.4 Raizer](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-mhd/#34-raizer)**  
+ **[3.5 Spitzer-Harm](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-mhd/#35-spitzer-harm)**  

### [4) Hall parameter](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-mhd/#4-hall-parameter)  

### [5) Creation of an initial magnetic field and electric potential](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-mhd/#5-creation-of-an-initial-magnetic-field-and-electric-potential)  
<br>

---  
## [G. Initial conditions](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-initial-conditions/)

### [1) The _include/_ sub-folder](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-initial-conditions/#1-the-include-sub-folder)

### [2) Species mass or molar fractions](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-initial-conditions/#2-species-mass-or-molar-fractions)  
+ **[2.1 Non-catalytic wall](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-initial-conditions/#21-non-catalytic-wall)**  
+ **[2.2 Super-catalytic wall](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-initial-conditions/#22-super-catalytic-wall)**

### [3) Temperature fields](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-initial-conditions/#3-temperature-fields)  
+ **[3.1 Trans-rotational temperature](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-initial-conditions/#31-trans-rotational-temperature)**  
+ **[3.2 Vibro-electronic temperature](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-initial-conditions/#32-vibro-electronic-temperature)**  
      - [3.2.1 Single vibro-electronic energy pool formulation](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-initial-conditions/#321-single-vibro-electronic-energy-pool-formulation)  
      - [3.2.2 Multiple vibro-electronic energy pools formulation](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-initial-conditions/#322-multiple-vibro-electronic-energy-pools-formulation)   
 
### [4) Velocity field](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-initial-conditions/#4-velocity-field)  
+ **[4.1 Maxwell velocity slip](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-initial-conditions/#41-maxwell-velocity-slip)**  
+ **[4.2 Linear inlet ramp](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-initial-conditions/#42-linear-inlet-ramp)**  

<br>

---  
## [H. Advanced](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-advanced/)

### [1) Local time stepping](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-advanced/#1-local-time-stepping)  

### [2) On-the-fly dictionary editing](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-advanced/#2-on-the-fly-dictionary-editing)  

### [3) Bounding the temperature field](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-advanced/#3-bounding-the-temperature-field) 

### [4) The _hyLight_ switch](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-advanced/#4-the-hylight-switch)   

### [5) Adaptive mesh refinement](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-advanced/#5-adaptive-mesh-refinement)  

<br>

---  
## [I. Monitoring & Post-processing](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-monitoring-post-processing)

### [1) Monitoring](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-monitoring-post-processing/#1-monitoring)  
+ **[1.1 Wall heat flux](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-monitoring-post-processing/#11-wall-heat-flux)**  
+ **[1.2 Wall shear stress](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-monitoring-post-processing/#12-wall-shear-stress)**
+ **[1.3 Forces](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-monitoring-post-processing/#13-forces)**  
+ **[1.4 Residuals](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-monitoring-post-processing/#14-residuals)**  

### [2) Post-processing](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-monitoring-post-processing/#2-post-processing)  
+ **[2.1 Pressure coefficient](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-monitoring-post-processing/#21-pressure-coefficient)**  
+ **[2.2 Stanton number](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-monitoring-post-processing/#22-stanton-number)**  
+ **[2.3 Skin-friction coefficient](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-monitoring-post-processing/#23-skin-friction-coefficient)**  
+ **[2.4 _y+_](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-monitoring-post-processing/#24-y)**  
+ **[2.5 ParaView](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-monitoring-post-processing/#25-paraview)**  
