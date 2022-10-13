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
  
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-advanced/" style="background-color:#FFCCCC"><b>H. ADVANCED</b></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-advanced/#1-local-time-stepping" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Local time stepping</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-advanced/#2-on-the-fly-dictionary-editing" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) On-the-fly editing</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-advanced/#3-bounding-the-temperature-field" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Bounding the temperature</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-advanced/#4-adaptive-mesh-refinement" style="background-color:#FFE6E6; padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) Adaptive mesh refinement</span></a>
  
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-monitoring-post-processing"><b>I. MONITORING & POST-PROCESSING</b></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-monitoring-post-processing/#1-monitoring" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Monitoring</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-monitoring-post-processing/#2-post-processing" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Post-processing</span></a>
</div>

<span style="position: fixed;font-size:30px;cursor:pointer; margin:0px; top:60px;left:30px;" onclick="reopenNav()">&#9776;</span>

<script>
function openNav() {
  document.getElementById("mySidenav").style.width = "225px";
  document.getElementById("mySidenav").style.transition = "0s";
  document.getElementById('mySidenav').scrollTop = "1100";
}

function closeNav() {
  document.getElementById("mySidenav").style.width = "0px";
}

function reopenNav() {
  document.getElementById("mySidenav").style.width = "225px";
  document.getElementById("mySidenav").style.transition = "0.5s";
  document.getElementById('mySidenav').scrollTop = "1100";
}

openNav()
</script>

