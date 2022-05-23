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

  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-transport/" style="background-color:#FFCCCC"><b>B. TRANSPORT</b></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-transport/#1-species-shear-viscosity-and-thermal-conductivity" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Species transport props</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-transport/#2-mixing-rules" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Mixing rules</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-transport/#3-mass-diffusion" style="background-color:#FFE6E6; padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Mass diffusion</span></a>

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


  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-initial-conditions/"><b>G. INITIAL CONDITIONS</b></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-initial-conditions/#1-the-include-sub-folder" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) The <i>include/</i> sub-folder</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-initial-conditions/#2-species-mass-or-molar-fractions" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Mass or molar fractions</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-initial-conditions/#3-temperature-fields" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Temperature fields</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-initial-conditions/#4-velocity-field" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) Velocity field</span></a>
  
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

These how-tos are based on the working folder located [here](https://github.com/vincentcasseau/hyStrath/tree/master/run/hyStrath/hy2Foam/genericCase).  

# Transport modelling

---
## 1) Species shear viscosity and thermal conductivity

### 1.1 Inviscid simulation    

This is done in two steps:  
  + in the <dict>thermophysicalProperties/</dict><subdict>thermoType</subdict> dictionary, edit the <dictkey>transport</dictkey> entry to <dictval>constant</dictval>;
  + in the <dict>thermoDEM/</dict><subdict>#speciesName/transport/constant</subdict> dictionary, for all species present in the gas mixture, edit the value of the entry <dictkey>mu</dictkey> to be <dictval>0</dictval>.

### 1.2 Viscous simulation with constant shear viscosity and thermal conductivity

Repeat the two steps presented in [§1.1](https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-transport/#11-inviscid-simulation) but edit <dictkey>mu</dictkey> to the desired value (units: kg/m/s). The constant thermal conductivities are set using the <dictkey>kappa</dictkey> (trans-rotational energy mode) and <dictkey>kappave</dictkey> (vibro-electronic energy mode) entries (units: kg/m/s<sup>3</sup>/K).

### 1.3 Other transport models

The names of all other available transport models to be loaded using the <dictkey>transport</dictkey> keyword in the <dict>thermophysicalProperties/</dict><subdict>thermoType</subdict> dictionary are  

| Transport model name    | Parameters          |
|:-------------:|-------------|
| <dictval>SutherlandEucken</dictval>      | <dictkey>As</dictkey>, <dictkey>Ts</dictkey>     |
| <dictval>BlottnerEucken</dictval> | <dictkey>A</dictkey>, <dictkey>B</dictkey>, <dictkey>C</dictkey>     |
| <dictval>CEA</dictval>      | <dictkey>temp()</dictkey>, <dictkey>visco()</dictkey>, <dictkey>kappa()</dictkey>      |
| <dictval>powerLawEucken</dictval> | <dictkey>diameter</dictkey>, <dictkey>omega</dictkey>     |

The coefficients of these models can be found in the <dict>thermoDEM/</dict><subdict>#speciesName</subdict> dictionary. The first three models are using coefficients located in the <subdict>transport</subdict> subdictionary, while the <dictval>powerLawEucken</dictval> model requires the species diameter, <dictkey>diameter</dictkey>, and the species temperature exponent of viscosity, <dictkey>omega</dictkey>, located in the <subdict>specie</subdict> subdictionary.

### 1.4 Print species shear viscosity and thermal conductivity
In the <dict>transportProperties/</dict><subdict>transportModels</subdict> dictionary, edit the state of these two switches to <dictval>on</dictval>  

```c++
    writeViscositySpecies          on;  
    writeThermalConducSpecies      on; 
```

<br>

---
## 2) Mixing rules

The available mixing rules are given in the following Table 

| Mixing rule name    | Parameters          |
|:-------------:|:-------------:|
| <dictval>molar</dictval>      | - |
| <dictval>Wilke</dictval>      | - |
| <dictval>ArmalySutton</dictval> | <dictkey>correctedArmalySutton</dictkey>    |

and the dedicated entry, <dictkey>mixingRule</dictkey>, is located in the <dict>transportProperties/</dict><subdict>transportModels</subdict> dictionary. The mixture shear viscosity and thermal conductivity can be printed by switching <dictval>on</dictval> the following booleans
  
```c++
    writeViscosityMixture          on;  
    writeThermalConducMixture      on; 
```  
<div style="line-height:50%;">
    <br>
</div>
    
> <b>NB</b>: There are no reasons to use the <dictval>molar</dictval> mixing rule other than for single-species flows or zero-dimensional heat baths.

<br>

---
## 3) Mass diffusion

### 3.1 Disable multi-species diffusion
In the <dict>transportProperties/</dict><subdict>transportModels</subdict> dictionary, edit the following entries to
  
```c++
    multiSpeciesTransport         noSpeciesDiffusion;  
    binaryDiffusionModel          noBinaryDiffusionModel;
```
&nbsp;

### 3.2 Lewis number model
In the <dict>transportProperties/</dict><subdict>transportModels</subdict> dictionary, edit the following entries to 
 
```c++
    multiSpeciesTransport         LewisNumber;  
    binaryDiffusionModel          noBinaryDiffusionModel;
```

The Lewis number value can be found in the <subdict>diffusionModelParameters</subdict> subdictionary

```c++
    diffusionModelParameters
    {
        LewisNumber                    1.4;
        
        [...]
    }
``` 

&nbsp; 

### 3.3 Fick's law and binary diffusion models
In the <dict>transportProperties/</dict><subdict>transportModels</subdict> dictionary, edit the following entry to
  
```c++
    multiSpeciesTransport         Fick; 
``` 

Binary diffusion coefficients can be calculated according to any of the models presented in the Table below  

| Binary diffusion model name    | Parameters          |
|:-------------:|-------------|
| <dictval>constantBinaryDiffusionModel</dictval>      | <dictkey>constantBinaryDiffusionModelCoefficients</dictkey> |
| <dictval>collisionData</dictval>      | <dictkey>collisionDataModel</dictkey>, <subdict>collisionData</subdict> dict     |
| <dictval>Stephani</dictval> | <dictkey>molWeight</dictkey>, <dictkey>diameter</dictkey>, <dictkey>omega</dictkey>     |

The <dictkey>constantBinaryDiffusionModelCoefficients</dictkey> and <dictkey>collisionDataModel</dictkey> entries can be found in the <subdict>diffusionModelParameters</subdict> subdictionary. <dictkey>collisionDataModel</dictkey> accepted values are <dictval>"Gupta1989D"</dictval>, <dictval>"Gupta1989O"</dictval>, <dictval>"Gupta1990D"</dictval>, <dictval>"Gupta1990O"</dictval>, and <dictval>"Wright2005O"</dictval>.

Example for a binary Nitrogen-Oxygen mixture:  

```c++
multiSpeciesTransport        Fick;
binaryDiffusionModel         collisionData;  
  
diffusionModelParameters   
{  
     collisionDataModel          "Gupta1989D";   
}  
  
collisionData
{
    tabulatedInteractions
    { 
        // NASA-TM-101528 (Gupta, Yos, Thompson: Feb. 1989)
        // Document ID: 19890011822
        // A review of reaction rates and thermodynamic and transport 
        // properties for the 11-species air model for chemical and thermal
        // nonequilibrium calculations to 30000 K
        Gupta1989D
        {
            // Table VI
            Dbar
            {
                N2_N2 (0.0 0.0112 1.16182 -11.3091);  
                N2_O2 (0.0 0.0465 0.9271 -8.1137);         
            } 
        }
    }  
}  
```  

&nbsp;

### 3.4 SCEBD model 
In the <dict>transportProperties/</dict><subdict>transportModels</subdict> dictionary, edit the following entry to  

```c++
    multiSpeciesTransport         SCEBD; 
``` 

Please refer to [§3.3](https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-transport/#33-ficks-law-and-binary-diffusion-models) for the list of available binary diffusion coefficient models.

### 3.5 Additional features (to Fick and SCEBD models)
Results using the non-corrected forms of Fick's law and the SCEBD model can be obtained by switching on the <dictkey>useNonCorrectedForm</dictkey> boolean located in the <subdict>diffusionModelParameters</subdict> subdictionary (for comparison with the corrected form only). It is turned <dictval>off</dictval> by default, which means that the sum of the diffusive fluxes is zero.

> <b>NB</b>: The <dictkey>useNonCorrectedForm</dictkey> entry can be deleted from the <subdict>diffusionModelParameters</subdict> subdictionary if you wish (safer).

In the same subdictionary, the <dictkey>addPressureGradientTerm</dictkey> switch allows to account for the effects of pressure gradients.

<!--<br>-->
<!--<a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-thermophysical/" class="btn btn-neutral float-left" title="A. THERMOPHYSICAL" accesskey="p" rel="prev"><span class="fa fa-arrow-circle-left" aria-hidden="true"></span> Previous</a>-->
<!--<a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-chemistry/" class="btn btn-neutral float-right" title="C. CHEMISTRY" accesskey="n" rel="next">Next <span class="fa fa-arrow-circle-right" aria-hidden="true"></span></a>-->
