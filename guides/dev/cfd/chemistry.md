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

  <a href="https://hystrath.github.io/guides/dev/cfd/chemistry/" style="background-color:#FFCCCC"><b>C. CHEMISTRY</b></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/chemistry/#1-multi-species-flow" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Multi-species flow</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/chemistry/#2-non-reacting-flow" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Non-reacting flow</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/chemistry/#3-chemically-reacting-flow" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Chemically-reacting flow</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/chemistry/#4-to-go-further-chemistry-vibration-coupling" style="background-color:#FFE6E6; padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) To go further</span></a>
  
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
  
  <a href="https://hystrath.github.io/guides/dev/cfd/advanced/"><b>H. ADVANCED</b></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/advanced/#1-local-time-stepping" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Local time stepping</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/advanced/#2-on-the-fly-dictionary-editing" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) On-the-fly editing</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/advanced/#3-bounding-the-temperature-field" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Bounding the temperature</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/advanced/#4-adaptive-mesh-refinement" style="background-color:#FFE6E6; padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) Adaptive mesh refinement</span></a>
  
  <a href="https://hystrath.github.io/guides/dev/cfd/monitoring-post-processing"><b>I. MONITORING & POST-PROCESSING</b></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/monitoring-post-processing/#1-monitoring" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Monitoring</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/monitoring-post-processing/#2-post-processing" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Post-processing</span></a>
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

