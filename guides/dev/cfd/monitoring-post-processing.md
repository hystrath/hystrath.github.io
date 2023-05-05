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
  <a href="https://hystrath.github.io/guides/dev/cfd/numerics/#1-time-schemes" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Time schemes</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/numerics/#2-flux-schemes" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Flux schemes</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/numerics/#3-other-spatial-schemes" style="padding-top:4px;"><span style="font-size:13px">&nbsp;&nbsp; 3) Other spatial schemes</span></a>
  
  <a href="https://hystrath.github.io/guides/dev/cfd/advanced/"><b>I. ADVANCED</b></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/advanced/#1-on-the-fly-dictionary-editing" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) On-the-fly editing</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/advanced/#2-bounding-the-temperature-field" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Bounding the temperature</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/advanced/#3-adaptive-mesh-refinement" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Adaptive mesh refinement</span></a>
  
  <a href="https://hystrath.github.io/guides/dev/cfd/monitoring-post-processing" style="background-color:#FFCCCC"><b>J. MONITORING & POST-PROCESSING</b></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/monitoring-post-processing/#1-monitoring" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Monitoring</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/monitoring-post-processing/#2-post-processing" style="background-color:#FFE6E6; padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Post-processing</span></a>
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

# Monitoring & Post-processing

---  
## 1) Monitoring 

### 1.1 Wall heat flux  

Pre-requirement: the patch type in <dirname>constant/polyMesh/</dirname><dict>boundary</dict> has to be <dictval>wall</dictval>.  

Open the <dict>transportProperties</dict> dictionary and make sure the switch is active  

```c++
    writeWallHeatFlux              on;
```

The field named _wallHeatFlux_ will be printed as a result in each time folder. In addition, the wall heat flux is integrated for each wall and printed in the log file at write time

```c++
Wall heat fluxes [W]
Patch 4 named lowerWall: 416.2644537
```

Thus, the integrated wall heat flux can easily be monitored (and later plotted) during the simulation using the _grep_ command. In the present case

```sh
grep lowerWall log.hy2Foam
```

Alternatively, use the dedicated monitoring script given in the <dirname>gnuplot/</dirname> folder, called _monitorIntegratedWallHeatFlux_, and replace _#patchName_ by the name of the wall patch.  

```c++
set output "gnuplot/integratedWallHeatFlux.eps"

set size 0.95,0.47
set origin 0.03,0.53
set xlabel "Time  [sec]"
set ylabel "Integrated wall heat flux  [kW]"

plot \
"< cat log.hy2Foam | grep -e 'named #patchName:' -e '^Time =' | awk '/^Time =/,/^Time =/ {lastc = $0; next}{ if ( lastc != \"\") { print lastc; lastc = \"\"; } print }' $1 | cut -d ':' -f 2 | cut -d '=' -f 2 | paste -d ' ' - -" u 1:($2/1000.0) w l ls 1 lw 1.8 not
```

&nbsp;

### 1.2 Wall shear stress

In the <dirname>system/</dirname><dict>controlDict</dict> dictionary, uncomment the include statement that prints surface quantities 
  
```c++
functions
{
    //#include "probes"
    
    //#include "forces"

    #include "surfaceQuantities"
}
```

and review/edit the relevant subdictionary in the <dirname>system/</dirname><dict>surfaceQuantities</dict> dictionary

```c++
wallShearStress
{
    type            wallShearStress;
    libs            ("libhyStrathFieldFunctionObjects.so");
    patches         ("cylinder");
    writeControl    outputTime;
    log             no;
}
```

&nbsp;

### 1.3 Forces

In the <dirname>system/</dirname><dict>controlDict</dict> dictionary, uncomment the include statement that prints forces and aerodynamic coefficients
  
```c++
functions
{
    //#include "probes"
    
    #include "forces"

    //#include "surfaceQuantities"
}
```

Open the <dirname>system/</dirname><dict>forces</dict> dictionary  

```c++
#include "../0/include/initialConditions"

forces
{
    type forces;
    libs ("libhyStrathForces.so");
    log false;
    writeFields false;
    patches (cylinder); // edit accordingly
    CofR (0 0 0);
    dragDir (1 0 0);
    liftDir (0 1 0);
    pitchAxis (0 0 1);
}

forceCoeffs
{
    #include "../0/include/initialConditions"

    type forceCoeffs;
    libs ("libhyStrathForces.so");
    log false;
    writeFields false;
    patches (cylinder); // edit accordingly
    rho rhoInf;
    rhoInf $rhoInlet;
    magUInf $velocityInlet;
    CofR (0 0 0);
    dragDir (1 0 0);
    liftDir (0 1 0);
    pitchAxis (0 0 1);
    lRef 0.05; // edit accordingly, see constant/transportProperties/rarefiedParameters/characteristicLength
    Aref 1.96646e-05; // edit accordingly
}
```

