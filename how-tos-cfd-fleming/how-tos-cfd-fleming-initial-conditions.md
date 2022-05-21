---
layout: page
title: How-tos
subtitle: CFD Module - Fleming release
nav-short: true
---

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()"><i class='fa fa-times'></i></a>
  <header>HOW-TOS — CFD</header>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-thermophysical/"><b>A. THERMOPHYSICAL</b></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-thermophysical/#1-species-thermophysical-properties" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Species thermo props</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-thermophysical/#2-addingremoving-energy-modes" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) +/- energy modes</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-thermophysical/#3-choosing-a-thermodem-dictionary" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) <i>thermoDEM</i> dictionary</span></a>

  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-transport/"><b>B. TRANSPORT</b></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-transport/#1-species-shear-viscosity-and-thermal-conductivity" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Species transport props</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-transport/#2-mixing-rules" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Mixing rules</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-transport/#3-mass-diffusion" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Mass diffusion</span></a>

  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-chemistry/"><b>C. CHEMISTRY</b></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-chemistry/#1-multi-species-flow" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Multi-species flow</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-chemistry/#2-non-reacting-flow" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Non-reacting flow</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-chemistry/#3-chemically-reacting-flow" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Chemically-reacting flow</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-chemistry/#4-to-go-further-chemistry-vibration-coupling" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) To go further</span></a>
  
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-nonequilibrium/"><b>D. NONEQUILIBRIUM</b></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-nonequilibrium/#1-thermal-equilibrium" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Thermal equilibrium</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-nonequilibrium/#2-thermal-non-equilibrium" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Thermal non-equilibrium</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-nonequilibrium/#3-mean-free-path-and-breakdown-parameter" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) MFP & Breakdown</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-nonequilibrium/#4-chemistry-vibration-coupling" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) Chem.-vib. coupling</span></a>
  
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-turbulence/"><b>E. TURBULENCE</b></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-turbulence/#1-laminar-flow-simulation" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Laminar</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-turbulence/#2-turbulent-flow-simulation" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Turbulent</span></a>
  
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-mhd/"><b>F. MHD</b></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-mhd/#1-enablingdisabling-mhd" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Enabling/disabling MHD</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-mhd/#2-mhd-models" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) MHD models</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-mhd/#3-electrical-conductivity-models" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Electrical conductivity</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-mhd/#4-hall-parameter" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) Hall parameter</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-mhd/#5-creation-of-an-initial-magnetic-field-and-electric-potential" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 5) Initial <i>B</i> & electric pot.</span></a>


  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-initial-conditions/" style="background-color:#FFCCCC"><b>G. INITIAL CONDITIONS</b></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-initial-conditions/#1-the-include-sub-folder" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) The <i>include/</i> sub-folder</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-initial-conditions/#2-species-mass-or-molar-fractions" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Mass or molar fractions</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-initial-conditions/#3-temperature-fields" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Temperature fields</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-initial-conditions/#4-velocity-field" style="background-color:#FFE6E6; padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) Velocity field</span></a>
  
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-advanced/"><b>H. ADVANCED</b></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-advanced/#1-local-time-stepping" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Local time stepping</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-advanced/#2-on-the-fly-dictionary-editing" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) On-the-fly editing</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-advanced/#3-bounding-the-temperature-field" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Bounding the temperature</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-advanced/#4-the-hylight-switch" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) The <i>hyLight</i> switch</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-advanced/#5-adaptive-mesh-refinement" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 5) Adaptive mesh refinement</span></a>
  
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-monitoring-post-processing"><b>I. MONITORING & POST-PROCESSING</b></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-monitoring-post-processing/#1-monitoring" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Monitoring</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-monitoring-post-processing/#2-post-processing" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Post-processing</span></a>
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

