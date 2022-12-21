---
layout: page
title: How-tos
subtitle: Hybrid Modules - Fleming release
nav-short: true
---

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()"><i class='fa fa-times'></i></a>
  <header>HOW-TOS — HYBD</header>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-thermophysical/"><b>A. THERMOPHYSICAL</b></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-thermophysical/#1-species-thermophysical-properties" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Species properties</span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-thermophysical/#2-addingremoving-energy-modes"  style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) +/- energy modes</span></a>

  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-collision-dynamics" style="background-color:#FFCCCC"><b>B. COLLISION DYNAMICS</b></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-collision-dynamics/#1-collision-partner-selection"  style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Collision partner selection</span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-collision-dynamics/#2-binary-collision"  style="background-color:#FFE6E6; padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Binary collision</span></a>

  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-chemistry/"><b>C. CHEMISTRY</b></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-chemistry/#1-chemical-reaction-models"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Chemical reaction models</span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-chemistry/#2-dissociation-reaction"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Dissociation reaction</span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-chemistry/#3-exchange-reaction"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Exchange reaction</span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-chemistry/#4-combined-reactions"  style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) Combined reactions</span></a>

  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-boundary-conditions"><b>D. BOUNDARY CONDITIONS</b></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-boundary-conditions/#1-generalities"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Generalities</span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-boundary-conditions/#2-inflow--outflow-boundary-conditions"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Inflow & Outflow</span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-boundary-conditions/#3-wall-boundary-conditions"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Wall</span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-boundary-conditions/#4-cyclic-boundary-conditions"  style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) Cyclic</span></a>
  
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-coordinate-system/"><b>E. COORDINATE SYSTEM</b></a>
  
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-initialisation/"><b>F. INITIALISATION</b></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-initialisation/#1-the-dsmcinitialisedict-dictionary"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) <i>dsmcInitialiseDict</i></span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-initialisation/#2-dsmc-parcel-vs-real-particles"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Parcel vs. particles</span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-initialisation/#3-creating-the-0-folder"  style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Creating the <i>0/</i> folder</span></a>
  
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-sampling/"><b>G. SAMPLING</b></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-sampling/#1-the-fieldpropertiesdict-dictionary"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) <i>fieldPropertiesDict</i></span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-sampling/#2-steady-state-simulations"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Steady-state simulations</span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-sampling/#3-transient-simulations" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Transient simulations</span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-sampling/#4-mean-free-path-computation"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) MFP computation</span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-sampling/#5-resume-sampling" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 5) Resume sampling</span></a>
  
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-load-balancing/"><b>H. LOAD BALANCING</b></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming/#i-adaptive-mesh-refinement"><b>I. ADAPTIVE MESH REFINEMENT</b></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming/#j-monitoring--post-processing"><b>J. MONITORING & POST-PROCESSING</b></a>
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
<!--## 1) Collision partner selection-->

<!--The No-Time-Counter of Bird is the only recommended collision partner selection model (others haven't been throughly tested). It is implemented as follows in <dirname>constant/</dirname><dict>dsmcProperties</dict>-->
<!--    -->
<!--```c++-->
<!--// Collision Partner Selection Model-->
<!--// ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->

<!--collisionPartnerSelectionModel        noTimeCounter;-->
<!--```-->

<!--In this model, each cell have 8 subcells (2 in each direction) to reduce the mean collision separation.-->

<!--<br>-->

<!-----  -->
<!--## 2) Binary collision-->

<!--The available binary collision models are:  -->
<!--  - <dictval>VariableHardSphere</dictval>  -->
<!--  - <dictval>VariableSoftSphere</dictval>  -->
<!--  - <dictval>LarsenBorgnakkeVariableHardSphere</dictval>   -->
<!--  - <dictval>LarsenBorgnakkeVariableSoftSphere</dictval>   -->

<!--The selected model is defined for the entry <dictkey>BinaryCollisionModel</dictkey> and its parameters are given in the subsequent <subdict>#modelCoeffs</subdict> subdictionary. Here is an example for the <dictval>LarsenBorgnakkeVariableHardSphere</dictval> model, using constant collision numbers-->

<!--```c++-->
<!--// Binary Collision Model-->
<!--// ~~~~~~~~~~~~~~~~~~~~~~-->

<!--BinaryCollisionModel        LarsenBorgnakkeVariableHardSphere;-->

<!--LarsenBorgnakkeVariableHardSphereCoeffs-->
<!--{-->
<!--    rotationalRelaxationCollisionNumber   5.0;-->
<!--    vibrationalRelaxationCollisionNumber  50.0;-->
<!--    electronicRelaxationCollisionNumber   500.0;-->
<!--}-->
<!--```-->

<!--<b>NB</b>: the reference temperature $$T_{ref}$$ is set to 273 K by default.-->

<!--The vibrational collision number can be set to be a function of temperature, in which case the line -->

<!--```c++-->
<!--    vibrationalRelaxationCollisionNumber  50.0;-->
<!--```-->

<!--should be deleted and replaced by another entry. The available options for a variable vibrational collision number are as follows: -->

<!--```c++-->
<!--    inverseZvFormulation           "pre-2008"; // (uses the collision temperature)-->
<!--    inverseZvFormulation               "2008"; // (uses the overall temperature)-->
<!--```-->

<!--and if the entry <dictkey>inverseZvFormulation</dictkey> is not specified, then $$Z_{vib}$$ will be defined as in Bird's 2013 book.  The `"pre-2008"` and `2013` models differ by a coefficient 1/5 and are both using the collision temperature. This is the recommended option and it is shown below-->

<!--```c++-->
<!--// Binary Collision Model-->
<!--// ~~~~~~~~~~~~~~~~~~~~~~-->

<!--BinaryCollisionModel        LarsenBorgnakkeVariableHardSphere;-->

<!--LarsenBorgnakkeVariableHardSphereCoeffs-->
<!--{-->
<!--    rotationalRelaxationCollisionNumber   5.0;-->
<!--    electronicRelaxationCollisionNumber   500.0;-->
<!--}-->
<!--```-->

<!--Please also refer to [A.1 Species thermophysical properties](https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-thermophysical/#1-species-thermophysical-properties) for the definitions of $$Z_{ref}$$ and $$T_{ref, Z_{ref}}$$. -->
