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
  
  <a href="https://hystrath.github.io/guides/fleming/picdsmc/initialisation/" style="background-color:#FFCCCC"><b>D. INITIALISATION</b></a>
  <a href="https://hystrath.github.io/guides/fleming/picdsmc/initialisation/#1-the-pdinitialisedict-dictionary"  style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) <i>pdInitialiseDict</i></span></a>
  <a href="https://hystrath.github.io/guides/fleming/picdsmc/initialisation/#2-parcel-vs-real-particles"  style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Parcel vs. particles</span></a>
  <a href="https://hystrath.github.io/guides/fleming/picdsmc/initialisation/#3-creating-the-0-folder"  style="background-color:#FFE6E6; padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Creating the <i>0/</i> folder</span></a>
  
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
  document.getElementById('mySidenav').scrollTop = "480";
}

function closeNav() {
  document.getElementById("mySidenav").style.width = "0px";
}

function reopenNav() {
  document.getElementById("mySidenav").style.width = "225px";
  document.getElementById("mySidenav").style.transition = "0.5s";
  document.getElementById('mySidenav').scrollTop = "480";
}

openNav()
</script>

&nbsp;   

# Initialisation

---
## 1) The _pdInitialiseDict_ dictionary

The <dict>pdInitialiseDict</dict> dictionary is located in the <dirname>system/</dirname> folder. The initial number density of all species present in the gas mixture (see [A.1 Species thermophysical properties](https://hystrath.github.io/guides/fleming/picdsmc/thermophysical/#1-species-thermophysical-properties)), modal temperatures and velocity are given in the following subdictionary

```c++
configurations
(
    configuration
    {
        type    pdMeshFill;

        numberDensities
        {
             Ar            1.4e20;
        };

        translationalTemperature     273.0;
        rotationalTemperature        0.0; 
        vibrationalTemperature       0.0;

        velocity        (100 0 0);
    }
);
```

where the <dictkey>type</dictkey> <dictval>pdMeshFill</dictval> indicates that the entire grid is going to be populated with particles. To start with a grid free of parcels, leave the `configurations()` list empty.

<br>

---
## 2) Parcel vs. real particles
 
The number of real particles represented by a single parcel is set in the <dirname>constant/</dirname><dict>pdProperties</dict> dictionary

```c++
nEquivalentParticles            2e7;
```

There should be a minimum of 20 parcels per cell whenever possible and <dictkey>nEquivalentParticles</dictkey> should be set accordingly.


<br>

---
## 3) Creating the _0/_ folder
 
In the working directory, type in:  
```sh
pdInitialise
```
This command line will create the <dirname>0/</dirname> folder. Simulators data is stored into the <dirname>0/lagrangian/pd/</dirname> subfolder and a volume field, _pdSigmaTcRMax_, is printed. The main executable will always look for these information in the time folder corresponding to the starting time. 

&nbsp;

### 3.1 Simulators data 

In the <dirname>0/lagrangian/pd/</dirname> folder, the files listed in the Table below are created. Each of them contains a dataset of size _number of parcels_.    

| File    | Meaning          |
|:-------------:|-------------|
| _positions_      | positions in Cartesian space |
| _U_      | velocity vector |
| _A_      | acceleration vector |
| _typeId_ | species index, cf. species list given in the _pdProperties_ dictionary |
| _newParcel_      | -1 if seeded at t = 0 or index of the patch the simulator entered the domain |
| _origProcId_ | index of the processor dealing with the simulator |
| _origId_ | local particle index in processor _origProcId_ |
| _classification_      | not used, to be revised |
|   |  |
| _ERot_      | rotational energy |
| _EVib_      | vibrational energy |
| _EPot_      | potential energy |

&nbsp;

### 3.2 Initial volume fields 
 
+ _pdSigmaTcRMax_ is a first estimate of the maximum value taken by the product of the collision cross-section by the relative speed. For a gas mixture, it is usually obtained by considering the properties (diameter, omega, alpha) of the most abundant species. As the simulation proceeds, this field is updated as soon as a new local maximum is found. It requires no user intervention.