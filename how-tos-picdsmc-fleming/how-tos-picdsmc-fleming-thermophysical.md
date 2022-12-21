---
layout: page
title: How-tos
subtitle: Hybrid Modules - Fleming release
nav-short: true
---

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()"><i class='fa fa-times'></i></a>
  <header>HOW-TOS — DSMC</header>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-thermophysical/" style="background-color:#FFCCCC"><b>A. THERMOPHYSICAL</b></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-thermophysical/#1-species-thermophysical-properties" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Species properties</span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-thermophysical/#2-addingremoving-energy-modes"  style="background-color:#FFE6E6; padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) +/- energy modes</span></a>

  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-collision-dynamics"><b>B. COLLISION DYNAMICS</b></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-collision-dynamics/#1-collision-partner-selection"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Collision partner selection</span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-collision-dynamics/#2-binary-collision"  style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Binary collision</span></a>

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

# Thermophysical modelling

<!-----  -->
<!--## 1) Species thermophysical properties-->

<!--The gas composition is given in the <dirname>constant/</dirname><dict>dsmcProperties</dict> dictionary in the form of a list.-->

<!--```c++-->
<!--// Molecular species-->
<!--// ~~~~~~~~~~~~~~~~~-->

<!--typeIdList           (N2 O2 NO N O);-->
<!--```-->

<!--The species thermophysical properties are given in the <dict>dsmcProperties</dict>/<subdict>moleculesProperties</subdict> dictionary. For the nitrogen molecule, it is defined as follows-->
<!--    -->
<!--```c++-->
<!--N2-->
<!--{-->
<!--    mass                                  46.5e-27;-->
<!--    diameter                              4.17e-10;-->
<!--    omega                                     0.74;-->
<!--    alpha                                     1.36;-->
<!--    rotationalDegreesOfFreedom                   2;-->
<!--    nVibrationalModes                            1;-->
<!--    vibrationalDegeneracyList                  (1);-->
<!--    characteristicVibrationalTemperature    (3371);-->
<!--    dissociationTemperature                 113500;-->
<!--    Zref                                   (52560);-->
<!--    referenceTempForZref                    (3371);-->
<!--    ionisationTemperature                 180798.3;-->
<!--    charge                                       0;-->
<!--    nElectronicLevels                           15;-->
<!--    electronicDegeneracyList-->
<!--    (-->
<!--        1 3 6 6 3 1 2 2 5 1 6 6 10 6 6-->
<!--    );-->
<!--    electronicEnergyList-->
<!--    (-->
<!--        0  9.972e-19 1.1843e-18 1.1881e-18 1.3165e-18 1.3538e-18-->
<!--          1.3763e-18 1.4483e-18 1.5415e-18 1.6925e-18 1.7242e-18-->
<!--          1.7707e-18 1.8474e-18 1.9388e-18 2.0778e-18-->
<!--    );-->
<!--}-->
<!--```-->

<!--The Table below lists the meaning of the different keys present in the <subdict>#speciesName</subdict> subdictionary. -->
<!--If a <dictkey>key</dictkey> is omitted, then a <dictval>default value</dictval> is used whenever possible.-->

