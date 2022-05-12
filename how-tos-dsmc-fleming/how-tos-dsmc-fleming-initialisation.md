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
  
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-initialisation/" style="background-color:#FFCCCC"><b>F. INITIALISATION</b></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-initialisation/#1-the-dsmcinitialisedict-dictionary"  style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) <i>dsmcInitialiseDict</i></span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-initialisation/#2-dsmc-parcel-vs-real-particles"  style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Parcel vs. particles</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-initialisation/#3-creating-the-0-folder"  style="background-color:#FFE6E6; padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Creating the <i>0/</i> folder</span></a>
  
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

# Initialisation

---
## 1) The _dsmcInitialiseDict_ dictionary

The <dict>dsmcInitialiseDict</dict> dictionary is located in the <dirname>system/</dirname> folder. The initial number density of all species present in the gas mixture (see [A.1 Species thermophysical properties](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-thermophysical/#1-species-thermophysical-properties)), modal temperatures and velocity are given in the following subdictionary

```c++
configurations
(
    configuration
    {
        type    dsmcMeshFill;

        numberDensities
        {
             Ar            1.4e20;
        };

        translationalTemperature     273.0;
        rotationalTemperature        0.0; 
        vibrationalTemperature       0.0;
        electronicTemperature        0.0;

        velocity        (100 0 0);
    }
);
```

where the <dictkey>type</dictkey> <dictval>dsmcMeshFill</dictval> indicates that the entire grid is going to be populated with particles. To start with a grid free of DSMC parcels, leave the `configurations()` list empty.

<br>

---
## 2) DSMC parcel vs. real particles
 
The number of real particles represented by a single DSMC parcel is set in the <dirname>constant/</dirname><dict>dsmcProperties</dict> dictionary

```c++
nEquivalentParticles            2e7;
```

There should be a minimum of 20 DSMC parcels per cell whenever possible and <dictkey>nEquivalentParticles</dictkey> should be set accordingly.


<br>

---
## 3) Creating the _0/_ folder
 
In the working directory, type in:  
```sh
dsmcInitialise+
```
This command line will create the <dirname>0/</dirname> folder. Simulators data is stored into the <dirname>0/lagrangian/dsmc/</dirname> subfolder and two volume fields, _cellLevel_ and _dsmcSigmaTcRMax_, are printed. The main DSMC executable will always look for these information in the time folder corresponding to the starting time. 

&nbsp;

### 3.1 Simulators data 

In the <dirname>0/lagrangian/dsmc/</dirname> folder, the files listed in the Table below are created. Each of them contains a dataset of size _number of DSMC parcels_.    

| File    | Meaning          |
|:-------------:|-------------|
| _positions_      | positions in Cartesian space |
| _U_      | velocity vector |
| _typeId_ | species index, cf. species list given in the _dsmcProperties_ dictionary |
| _newParcel_      | -1 if seeded at t = 0 or index of the patch the simulator entered the domain |
| _origProcId_ | index of the processor dealing with the simulator |
| _origId_ | local particle index in processor _origProcId_ |
| _classification_      | not used, to be revised |
|   |  |
| _ERot_      | rotational energy |
| _vibLevel_      | vibrational energy level for each vibrational energy mode |
| _ELevel_      | electronic energy level |

&nbsp;

### 3.2 Initial volume fields 
 
+ _dsmcSigmaTcRMax_ is a first estimate of the maximum value taken by the product of the collision cross-section by the relative speed. For a gas mixture, it is usually obtained by considering the properties (diameter, omega, alpha) of the most abundant species. As the simulation proceeds, this field is updated as soon as a new local maximum is found. It requires no user intervention.

+ _cellLevel_ represents the level of refinement of each cell. At _t_ = 0, it is equal to 0 which means that all cells are root cells (they cannot be further coarsened). This field will only be used when the AMR flag is passed as an argument to the main DSMC executable.
