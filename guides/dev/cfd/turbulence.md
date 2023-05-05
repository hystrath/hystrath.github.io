---
layout: page
title: Guides
subtitle: CFD Module - Dev release
nav-short: true
---

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()"><i class='fa fa-times'></i></a>
  <header>GUIDE — CFD</header>
  <a href="https://hystrath.github.io/guides/dev/cfd/thermophysical/"><b>A. THERMOPHYSICAL</b></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/thermophysical/#1-species-thermophysical-properties" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Species thermo props</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/thermophysical/#2-addingremoving-energy-modes" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) +/- energy modes</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/thermophysical/#3-choosing-a-thermodem-dictionary" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) <i>thermoDEM</i> dictionary</span></a>

  <a href="https://hystrath.github.io/guides/dev/cfd/transport/"><b>B. TRANSPORT</b></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/transport/#1-species-shear-viscosity-and-thermal-conductivity" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Species transport props</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/transport/#2-mixing-rules" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Mixing rules</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/transport/#3-mass-diffusion" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Mass diffusion</span></a>

  <a href="https://hystrath.github.io/guides/dev/cfd/chemistry/"><b>C. CHEMISTRY</b></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/chemistry/#1-multi-species-flow" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Multi-species flow</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/chemistry/#2-non-reacting-flow" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Non-reacting flow</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/chemistry/#3-chemically-reacting-flow" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Chemically-reacting flow</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/chemistry/#4-to-go-further-chemistry-vibration-coupling" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) To go further</span></a>
  
  <a href="https://hystrath.github.io/guides/dev/cfd/nonequilibrium/"><b>D. NONEQUILIBRIUM</b></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/nonequilibrium/#1-thermal-equilibrium" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Thermal equilibrium</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/nonequilibrium/#2-thermal-non-equilibrium" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Thermal non-equilibrium</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/nonequilibrium/#3-mean-free-path-and-breakdown-parameter" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) MFP & Breakdown</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/nonequilibrium/#4-chemistry-vibration-coupling" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) Chem.-vib. coupling</span></a>
  
  <a href="https://hystrath.github.io/guides/dev/cfd/turbulence/" style="background-color:#FFCCCC"><b>E. TURBULENCE</b></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/turbulence/#1-laminar-flow-simulation" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Laminar</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/turbulence/#2-turbulent-flow-simulation" style="background-color:#FFE6E6; padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Turbulent</span></a>
  
  <a href="https://hystrath.github.io/guides/dev/cfd/mhd/"><b>F. MHD</b></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/mhd/#1-enablingdisabling-mhd" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Enabling/disabling MHD</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/mhd/#2-mhd-models" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) MHD models</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/mhd/#3-electrical-conductivity-models" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Electrical conductivity</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/mhd/#4-hall-parameter" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) Hall parameter</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/mhd/#5-creation-of-an-initial-magnetic-field-and-electric-potential" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 5) Initial <i>B</i> & electric pot.</span></a>


  <a href="https://hystrath.github.io/guides/dev/cfd/initial-conditions/"><b>G. INITIAL CONDITIONS</b></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/initial-conditions/#1-the-include-sub-folder" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) The <i>include/</i> sub-folder</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/initial-conditions/#2-species-mass-or-molar-fractions" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Mass or molar fractions</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/initial-conditions/#3-temperature-fields" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Temperature fields</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/initial-conditions/#4-velocity-field" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) Velocity field</span></a>
  
  <a href="https://hystrath.github.io/guides/dev/cfd/numerics/"><b>H. NUMERICS</b></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/numerics/#1-time-schemes" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Time schemes</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/numerics/#2-flux-schemes" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Flux schemes</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/numerics/#3-other-schemes" style="padding-top:4px;"><span style="font-size:13px">&nbsp;&nbsp; 3) Other schemes</span></a>
  
  <a href="https://hystrath.github.io/guides/dev/cfd/advanced/"><b>I. ADVANCED</b></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/advanced/#1-on-the-fly-dictionary-editing" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) On-the-fly editing</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/advanced/#2-bounding-the-temperature-field" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Bounding the temperature</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/advanced/#3-adaptive-mesh-refinement" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Adaptive mesh refinement</span></a>
  
  <a href="https://hystrath.github.io/guides/dev/cfd/monitoring-post-processing"><b>J. MONITORING & POST-PROCESSING</b></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/monitoring-post-processing/#1-monitoring" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Monitoring</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/monitoring-post-processing/#2-post-processing" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Post-processing</span></a>
</div>

<span style="position: fixed;font-size:30px;cursor:pointer; margin:0px; top:60px;left:30px;" onclick="reopenNav()">&#9776;</span>

<script>
function openNav() {
  document.getElementById("mySidenav").style.width = "225px";
  document.getElementById("mySidenav").style.transition = "0s";
  document.getElementById('mySidenav').scrollTop = "720";
}

function closeNav() {
  document.getElementById("mySidenav").style.width = "0px";
}

function reopenNav() {
  document.getElementById("mySidenav").style.width = "225px";
  document.getElementById("mySidenav").style.transition = "0.5s";
  document.getElementById('mySidenav').scrollTop = "720";
}

openNav()
</script>

These guidelines are based on the working folder located [here](https://github.com/hystrath/hyStrath/tree/OF-v2112/run/hyStrath/hy2Foam/genericCase).  

# Turbulence modelling

---
## 1) Laminar flow simulation 
  
In the <dict>turbulenceProperties</dict> dictionary, edit the <dictkey>simulationType</dictkey> entry to <dictval>laminar</dictval>.

<br>

---
## 2) Turbulent flow simulation

In the <dict>turbulenceProperties</dict> dictionary, edit the <dictkey>simulationType</dictkey> entry to <dictval>RAS</dictval>.  
Then, in the <subdict>RAS</subdict> sub-dictionary, edit the <dictkey>RASModel</dictkey> to the desired turbulence model and the <dictkey>turbulence</dictkey> switch to <dictval>on</dictval>. Depending on which model is chosen, some fields may have to be added to the <dirname>0/</dirname> directory. Please refer to the official OpenFOAM tutorials for further information.