These how-tos are based on the working folder located [here](https://github.com/vincentcasseau/hyStrath/tree/master/run/hyStrath/hy2Foam/genericCase).  

# Initial conditions: the 0/ folder

---  
## 1) The include/ sub-folder

A call to a dictionary located in the <dirname>0/include/</dirname> sub-folder can be made to avoid editing multiple files in the <dirname>0/</dirname> directory, in particular if the gas mixture is composed of many species. <dictval>empty</dictval>, <dictval>cyclic</dictval>, <dictval>wedge</dictval>, <dictval>zeroGradient</dictval>, and <dictval>symmetry</dictval> boundary patches can be put into <dirname>include/</dirname><dict>boundaries</dict>. For instance, most fields in the <dirname>0/</dirname> folder require a <dictval>zeroGradient</dictval> outlet boundary condition (BC) and this patch can thus be replaced by a call to <dict>boundaries</dict>, as shown below

```c++
boundaryField
{ 
    [...]

    #include "include/boundaries"
}
```

In <dirname>include/</dirname><dict>boundaries</dict>, the outlet BC would then be written as follows
  
```c++
outlet
{
    type            zeroGradient;
}
```

Similarly, it can become handy to group the initial conditions into a single file by calling the <dirname>include/</dirname><dict>initialConditions</dict> dictionary and using the _**$**_ symbol. The *include* statement can be placed at the top of each file  

```c++
FoamFile
{
    version     2.0;
    format      ascii;
    class       volVectorField;
    object      U;
}
// * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * //

#include "include/initialConditions"

dimensions      [0 1 -1 0 0 0 0];

internalField   uniform $velocityField;

boundaryField
{
    [...]
}
```

After repeating this operation for every field in the <dirname>0/</dirname> folder, the <dirname>include/</dirname><dict>initialConditions</dict> dictionary may be defined as follows

```c++
Ttr       300;
Tve       $Ttr;
Tsurf     810;

pressure  5.18655;

UxInlet 1.131e4;
velocityInlet  ($UxInlet 0 0);
velocityField  (0 0 0);
velocityWall   (0 0 0);

Y_N2      0.767;
Y_O2      0.233;
Y_NO      0;
Y_N       0;
Y_O       0;
```

> A simple bash or python script can edit the entries of this single dictionary and running parameterized simulations becomes much easier.

<br>

---  
## 2) Species mass or molar fractions
  
Either the mass or molar fractions of all species appearing in the [_**species()**_ list](https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-chemistry/#12-addingdeleting-species) must be given in the <dirname>0/</dirname> folder. OpenFOAM's naming convention for mass fractions omits the prefix "_Y\__", which means that the mass fraction of species _N2_ is simply called _**N2**_.

To initialise the simulation using molar fractions instead, rename the species files with the prefix "_X\__", for example: _**X_N2**_. The <dirname>include/</dirname><dict>initialConditions</dict> dictionary may then be defined to contain

```c++
X_N2      0.79;
X_O2      0.21;
```

When both species mass and molar fractions are given in a time folder, the simulation will (re)start using the species mass fractions.

### 2.1 Non-catalytic wall
A non-catalytic wall BC can be set-up using the <dictval>zeroGradient</dictval> wall boundary type  

```c++
    wall
    {
        type            zeroGradient;
    }
```

&nbsp;

### 2.2 Super-catalytic wall
For a super-catalytic wall, the mixture composition at the surface is that of the free-stream and its implementation is as follows
  
```c++
    inlet
    {
        type            fixedValue;
        value           uniform $Y_#speciesName;
    }

    wall
    {
        type            fixedValue;
        value           uniform $Y_#speciesName;
    }
```

<br>

---  
## 3) Temperature fields

### 3.1 Trans-rotational temperature
The trans-rotational temperature field is printed as _**Tt**_  and must always be present in the <dirname>0/</dirname> folder.
Its implementation is identical to the temperature field in all official OpenFOAM solvers, except for the Smoluchowski temperature jump boundary condition. Some examples are given hereafter.  

+ An isothermal wall
```c++
    wall
    {
        type            fixedValue;
        value           uniform $Tsurf;
    }
```
+ An adiabatic wall
```c++
    wall
    {
        type            zeroGradient;
    }
```
+ A wall with the Smoluchowski trans-rotational temperature jump BC
```c++
    wall
    {
        type            nonEqSmoluchowskiJumpT;
        accommodationCoeff 1;
        Twall           uniform $Tsurf;
        value           uniform $Tsurf;
    }
```

&nbsp;

### 3.2 Vibro-electronic temperature

#### 3.2.1 Single vibro-electronic energy pool formulation  
Please refer to [D. §2.1](https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-nonequilibrium/#21-single-vibro-electronic-energy-pool) if you are not familiar with this code feature.  
   
The mixture vibro-electronic temperature field is called _**Tv**_ and must be present in the <dirname>0/</dirname> folder.
The Smoluchowski vibro-electronic temperature jump BC is written as follows  

```c++
    wall
    {
        type            nonEqSmoluchowskiJumpTvMix;
        accommodationCoeff 1;
        Twall           uniform $Tsurf;
        value           uniform $Tsurf;
    }
```

&nbsp;

#### 3.2.2 Multiple vibro-electronic energy pools formulation  
Please refer to [D. §2.2](https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-nonequilibrium/#22-multiple-vibro-electronic-energy-pools) if you are not familiar with this code feature.
  
The species vibro-electronic temperature fields are called _**Tv\_#speciesName**_ and there are as many fields as there are species in the <dictkey>species()</dictkey> list.
The Smoluchowski vibro-electronic temperature jump BC for molecule species is defined as

```c++
    wall
    {
        type            nonEqSmoluchowskiJumpTv;
        accommodationCoeff 1;
        Twall           uniform $Tsurf;
        value           uniform $Tsurf;
    }
```

<br>

---  
## 4) Velocity field

### 4.1 Maxwell velocity slip
The Maxwell velocity slip BC has been slightly re-written (the [mean free path](https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-nonequilibrium/#3-mean-free-path-and-breakdown-parameter) is now calculated according to the model chosen in the <dict>transportProperties</dict> dictionary) and is given by 

```c++
    wall
    {
        type            nonEqMaxwellSlipU;
        accommodationCoeff 1;
        Uwall           $velocityWall;
        refValue        uniform $velocityWall;
        valueFraction   uniform 1.0;
        thermalCreep    true;
        curvature       true;
        value           uniform $velocityWall;
    }
```

&nbsp;

### 4.2 Linear inlet ramp
The velocity at an inflow patch can be set to increase linearly with time from an <dictkey>offset</dictkey> value up to a velocity whose components are given by the entry <dictkey>refValue</dictkey>, components that are then multiplied by the <dictkey>amplitude</dictkey> scalar.  

For example, a 0.1 ms-long linear increase in velocity from 50 m/s to 1000 m/s with no angle of attack nor slip angle (_**U**_ is thus aligned with the x-axis: (1 0 0)) is obtained by setting up the <dictkey>rampInlet</dictkey> BC as

```c++
    inlet
    {
        type            rampInlet;
        refValue        uniform (1 0 0);
        offset          (50 0 0);
        amplitude       1000;
        tRamp           1e-4;
    }
```

To use the <dictkey>rampInlet</dictkey> BC, one line should be added to the <dirname>system/</dirname><dict>controlDict</dict> dictionary 
 
```c++
libs ("libstrathFiniteVolume.so");
```
