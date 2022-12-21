---
layout: page
title: How-tos
subtitle: Hybrid Modules - Fleming release
nav-short: true
---

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()"><i class='fa fa-times'></i></a>
  <header>HOW-TOS — HYBD</header>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-thermophysical/" style="background-color:#FFCCCC"><b>A. THERMOPHYSICAL</b></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-thermophysical/#1-species-thermophysical-properties" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Species properties</span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-thermophysical/#2-addingremoving-energy-modes"  style="background-color:#FFE6E6; padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) +/- energy modes</span></a>

  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-collision-dynamics"><b>B. COLLISION DYNAMICS</b></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-collision-dynamics/#1-binary-collision-model"  style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Binary collision model</span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-collision-dynamics/#2-collision-partner-selection"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Collision partner selection</span></a>

  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-boundary-conditions"><b>C. BOUNDARY CONDITIONS</b></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-boundary-conditions/#1-generalities"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Generalities</span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-boundary-conditions/#2-inflow--outflow-boundary-conditions"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Inflow & Outflow</span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-boundary-conditions/#3-wall-boundary-conditions"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Wall</span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-boundary-conditions/#4-cyclic-boundary-conditions"  style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) Cyclic</span></a>
  
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-initialisation/"><b>D. INITIALISATION</b></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-initialisation/#1-the-pdinitialisedict-dictionary"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) <i>pdInitialiseDict</i></span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-initialisation/#2-parcel-vs-real-particles"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Parcel vs. particles</span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-initialisation/#3-creating-the-0-folder"  style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Creating the <i>0/</i> folder</span></a>
  
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-sampling/"><b>E. SAMPLING</b></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-sampling/#1-the-fieldpropertiesdict-dictionary"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) <i>fieldPropertiesDict</i></span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-sampling/#2-steady-state-simulations"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Steady-state simulations</span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-sampling/#3-transient-simulations" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Transient simulations</span></a>
  
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming/#f-monitoring--post-processing"><b>F. MONITORING & POST-PROCESSING</b></a>
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

---  
## 1) Species thermophysical properties

The gas composition is given in the <dirname>constant/</dirname><dict>pdProperties</dict> dictionary in the form of a list.

```c++
// Molecular species
// ~~~~~~~~~~~~~~~~~

typeIdList           (N2 O2);
```

The species thermophysical properties are given in the <dict>pdProperties</dict>/<subdict>moleculesProperties</subdict> dictionary. For the nitrogen molecule, it is defined as follows
    
```c++
N2
{
    mass                                  46.5e-27;
    diameter                              4.17e-10;
    omega                                     0.74;
    alpha                                     1.36;
    rotationalDegreesOfFreedom                   2;
    vibrationalModes                             1;
    characteristicVibrationalTemperature      3371;
    dissociationTemperature                 113500;
    Zref                                     52560;
    referenceTempForZref                      3371;
    Ze                                           0;
}
```

The Table below lists the meaning of the different keys present in the <subdict>#speciesName</subdict> subdictionary. 
If a <dictkey>key</dictkey> is omitted, then a <dictval>default value</dictval> is used whenever possible.

<table>
  <tr>
    <td align="center" colspan="3"><b><subdict>#speciesName</subdict> subdictionary</b></td>
  </tr>
  <tr>
    <td align="center"><b>Key</b></td>
    <td align="center"><b>Units</b></td>
    <td align="center"><b>Meaning</b></td>
  </tr>
  <tr>
    <td align="center"><dictkey>mass</dictkey></td>
    <td align="center"> kg </td>
    <td align="center">mass of a single particle</td>
  </tr>
  <tr>
    <td align="center"><dictkey>diameter</dictkey></td>
    <td align="center"> m </td>  
    <td align="center">particle diameter </td>
  </tr>
  <tr>
    <td align="center"><dictkey>omega</dictkey></td>
    <td align="center"> - </td>  
    <td align="center">temperature exponent of viscosity</td>
  </tr>
  <tr>
    <td align="center"><dictkey>alpha</dictkey></td>
    <td align="center"> - </td>  
    <td align="center">soft-sphere scattering parameter (default is <dictval>1.0</dictval>, <i>i.e.</i>, hard-sphere gas)</td>
  </tr>
  <tr>
    <td align="center"><dictkey>rotationalDegreesOfFreedom</dictkey></td>
    <td align="center"> - </td>  
    <td align="center">number of rotational degrees of freedom (default is <dictval>0</dictval>)</td>
  </tr>
  <tr>
    <td align="center"><dictkey>vibrationalModes</dictkey></td>
    <td align="center"> - </td>  
    <td align="center">number of vibrational energy modes (default is <dictval>0</dictval>)</td>
  </tr>
  <tr>
    <td align="center"><dictkey>characteristicVibrationalTemperature</dictkey></td>
    <td align="center"> K </td>  
    <td align="center">characteristic vibrational temperature (default is <dictval>0</dictval>)</td>
  </tr>
  <tr>
    <td align="center"><dictkey>dissociationTemperature</dictkey></td>
    <td align="center"> K </td>  
    <td align="center">dissociation temperature (default is <dictval>0.0</dictval>)</td>
  </tr>
  <tr>
    <td align="center"><dictkey>Zref</dictkey></td>
    <td align="center"> - </td>  
    <td align="center"> reference vibrational collision number (default is <dictval>0.0</dictval>)</td>
  </tr>
  <tr>
    <td align="center"><dictkey>referenceTempForZref</dictkey></td>
    <td align="center"> K </td>  
    <td align="center"> reference temperature in the vibrational collision number calculation (default is <dictval>0.0</dictval>)</td>
  </tr>
  <tr>
    <td align="center"><dictkey>Ze</dictkey></td>
    <td align="center"> - </td>  
    <td align="center">charge of the particle (<dictval>-1</dictval>: electron, <dictval>0</dictval>: neutral atom and molecule, <dictval>+1</dictval>: charged atom and molecule, default is <dictval>0</dictval>) </td>
  </tr>
</table>

&nbsp;

---  
## 2) Adding/removing energy modes

### 2.1 Disabling/enabling the rotational mode of a molecule 

In the <dict>pdProperties</dict>/<subdict>moleculesProperties/#speciesName</subdict> dictionary, either edit  <dictkey>rotationalDegreesOfFreedom</dictkey> to be <dictval>0</dictval> or remove this key from the dictionary.  

In the following example, the rotational energy mode of the N2 molecule is enabled  

```c++
    rotationalDegreesOfFreedom                   2;
```

&nbsp;

### 2.2 Disabling/enabling the vibrational mode of a molecule 

In the <dict>pdProperties</dict>/<subdict>moleculesProperties/#speciesName</subdict> dictionary, remove the <dictkey>vibrationalModes</dictkey>, <dictkey>characteristicVibrationalTemperature</dictkey>, <dictkey>Zref</dictkey> and <dictkey>referenceTempForZref</dictkey> keys.  

In the following example, the vibrational energy mode of the N2 molecule is enabled  

```c++
    vibrationalModes                             1;
    characteristicVibrationalTemperature      3371;
    Zref                                     52560;
    referenceTempForZref                      3371;
```
