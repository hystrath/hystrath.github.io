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
  
  <a href="https://hystrath.github.io/guides/dev/cfd/turbulence/"><b>E. TURBULENCE</b></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/turbulence/#1-laminar-flow-simulation" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Laminar</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/turbulence/#2-turbulent-flow-simulation" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Turbulent</span></a>
  
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
  <a href="https://hystrath.github.io/guides/dev/cfd/numerics/#1-local-time-stepping" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Local time stepping</span></a>
  
  <a href="https://hystrath.github.io/guides/dev/cfd/advanced/" style="background-color:#FFCCCC"><b>I. ADVANCED</b></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/advanced/#1-on-the-fly-dictionary-editing" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) On-the-fly editing</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/advanced/#2-bounding-the-temperature-field" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Bounding the temperature</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/advanced/#3-adaptive-mesh-refinement" style="background-color:#FFE6E6; padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Adaptive mesh refinement</span></a>
  
  <a href="https://hystrath.github.io/guides/dev/cfd/monitoring-post-processing"><b>J. MONITORING & POST-PROCESSING</b></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/monitoring-post-processing/#1-monitoring" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Monitoring</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/monitoring-post-processing/#2-post-processing" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Post-processing</span></a>
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

These guidelines are based on the working folder located [here](https://github.com/hystrath/hyStrath/tree/OF-v2112/run/hyStrath/hy2Foam/genericCase).  

# Advanced features

---  
## 1) On-the-fly dictionary editing  

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
## 2) Bounding the temperature field

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
## 3) Adaptive mesh refinement

When added to the <dirname>constant/</dirname> folder, the optional <dict>dynamicMeshDict</dict> dictionary will be read. In this section, we are interested in two types of dynamicFvMeshes: staticFvmesh and dynamicRefineFvMesh.

Use <dictval>staticFvmesh</dictval> or delete <dirname>constant/</dirname><dict>dynamicMeshDict</dict> when the mesh should not be adapted.

Use <dictval>dynamicRefineFvMesh</dictval> otherwise and implement the <subdict>dynamicRefineFvMeshCoeffs</subdict> subdictionary as shown below. The field on which refinement/coarsening is based on is given by the key <dictkey>field</dictkey>. You can either provide the name of an existing scalar field or input any of hy2Foam's hardcoded adaptation fields:
- <dictval>normalisedDensityGradient</dictval>
- <dictval>normalisedPressureGradient</dictval>  
- <dictval>normalisedTemperatureGradient</dictval>  
- <dictval>normalisedViscosityGradient</dictval>  
- <dictval>MachGradient</dictval>  
- <dictval>massFractionGradient</dictval>  
- <dictval>normalisedGradients</dictval>


<p><dictval>normalisedTemperatureGradient</dictval> and <dictval>normalisedGradients</dictval> are based on the gradients of more than one field and each can be weighted using coefficients (defaulted to 1) located in the <subdict>gradientWeights</subdict> subdictionary. These coefficients can also be used as 0/1 switches.</p>
 
If you choose one of these adaptation fields, it will be printed in the results folders.

```c++
dynamicFvMesh   dynamicRefineFvMesh; // Write staticFvmesh to disable AMR

dynamicRefineFvMeshCoeffs
{
    // How often to refine
    refineInterval  10000;
    
    // Field to base refinement on
    field normalisedDensityGradient;
    
    // Weighting factors when there is more than one field to base refinement on
    gradientWeights
    {
        rho    1.0;
        p      1.0;
        Ttr    1.0;
        Tve    1.0;
        Mach   1.0;
        mu     1.0;
        Y      1.0;
    }
    
    // Refine field inbetween lower..upper
    lowerRefineLevel 2.0;
    upperRefineLevel 1e6;
    
    // Unrefine field inbetween 0..unrefine
    unrefineLevel 0.5;
    
    // Have slower than 2:1 refinement
    nBufferLayers   4;
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
        (phiEv none)
        (amaxSf none)
    );
    
    // Write the refinement level as a volScalarField
    dumpLevel       true;
}
```

In the logfile, the number of adaptation cycles that the mesh has undergone is given before the execution time:

```c++
AdaptationCycle = 2
ExecutionTime = 153.02 s  ClockTime = 157 s  Iteration no 9074 (0.03 s)
```

<b>NB1</b>: If your results look off, please check that there aren't any _empty_ patches defined and if there are, redefine them as _symmetry_ patches.  

<b>NB2</b>: In Paraview, on the left-hand side panel, _Properties_ tab, untick _Decompose Polyhedra_ and then set _Representation_ to _Surface With Edges_.

For further information on AMR, please refer to the official OpenFOAM tutorials. Typing the following command line will list all <dict>dynamicMeshDict</dict> available

```sh
tut
find . -type f -name "dynamicMeshDict"
```