These how-tos are based on the working folder located [here](https://github.com/hystrath/hyStrath/tree/master/run/hyStrath/hy2Foam/genericCase).  

# Advanced features

---  
## 1) Local time stepping
  
In the <dirname>system/</dirname> directory, open the <dict>fvSchemes</dict> dictionary and edit the default <dictkey>ddtSchemes</dictkey> entry to <dictval>localEuler rDeltaT</dictval>.

The [Lorrain scramjet tutorial](https://hystrath.github.io/tutos-hyfoam/#3-lorrain-scramjet) is a suitable case to employ LTS and the aforementioned time discretisation scheme is the only modification to be made.  

> Local time stepping is currently inappropriate for axisymmetric and chemically-reacting simulations. 

<br>

---  
## 2) On-the-fly dictionary editing  

On-the-fly editing was made available primarily for computations on a high-performance computer where days can be lost waiting in a priority queue. The different steps to follow are explained below depending on the dictionary that is affected by the changes.

For the <u><dict>transportProperties</dict> dictionary</u>:  
  + Open the <dict>transportProperties</dict> dictionary  
  + Edit one or several entries inside the <subdict>rarefiedParameters</subdict> or <subdict>transportModels</subdict> subdictionaries  
  + <i>NB: if you save the file at this point, nothing will happen</i> 
  + Add a new key to the modified subdictionary
```c++
    applyChanges        true;
```
  + Save the file  
  + <i>NB: For safety, once the modification has taken effect, the file can be re-opened and the <dictkey>applyChanges</dictkey> entry can be removed. Save again.</i> 
  + If this operation worked, then your simulation should have entered into a second sub-phase of the run, as shown in the log file

Before:  

```c++
Phase no 1.0  ExecutionTime = 72.29 s  ClockTime = 74 s  Iteration no 4504 (0.04 s)
```

After:

```c++
Phase no 1.1  ExecutionTime = 72.32 s  ClockTime = 74 s  Iteration no 4505 (0.03 s)
```

For the <u><dict>thermo2TModel</dict> dictionary</u>:  
  + The steps to follow are similar to the <dict>transportProperties</dict> dictionary: add the <dictkey>applyChanges</dictkey> key after editing the desired subdictionary and save.  


For <u>any other dictionaries</u>:  
  + Make modifications to the dictionary in question (_e.g._, adding additional chemical reactions, etc) and save.  
  + Open the <dict>hTCProperties</dict> dictionary and add the <dictkey>applyChanges<dictkey> key
  + Save the <dict>hTCProperties</dict> dictionary  

As shown in the log file, the simulation enters into a new stage/phase

Before:  

```c++
Phase no 1.1  ExecutionTime = 153.02 s  ClockTime = 157 s  Iteration no 9074 (0.03 s)
```

After:

```c++
Phase no 2.0  ExecutionTime = 153.05 s  ClockTime = 157 s  Iteration no 9075 (0.03 s)
```

For all dictionaries, 

```c++
    applyChangesAtWriteTime        true;
```

can be used instead of 

```c++
    applyChanges        true;
```

should the solution needs to be printed before making modification(s) to the computation.  

<br>

For <u>boundary conditions</u>:  
  + Open the <dict>hTCProperties</dict> dictionary   
  + Add the key
```c++
    applyChangesAtWriteTimeAndWait        #numberOfSeconds;
``` 
where <dictval>#numberOfSeconds</dictval> is an integer value prescribing the time during which the simulation will be paused (give yourself enough time!).  
  + Save the <dict>hTCProperties</dict> dictionary   
  + Type in: _tail -f log.hy2Foam_ into the terminal window and wait until the next write time  
  + Once the simulation is sleeping, _reconstructPar_ can be used (for a parallel job)  
  + Edit the desired boundary condition and save  
  + Delete the _processors#ID_ folders and run: _decomposePar -latestTime_ 
  + Monitor the log file as the simulation restarts to make sure everything went well  

<br>

---  
## 3) Bounding the temperature field

In the <dict>thermophysicalProperties</dict> dictionary, the <subdict>temperatureBounds</subdict> subdictionary shown below can be copy-pasted to bound the temperature field and increase robustness. After stopping the simulation, please make sure that the minimum and maximum temperature values are <b>strictly</b> within these bounds.

```c++
temperatureBounds
{
    Tlow      200; //default is   100 K
    Thigh   40000; //default is 40000 K
}
```

If the temperature field goes unbounded, a warning will be printed in the log file for this iteration. It reports the number of times the _limit_ function had to be called and the minimum/maximum temperature recorded before bounding.

```c++
Attempt to use rho2ReactionThermo out of temperature range 3197 times during this iteration.
		Thigh: 40000 < 45289
```

<br>

---  
## 4) Adaptive mesh refinement

The <dict>dynamicMeshDict</dict> dictionary needs to be added to the standard _hy2Foam_ working directory: please refer to the official OpenFOAM tutorials and copy-paste the most appropriate one in the <dirname>constant/</dirname> folder. For instance, the following command line will list all <dict>dynamicMeshDict</dict> available

```sh
tut
find . -type f -name "dynamicMeshDict"
```

and the one located here

```sh
./multiphase/interDyMFoam/RAS/motorBike/constant/dynamicMeshDict
```

is suitable. In the <subdict>dynamicRefineFvMeshCoeffs</subdict> subdictionary, the field on which refinement/coarsening is based is given by the key <dictkey>field</dictkey>.
You can either provide the name of an existing field or input any of three hardcoded fields: <dictval>MachGradient</dictval>, <dictval>normalisedDensityGradient</dictval> or <dictval>normalisedPressureGradient</dictval>. If you choose one of these three hardcoded adaptation fields, it will be printed in the results folders. Finally, an example is given below:

```c++
dynamicRefineFvMeshCoeffs
{
    // How often to refine
    refineInterval  10000;
    
    // Field to base refinement on
    field normalisedDensityGradient;
    
    // Refine field inbetween lower..upper
    lowerRefineLevel 1.0;
    upperRefineLevel 1e6;
    
    // Unrefine field inbetween 0..unrefine
    unrefineLevel 0.5;
    
    // Have slower than 2:1 refinement
    nBufferLayers   1;
    // Refine cells only up to maxRefinement levels
    maxRefinement   3;
    // Stop refinement if maxCells reached
    maxCells        2000000;
    // Flux field and corresponding velocity field. Fluxes on changed
    // faces get recalculated by interpolating the velocity. Use 'none'
    // on surfaceScalarFields that do not need to be reinterpolated.
    correctFluxes
    (
        (pos none)
        (neg none)
        (phi none)
        (phiEp none)
        (phiEvk none)
        (amaxSf none)
        (rho_pos none)
        (rho_neg none)
        (cSf_pos none)
        (cSf_neg none)
        (e_pos none)
        (e_neg none)
        (ev_pos none)
        (ev_neg none)
        (p_pos none)
        (p_neg none)
        (rPsi_pos none)
        (rPsi_neg none)
    );
    
    // Write the refinement level as a volScalarField
    dumpLevel       true;
}
```

The command line to run _hy2Foam_ with adaptive mesh refinement, is  

```sh
hy2DyMFoam > log.hy2DyMFoam 2>&1 &
```

In the logfile, the number of adaptation cycles that the mesh has undergone at any time is given before the '/' symbol, that is 2 in the following example:

```c++
Phase no 2/1.0  ExecutionTime = 153.02 s  ClockTime = 157 s  Iteration no 9074 (0.03 s)
```

<b>NB</b>: In Paraview, on the left-hand side panel, _Properties_ tab, untick _Decompose Polyhedra_ and then set _Representation_ to _Surface With Edges_.