These guidelines are based on the working folder located [here](https://github.com/hystrath/hyStrath/tree/master/run/hyStrath/hy2Foam/genericCase).  

# Chemistry modelling

---
## 1) Multi-species flow

### 1.1 The chemDicts/ folder
In the <dirname>constant/</dirname> directory, the <dirname>chemDicts/</dirname> folder is storing default chemistry dictionaries. It is advised not to modify the original files for future reference. Thus, a copy of the most appropriate <dict>hTCReactions#name</dict> dictionary can be made into the <dirname>constant/</dirname> folder.  

The path to the <dict>hTCReactions#name</dict> dictionary needs to be edited accordingly in <dict>thermophysicalProperties</dict>. This done using the  <dictkey>foamChemistryFile</dictkey> entry as  

```c++
    foamChemistryFile        "<constant>/hTCReactions#name";
```

Available <dict>hTCReactions#name</dict> dictionaries are

| Chemistry dict name    | Reference
|:-------------:|:-------------:|
| <dict>hTCReactionsEarth93</dict>      |  Park _et al._, 1993 |
| <dict>hTCReactionsMars74</dict>      |  Evans, Schexnayder & Grose, 1974          |
| <dict>hTCReactionsMars94</dict>      |  Park _et al._, 1994           |
| <dict>hTCReactionsDK</dict>      |  Dunn & Kang, 1973          |
| <dict>hTCReactionsES</dict>      |  Evans & Schexnayder, 1980          |
| <dict>hTCReactionsJ92</dict>      |  Jachimowski, 1992           |
| <dict>hTCReactionsJ92_fwd</dict>      |  Jachimowski, forward reactions only, 1992           |
| <dict>hTCReactionsQK<dict>      |  Quantum-kinetics, Scanlon _et al._, 2015      |

&nbsp;  

### 1.2 Adding/deleting species   
In the <dict>hTCReactions#name</dict> dictionary, the species composing the gas mixture need to be uncommented in <dictkey>species()</dictkey>. For a 5-species air mixture  
 
```c++
    species
    (
        N2
        O2
        NO
      //N2+
      //O2+
      //NO+
        N
        O
      //N+
      //O+
      //e-
    );
```

As shown in this example, a specific order must be respected  
1. molecules  
2. charged molecules  
3. atoms  
4. charged atoms  
5. electrons  

All species listed in the <dict>hTCReactions#name</dict> dictionary should also be present in <dict>thermoDEM</dict> and the <dirname>0/</dirname> directory. This is discussed in [G. Initial conditions](https://hystrath.github.io/guides/dev/cfd/initial-conditions/#2-species-mass-fractions).

### 1.3 Printing species quantities  
In the <dict>hTCProperties</dict> dictionary, switch <dictval>on</dictval>/<dictval>off</dictval> any of these booleans to print the desired fields 
 
```c++
mixtureOutputs
{
    molarFraction       off;
    numberDensity       off;
    partialDensity      off;
    partialPressure     off;
    degreesOfFreedom    off;
    vibrationalEnergy   off;
}
```

<br>

---

## 2) Non-reacting flow

### 2.1 Disable chemistry  
In the <dict>hTCProperties</dict> dictionary, switch <dictval>off</dictval> the <dictkey>active</dictkey> boolean as follows   
 
```c++
     active          off;
```  

<br>

---  
## 3) Chemically-reacting flow  

### 3.1 Enable chemistry
In the <dict>hTCProperties</dict> dictionary, switch <dictval>on</dictval> the <dictkey>active</dictkey> boolean as follows 
   
```c++
     active          on;
```  

In the <dict>chemistryProperties</dict> dictionary, the same operation must be repeated with the <dictkey>chemistry</dictkey> switch  

```c++
     chemistry          on;
     initialChemicalTimeStep          1e-09;
```

where the <dictkey>initialChemicalTimeStep</dictkey> entry sets the initial chemical time-step.  

### 3.2 Implementing a chemical reaction  
#### 3.2.1 Forward reaction  
In the <dict>hTCReactions#name</dict> dictionary, the <subdict>reactions</subdict> subdictionary is enumerating the different chemical reactions to consider. The modified Arrhenius law coefficients are given in the table below

| Coefficient    | Meaning | Units |
|:-------------:|:-------------|:------:|
| <dictkey>A</dictkey>      |  pre-exponential factor | m&#179;/kmol/s |
| <dictkey>beta</dictkey>      |  temperature exponent          |   -     |
| <dictkey>Ta</dictkey>      |  temperature of activation           |   K    |

<div style="line-height:50%;">
    <br>
</div>
    
> <b>NB</b>: Please pay attention to the units of the pre-exponential factor, <dictkey>A</dictkey>, when customising your own <dict>hTCReactions#name</dict> dictionary.

The reaction <dictkey>type</dictkey> is defined as <dictval>irreversibleArrheniusReaction</dictval>.

```c++
reactions
{
    // Reaction no 1
    oxygenAtomicNitrogenReaction
    {
        type     irreversibleArrheniusReaction;
        reaction "O2 + N = 2O + N";
        A        1.0e19;
        beta     -1.5;
        Ta       59500; 
    }
}
```

&nbsp;

#### 3.2.2 Reverse reaction   
Additional coefficients entering into the calculation of the reverse reaction rate constant [1], _k\_rev_, are given below  

| Extra coefficient    | Meaning | Units |
|:-------------:|:-------------|:------:|
| <dictkey>ni()</dictkey>      |  mixture number density list | m&#8315;&#179; |
| <dictkey>A0()</dictkey> - <dictkey>A4()</dictkey>      | Park's coefficients for _k\_rev_  |   -    |
 
In the <dict>hTCReactions#name/</dict><subdict>reactions</subdict> dictionary, the reaction <dictkey>type</dictkey>  can either be <dictval>reversibleArrheniusReaction</dictval> or <dictval>nonEquilibriumReversibleArrheniusReaction</dictval>. Their implementation is exemplified hereafter    

```c++
reactions
{
    // Reaction no 1
    oxygenAtomicNitrogenReaction
    {
        type     reversibleArrheniusReaction;
        reaction "O2 + N = 2O + N";
        A        1.0e19;
        beta     -1.5;
        Ta       59500;
        
        ni       (1e20 1e21 1e22 1e23 1e24 1e25);
        A0       (1.8103 0.91354 0.64183 0.55388 0.52455 0.50989);
        A1       (8.8685 9.2238 9.3331 9.3678 9.3793 9.3851);
        A2       (3.5716 2.2885 1.9026 1.7763 1.7342 1.7132);
        A3       (-7.3623 -6.7969 -6.6277 -6.572 -6.5534 -6.5441);
        A4       (0.083861 0.046338 0.035151 0.031445 0.030209 0.029591);  
    }

    // Reaction no 2
    hydrogenAtomOxygenReaction
    {
        type     nonEquilibriumReversibleArrheniusReaction;
        reaction "H + O2 = OH + O";
        forward
        {
            A        2.2e11;
            beta     0;
            Ta       8454;
        }
        reverse
        {
            A        1.42e4;
            beta     0;
            Ta       1664;
        }
    }
}
```

<p><img src="/docs/img/publis.png" width="40">[1] C. Park. <i>Nonequilibrium Hypersonic Aerothermodynamics</i>, Wiley International, New
York, <b>1990</b></p>

&nbsp;

#### 3.2.3 Third-body interaction  
In the <dict>hTCReactions#name/</dict><subdict>reactions</subdict> dictionary, the <dictkey>type</dictkey> of the reaction is modified to either <dictval>irreversiblethirdBodyArrheniusReaction</dictval>, <dictval>reversiblethirdBodyArrheniusReaction</dictval>, or <dictval>nonEquilibriumReversiblethirdBodyArrheniusReaction</dictval>. An example is given below and many more can be found in the <dirname>chemDicts/</dirname> folder.  

```c++
reactions
{
    // Reaction no 1
    oxygenTBReaction
    {
        type     reversiblethirdBodyArrheniusReaction;
        reaction "O2 + M = 2O + M";
        A        2.0e18;
        beta     -1.5;
        Ta       59500;
        coeffs
        (
            ("N2" 1.0)
            ("O2" 1.0)
            ("NO" 1.0)
          //("N2+" 1.0)
          //("O2+" 1.0)
          //("NO+" 1.0)
            ("N" 5.0)
            ("O" 5.0)
          //("N+" 5.0)
          //("O+" 5.0)
          //("e-" 0.0)
        );
        
        ni       (1e20 1e21 1e22 1e23 1e24 1e25);
        A0       (1.8103 0.91354 0.64183 0.55388 0.52455 0.50989);
        A1       (8.8685 9.2238 9.3331 9.3678 9.3793 9.3851);
        A2       (3.5716 2.2885 1.9026 1.7763 1.7342 1.7132);
        A3       (-7.3623 -6.7969 -6.6277 -6.572 -6.5534 -6.5441);
        A4       (0.083861 0.046338 0.035151 0.031445 0.030209 0.029591);  
    }
}
```
<div style="line-height:50%;">
    <br>
</div>
    
> <b>NB</b>: All species present in the <dictkey>species()</dictkey> list must be present in the <dictkey>coeff()</dictkey> list, no more, no less. 

### 3.3  Increase robustness
Backward reaction rates may sometimes cause problems in low-temperature regions and yield the simulation to crash. A minimum temperature value, <dictkey>Tmin</dictkey>, can be introduced into the rate calculations to increase robustness [1]. A switch called <dictkey>modifiedTemperature</dictkey> located in the <dict>chemistryProperties</dict> dictionary is there for this purpose.

```c++
modifiedTemperature on;
modifiedTemperatureCoeffs
{
    Tmin      800.0;
    epsilon   80.0;
}
```

<p><img src="/docs/img/publis.png" width="40">[1] L. C. Scalabrin, "Numerical Simulation of Weakly Ionized Hypersonic Flow over Reentry Capsules," PhD thesis, University of Michigan, Ann Arbor (US), <b>2007</b> &nbsp; <a href="http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.453.3057&rep=rep1&type=pdf" target="_blank" style="color:orange"> [PDF→]</a></p>

<br>

---  

## 4) To go further: chemistry-vibration coupling  
This aspect is detailed in [D. Nonequilibrium](https://hystrath.github.io/guides/dev/cfd/nonequilibrium/#4-chemistry-vibration-coupling).
