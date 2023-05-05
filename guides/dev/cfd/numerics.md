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
  
  <a href="https://hystrath.github.io/guides/dev/cfd/numerics/" style="background-color:#FFCCCC"><b>H. NUMERICS</b></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/numerics/#1-time-schemes" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Time schemes</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/numerics/#2-flux-schemes" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Flux schemes</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/numerics/#3-other-spatial-schemes" style="background-color:#FFE6E6; padding-top:4px;"><span style="font-size:13px">&nbsp;&nbsp; 3) Other spatial schemes</span></a>
  
  <a href="https://hystrath.github.io/guides/dev/cfd/advanced/"><b>I. ADVANCED</b></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/advanced/#1-on-the-fly-dictionary-editing" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) On-the-fly editing</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/advanced/#2-bounding-the-temperature-field" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Bounding the temperature</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/advanced/#3-adaptive-mesh-refinement" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Adaptive mesh refinement</span></a>
  
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

# Numerics

---  
## 1) Time schemes

### 1.1 Euler time scheme  

The implicit first-order Euler time scheme can be selected in <dirname>system/</dirname><dict>fvSchemes</dict> as follows

```c++
ddtSchemes
{
    default           Euler;
}
```

For more information, please check the [official documentation](https://www.openfoam.com/documentation/guides/v2112/doc/guide-schemes-time-euler.html).

&nbsp;  

### 1.2 Local time stepping scheme  

To select the first-order local time stepping scheme, open the <dirname>system/</dirname><dict>fvSchemes</dict> dictionary and set

```c++
ddtSchemes
{
    default           localEuler rDeltaT;
}
```

The [Lorrain scramjet tutorial](https://hystrath.github.io/tutos/dev/hyfoam/toc/#3-lorrains-scramjet) is a suitable case to use LTS and the aforementioned time discretisation scheme is the only modification to be made.  

> Local time stepping is currently inappropriate for axisymmetric and chemically-reacting simulations.

For more information, please check the [official documentation](https://www.openfoam.com/documentation/guides/v2112/doc/guide-schemes-time-local-euler.html).

&nbsp;

### 1.3 Other time schemes

For other time schemes, please refer to the [official documention](https://www.openfoam.com/documentation/guides/v2112/doc/guide-schemes-time.html). 

<br>

---  
## 2) Flux schemes  

### 2.1 Kurganov and Tadmor


```c++
fluxScheme            Kurganov;
```

```c++
fluxScheme            Tadmor;
``` 

&nbsp;

### 2.2 AUSM+up

```c++
fluxScheme            AUSM+up;

fluxSchemeCoefficients
{
    AUSM+upCoefficients
    {
        MachInf          1.0;
/*        scalingFactor    1.0;*/
        
        alpha         0.1875;
        beta           0.125;
        sigma            1.0;
        Kp              0.25;
        Ku              0.75;
    }
}
```

<br>

---  
## 3) Other spatial schemes  

For other spatial schemes, please refer to the [official documention](https://www.openfoam.com/documentation/guides/v2112/doc/guide-schemes-time.html). 