<!--<table>-->
<!--  <tr>-->
<!--    <td align="center" colspan="3"><b><subdict>#speciesName</subdict> subdictionary</b></td>-->
<!--  </tr>-->
<!--  <tr>-->
<!--    <td align="center"><b>Key</b></td>-->
<!--    <td align="center"><b>Units</b></td>-->
<!--    <td align="center"><b>Meaning</b></td>-->
<!--  </tr>-->
<!--  <tr>-->
<!--    <td align="center"><dictkey>mass</dictkey></td>-->
<!--    <td align="center"> kg </td>-->
<!--    <td align="center">mass of a single particle</td>-->
<!--  </tr>-->
<!--  <tr>-->
<!--    <td align="center"><dictkey>diameter</dictkey></td>-->
<!--    <td align="center"> m </td>  -->
<!--    <td align="center">particle diameter </td>-->
<!--  </tr>-->
<!--  <tr>-->
<!--    <td align="center"><dictkey>omega</dictkey></td>-->
<!--    <td align="center"> - </td>  -->
<!--    <td align="center">temperature exponent of viscosity</td>-->
<!--  </tr>-->
<!--  <tr>-->
<!--    <td align="center"><dictkey>alpha</dictkey></td>-->
<!--    <td align="center"> - </td>  -->
<!--    <td align="center">soft-sphere scattering parameter (default is <dictval>1.0</dictval>, <i>i.e.</i>, hard-sphere gas)</td>-->
<!--  </tr>-->
<!--  <tr>-->
<!--    <td align="center"><dictkey>rotationalDegreesOfFreedom</dictkey></td>-->
<!--    <td align="center"> - </td>  -->
<!--    <td align="center">number of rotational degrees of freedom (default is <dictval>0</dictval>)</td>-->
<!--  </tr>-->
<!--  <tr>-->
<!--    <td align="center"><dictkey>nVibrationalModes</dictkey></td>-->
<!--    <td align="center"> - </td>  -->
<!--    <td align="center">number of vibrational energy modes (default is <dictval>0</dictval>)</td>-->
<!--  </tr>-->
<!--  <tr>-->
<!--    <td align="center"><dictkey>vibrationalDegeneracyList</dictkey></td>-->
<!--    <td align="center"> - </td>  -->
<!--    <td align="center">degeneracy of each vibrational energy mode (default is <dictval>1</dictval>, list of size <dictkey>nVibrationalModes</dictkey>)</td>-->
<!--  </tr>-->
<!--  <tr>-->
<!--    <td align="center"><dictkey>characteristicVibrationalTemperature</dictkey></td>-->
<!--    <td align="center"> K </td>  -->
<!--    <td align="center">characteristic vibrational temperature (list of size <dictkey>nVibrationalModes</dictkey>)</td>-->
<!--  </tr>-->
<!--  <tr>-->
<!--    <td align="center"><dictkey>dissociationTemperature</dictkey></td>-->
<!--    <td align="center"> K </td>  -->
<!--    <td align="center">dissociation temperature (default is <dictval>0.0</dictval>)</td>-->
<!--  </tr>-->
<!--  <tr>-->
<!--    <td align="center"><dictkey>Zref</dictkey></td>-->
<!--    <td align="center"> - </td>  -->
<!--    <td align="center"> reference vibrational collision number (list of size <dictkey>nVibrationalModes</dictkey>)</td>-->
<!--  </tr>-->
<!--  <tr>-->
<!--    <td align="center"><dictkey>referenceTempForZref</dictkey></td>-->
<!--    <td align="center"> K </td>  -->
<!--    <td align="center"> reference temperature in the vibrational collision number calculation (list of size <dictkey>nVibrationalModes</dictkey>)</td>-->
<!--  </tr>-->
<!--  <tr>-->
<!--    <td align="center"><dictkey>ionisationTemperature</dictkey></td>-->
<!--    <td align="center"> K </td>  -->
<!--    <td align="center">ionisation temperature (default is <dictval>1.0e10</dictval>)</td>-->
<!--  </tr>-->
<!--  <tr>-->
<!--    <td align="center"><dictkey>charge</dictkey></td>-->
<!--    <td align="center"> - </td>  -->
<!--    <td align="center">charge of the particle (<dictval>-1</dictval>: electron, <dictval>0</dictval>: neutral atom and molecule, <dictval>+1</dictval>: charged atom and molecule, default is <dictval>0</dictval>) </td>-->
<!--  </tr>-->
<!--  <tr>  -->
<!--    <td align="center"><dictkey>nElectronicLevels</dictkey></td>-->
<!--    <td align="center"> - </td>  -->
<!--    <td align="center"> number of electronic energy levels (default is <dictval>0</dictval>)</td>-->
<!--  </tr>-->
<!--  <tr>-->
<!--    <td align="center"><dictkey>electronicDegeneracyList</dictkey></td>-->
<!--    <td align="center"> - </td>  -->
<!--    <td align="center"> degeneracy of each electronic energy level (default is <dictval>1</dictval>, list of size <dictkey>nElectronicLevels</dictkey>)</td>-->
<!--  </tr>-->
<!--  <tr>-->
<!--    <td align="center"><dictkey>electronicEnergyList</dictkey></td>-->
<!--    <td align="center"> J </td>  -->
<!--    <td align="center"> electronic energy of each electronic energy level (list of size <dictkey>nElectronicLevels</dictkey>)</td>-->
<!--  </tr>-->
<!--</table>-->


