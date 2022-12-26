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

  <a href="https://hystrath.github.io/guides/fleming/picdsmc/collision-dynamics" style="background-color:#FFCCCC"><b>B. COLLISION DYNAMICS</b></a>
  <a href="https://hystrath.github.io/guides/fleming/picdsmc/collision-dynamics/#1-binary-collision-model"  style="background-color:#FFE6E6; padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Binary collision model</span></a>
  <a href="https://hystrath.github.io/guides/fleming/picdsmc/collision-dynamics/#2-collision-partner-selection"  style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Collision partner selection</span></a>

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

# Collision dynamics

---  
## 1) Binary collision model

The available binary collision models are:  
  - <dictval>NoBinaryCollision</dictval>  
  - <dictval>VariableHardSphere</dictval>  
  - <dictval>VariableSoftSphere</dictval>  

The selected model is defined for the entry <dictkey>BinaryCollisionModel</dictkey>. Here is an example for the <dictval>VariableHardSphere</dictval> model where the reference temperature $$T_{ref}$$ is set to 273 K by default

```c++
// Binary Collision Model
// ~~~~~~~~~~~~~~~~~~~~~~

BinaryCollisionModel        VariableHardSphere;
```

<br>

--- 
## 2) Collision partner selection

The No-Time-Counter of Bird is the only recommended collision partner selection model (others haven't been throughly tested). It is implemented as follows in <dirname>constant/</dirname><dict>pdProperties</dict>
    
```c++
// Collision Partner Selection Model
// ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

collisionPartnerSelectionModel        noTimeCounter;
```

In this model, each cell have 8 subcells (2 in each direction) to reduce the mean collision separation. 
