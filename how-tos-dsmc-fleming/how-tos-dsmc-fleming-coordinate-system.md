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
  
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-coordinate-system/" style="background-color:#FFCCCC"><b>E. COORDINATE SYSTEM</b></a>
  
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
  document.getElementById('mySidenav').scrollTop = "650";
}

function closeNav() {
  document.getElementById("mySidenav").style.width = "0px";
}

function reopenNav() {
  document.getElementById("mySidenav").style.width = "225px";
  document.getElementById("mySidenav").style.transition = "0.5s";
  document.getElementById('mySidenav').scrollTop = "650";
}

openNav()
</script>

&nbsp; 

# Coordinate system

The default coordinate system is _Cartesian_. For axisymmetric simulations, the <dictkey>coordinateSystem</dictkey> entry can be set in the <dirname>constant/</dirname><dict>dsmcProperties</dict> dictionary as follows

```c++
// General Properties
// ~~~~~~~~~~~~~~~~~~

coordinateSystem   dsmcAxisymmetric;

axisymmetricProperties
{
    maxRadialWeightingFactor    1000;
}
```

Cell-based radial weighting factors (RWFs) are employed and the maximum RWF obtained for $$r = r_{max}$$ can be set with <subdict>axisymmetricProperties</subdict>/<dictkey>maxRadialWeightingFactor</dictkey>.

Should the revolution axis not be aligned with the $$x$$-axis and the polar axis not be aligned with the $$y$$-axis, two additional entries can be set in <subdict>axisymmetricProperties</subdict> to accommodate this

```c++
axisymmetricProperties
{
    revolutionAxis  "x";
    polarAxis       "y";
}
```