<!--<b>NB</b>: An example for 5-species air is given in the [chemically-reacting heat bath tutorial](https://hystrath.github.io/tutos-dsmcfoam/#6-chemically-reacting-heat-bath), [on this page](https://github.com/hystrath/hyStrath/tree/master/run/hyStrath/dsmcFoam%2B/heatBath-5species/constant/dsmcProperties).-->

<!--&nbsp;-->

<!--<p style="text-align:center; color:Tomato"><strong> >> Electronic energy unavailable until further notice << </strong></p>-->

<!--&nbsp;-->

<!-----  -->
<!--## 2) Adding/removing energy modes-->

<!--### 2.1 Disabling/enabling the rotational mode of a molecule -->

<!--In the <dict>dsmcProperties</dict>/<subdict>moleculesProperties/#speciesName</subdict> dictionary, either edit  <dictkey>rotationalDegreesOfFreedom</dictkey> to be <dictval>0</dictval> or remove this key from the dictionary.  -->

<!--In the following example, the rotational energy mode of the N2 molecule is enabled  -->

<!--```c++-->
<!--    rotationalDegreesOfFreedom                   2;-->
<!--```-->

<!--&nbsp;-->

<!--### 2.2 Disabling/enabling the vibrational mode of a molecule -->

<!--In the <dict>dsmcProperties</dict>/<subdict>moleculesProperties/#speciesName</subdict> dictionary, remove the <dictkey>nVibrationalModes</dictkey>, <dictkey>vibrationalDegeneracyList</dictkey> and <dictkey>characteristicVibrationalTemperature</dictkey> keys.  -->

<!--In the following example, the vibrational energy mode of the N2 molecule is enabled  -->

<!--```c++-->
<!--    nVibrationalModes                            1;-->
<!--    vibrationalDegeneracyList                  (1);-->
<!--    characteristicVibrationalTemperature    (3371);-->
<!--```-->

<!--&nbsp;-->

<!--### 2.3 Disabling/enabling the electronic mode of a particle  -->

<!--In the <dict>dsmcProperties</dict>/<subdict>moleculesProperties/#speciesName</subdict> dictionary, remove the <dictkey>nElectronicLevels</dictkey>, <dictkey>electronicDegeneracyList</dictkey> and <dictkey>electronicEnergyList</dictkey> keys.  -->

<!--In the following example, the electronic energy mode of the N2 molecule is enabled  -->

<!--```c++-->
<!--    nElectronicLevels                           15;-->
<!--    electronicDegeneracyList-->
<!--    (-->
<!--        1 3 6 6 3 1 2 2 5 1 6 6 10 6 6-->
<!--    );-->
<!--    electronicEnergyList-->
<!--    (-->
<!--        0  9.972e-19 1.1843e-18 1.1881e-18 1.3165e-18 1.3538e-18-->
<!--          1.3763e-18 1.4483e-18 1.5415e-18 1.6925e-18 1.7242e-18-->
<!--          1.7707e-18 1.8474e-18 1.9388e-18 2.0778e-18-->
<!--    );-->
<!--```-->