Review and edit the relevant entries. Forces / aerodynamic coefficients (_e.g._ drag coefficient) can be monitored using the script file given in the <dirname>gnuplot/</dirname> folder
  
```c++
set output "gnuplot/dragCoefficient.eps"

set size 0.95,0.47
set origin 0.03,0.53
set xlabel "Write time"
set ylabel "Drag coefficient"

plot \
"< cat log.hy2Foam | grep 'Cd' | cut -d '=' -f 2" w l ls 1 not
```

&nbsp;

### 1.4 Residuals

An example is given below for monitoring the residuals. The fields (_**Ux**_, _**Uy**_, _**e\_{ve, N2}**_, _**e**_) may be edited depending on the simulation set-up.

```sh
set output "gnuplot/residuals.eps"

set size 0.95,0.47
set origin 0.03,0.53
set logscale y
set format y "10^{\%01T}"
set xlabel "Timestep [x 100]"
set ylabel "Residuals"
set mytics 10

plot \
"< cat log.hy2Foam | grep 'Solving for Ux' | cut -d '=' -f 2 | cut -d ',' -f 1" every 100 w l ls 12 t 'Ux initial',\
"< cat log.hy2Foam | grep 'Solving for Ux' | cut -d '=' -f 3 | cut -d ',' -f 1" every 100 w l ls 1  t 'Ux final',\
"< cat log.hy2Foam | grep 'Solving for Uy' | cut -d '=' -f 2 | cut -d ',' -f 1" every 100 w l ls 22 t 'Uy initial',\
"< cat log.hy2Foam | grep 'Solving for Uy' | cut -d '=' -f 3 | cut -d ',' -f 1" every 100 w l ls 2 t 'Uy final',\
"< cat log.hy2Foam | grep 'Solving for evel_N2' | cut -d '=' -f 2 | cut -d ',' -f 1" every 100 w l ls 32 t 'e_{vel,{N_2}} initial',\
"< cat log.hy2Foam | grep 'Solving for evel_N2' | cut -d '=' -f 3 | cut -d ',' -f 1" every 100 w l ls 3 t 'e_{vel,{N_2}} final',\
"< cat log.hy2Foam | grep 'Solving for e,' | cut -d '=' -f 2 | cut -d ',' -f 1" every 100 w l ls 42 t 'e initial',\
"< cat log.hy2Foam | grep 'Solving for e,' | cut -d '=' -f 3 | cut -d ',' -f 1" every 100 w l ls 4 t 'e final'
```

and this script can be run as follows

```c++
gnuplot gnuplot/monitorResiduals
```

<br>

---  
## 2) Post-processing

In a terminal window, type in
  
```c++
hy2Foam -postProcess -dict 'system/surfaceCoefficients' -latestTime
``` 
 
where <dirname>system/</dirname><dict>surfaceCoefficients</dict> is a dictionary that contains the desired surface coefficients. Their implementation in the <subdict>functions</subdict> sub-dictionary is shown below.

### 2.1 Pressure coefficient

In the <subdict>functions</subdict> sub-dictionary, add  
  
```c++
pressureCoefficient
{
    type            pressureCoefficient;
    libs            ("libhyStrathFieldFunctionObjects.so");
    writeControl    outputTime;
    log             no;
}
```

&nbsp;

### 2.2 Stanton number

The _**wallHeatFlux**_ field is a required input.
In the <subdict>functions</subdict> sub-dictionary, add
  
```c++
StantonNumber
{
    type            StantonNo;
    //- see constant/transportProperties/transportModels: writeWallHeatFlux
    wallHeatFlux    "wallHeatFlux"; 
    libs            ("libhyStrathFieldFunctionObjects.so");
    writeControl    outputTime;
    log             no;
}
```

&nbsp;

### 2.3 Skin-friction coefficient

The _**wallShearStress**_ field is a required input.
In the <subdict>functions</subdict> sub-dictionary, add  
  
```c++
frictionCoefficient
{
    type            frictionCoefficient;
    libs            ("libhyStrathFieldFunctionObjects.so");
    writeControl    outputTime;
    log             no;
}
```

&nbsp;

### 2.4 y+

In the <subdict>functions</subdict> sub-dictionary, add  

```c++
yPlus
{
    type            yPlus;
    libs            ("libhyStrathFieldFunctionObjects.so");
    writeControl    outputTime;
    log             no;
}
```

&nbsp;

### 2.5 ParaView

+ Open ParaView and load wall patches in _Mesh Regions_  
+ Plot any of these surface quantities using the _plotData_ filter
