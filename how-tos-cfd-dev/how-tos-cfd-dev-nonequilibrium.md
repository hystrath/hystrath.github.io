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
  
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-nonequilibrium/" style="background-color:#FFCCCC"><b>D. NONEQUILIBRIUM</b></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-nonequilibrium/#1-thermal-equilibrium" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Thermal equilibrium</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-nonequilibrium/#2-thermal-non-equilibrium" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Thermal non-equilibrium</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-nonequilibrium/#3-mean-free-path-and-breakdown-parameter" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) MFP & Breakdown</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-nonequilibrium/#4-chemistry-vibration-coupling" style="background-color:#FFE6E6; padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) Chem.-vib. coupling</span></a>
  
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
  
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-advanced/"><b>H. ADVANCED</b></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-advanced/#1-local-time-stepping" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Local time stepping</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-advanced/#2-on-the-fly-dictionary-editing" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) On-the-fly editing</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-advanced/#3-bounding-the-temperature-field" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Bounding the temperature</span></a>
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
  document.getElementById('mySidenav').scrollTop = "540";
}

function closeNav() {
  document.getElementById("mySidenav").style.width = "0px";
}

function reopenNav() {
  document.getElementById("mySidenav").style.width = "225px";
  document.getElementById("mySidenav").style.transition = "0.5s";
  document.getElementById('mySidenav').scrollTop = "540";
}

openNav()
</script>

These how-tos are based on the working folder located [here](https://github.com/hystrath/hyStrath/tree/master/run/hyStrath/hy2Foam/genericCase).  

# Non-equilibrium flow modelling

The solver's default behaviour is to use the two-temperature formulation with multiple vibro-electronic energy pools. In the <dict>thermophysicalProperties</dict> dictionary, two switches, <dictkey>downgradeToSingleTv</dictkey> and <dictkey>downgradeToSingleTemperature</dictkey>, can alter this behaviour to either produce a two-temperature solver with a single vibro-electronic energy pool or a single-temperature solver.  

---  
## 1) Thermal equilibrium

The single-temperature solver, _hyFoam_, is obtained with  

```c++
    downgradeToSingleTv          no;
    downgradeToSingleTemperature yes;
```  

There is a unique application, called _hy2Foam_, for both solvers: the use of _hyFoam_ is more of a naming convention to clarify that the single-temperature model is adopted. All two-temperature-related object pointers are not allocated and the vibrational energy equation is not solved.  

The command line to run _hyFoam_ is thus identical to _hy2Foam_   

```sh
hy2Foam > log.hyFoam 2>&1 &
```

<br>

---  
## 2) Thermal non-equilibrium

As mentioned in the introduction, the non-equilibrium solver _hy2Foam_ can take two forms: it can either solve the mixture vibro-electronic energy equation or multiple vibro-electronic energy equations. The choice of the former variant is <u>highly recommended</u>.

### 2.1 Single vibro-electronic energy pool  
The <dict>thermophysicalProperties</dict> dictionary setup in this variant of _hy2Foam_ is  

```c++
    downgradeToSingleTv          yes;
    downgradeToSingleTemperature no;
```

The path to the non-equilibrium dictionary is also set in <dict>thermophysicalProperties</dict>   

```c++
    twoTemperatureDictFile "<constant>/thermo2TModel";
```

and its default name is <dict>thermo2TModel</dict>. It is composed of one subdictionary, <subdict>thermalRelaxationModels</subdict>, for the selection of the energy transfer models, and various subdictionaries to store the models coefficients. The energy transfers that are allowed to take place are vibrational-translational (V—T) and heavy-particles — electrons (H—e). If the gas mixture is composed of neutral species only, then H—e energy transfer is automatically discarded.
The subdictionary's default implementation is as follows

```c++
thermalRelaxationModels
{
    VT
    {
        relaxationType        LandauTellerVT;
        model                 LeMANSMWP;
        fullCoeffsForm        on;
        overwriteDefault      on;
        speciesDependent      on;
        collidingPair         on;
    }
    
    he
    {
        relaxationType        AppletonBray;
    }
}
```

As is customary, the Landau-Teller equation is employed for V—T energy exchange and the V—T relaxation time is obtained using the Millikan & White semi-empirical formula, with or without Park's correction. In the example above, the coefficients entering in the calculation of the V—T relaxation time are made colliding-pair specific and are read from one of the subsequent subdictionaries (since <dictkey>overwriteDefault</dictkey> is <dictval>on</dictval>). The meaning of the all entries in <subdict>thermalRelaxationModels</subdict> is given in the Table below

<table>
  <tr>
    <td align="center" colspan="3"><b>V—T energy exchange</b></td>
  </tr>
  <tr>
    <td align="center"><b>Key</b></td>
    <td align="center"><b>Values</b></td>
    <td align="center"><b>Meaning</b></td>
  </tr>
  <tr>
    <td align="center"><dictkey>relaxationType</dictkey></td>
    <td align="center"><dictval>LandauTellerVT</dictval> &nbsp; <i class="fa fa-thumbs-up" style="font-size:18px;color:green" title="recommended"></i> <br /> <dictval>noVTEnergyTransfer</dictval>  </td>
    <td align="center">name of the V—T energy transfer model</td>
  </tr>
  <tr>
    <td align="center"><dictkey>model</dictkey></td>
    <td align="center"><dictval>LeMANSMWP</dictval> &nbsp; <i class="fa fa-thumbs-up" style="font-size:18px;color:green" title="recommended"></i> <br /> <dictval>MillikanWhite</dictval></td>  
    <td align="center">if <dictval>LandauTellerVT</dictval> is chosen, whether to use Park's correction or not</td>
  </tr>
  <tr>  
    <td align="center"><dictkey>fullCoeffsForm</dictkey></td>
    <td align="center"><dictval>on</dictval> &nbsp; <i class="fa fa-thumbs-up" style="font-size:18px;color:green" title="recommended"></i> <br /> <dictval>off</dictval></td>
    <td align="center">whether to use the tabulated data or the Millikan and White formulas for _A_ and _B_</td>
  </tr>
  <tr>
    <td align="center"><dictkey>overwriteDefault</dictkey></td>
    <td align="center"><dictval>on</dictval> &nbsp; <i class="fa fa-thumbs-up" style="font-size:18px;color:green" title="recommended"></i> <br /> <dictval>off</dictval></td>
    <td align="center">if <dictkey>fullCoeffsForm</dictkey> is <dictval>on</dictval>, whether to use the subdictionary values (<subdict>MillikanWhite</subdict> or <subdict>Park</subdict>) or the harcoded values</td>
  </tr>
  <tr>
    <td align="center"><dictkey>speciesDependent</dictkey></td>
    <td align="center"><dictval>on</dictval> &nbsp; <i class="fa fa-thumbs-up" style="font-size:18px;color:green" title="recommended"></i> <br /> <dictval>off</dictval></td>
    <td align="center">if <dictkey>overwriteDefault</dictkey> is <dictval>on</dictval>, whether to use different coeffs for different species or coeffs common to all species</td>
  </tr>
  <tr>
    <td align="center"><dictkey>collidingPair</dictkey></td>
    <td align="center"><dictval>on</dictval> &nbsp; <i class="fa fa-thumbs-up" style="font-size:18px;color:green" title="recommended"></i> <br /> <dictval>off</dictval></td>
    <td align="center">if <dictkey>speciesDependent</dictkey> is <dictval>on</dictval>, whether to use different coeffs for different colliding partners or not</td>
  </tr>
</table>

The H—e energy transfer of Appleton & Bray (1963) does not require any input. It can be disabled using a <dictkey>relaxationType</dictkey> set to <dictval>noHEEnergyTransfer</dictval>.


### 2.2 Multiple vibro-electronic energy pools

<p style="text-align:center; color:Tomato"><strong> >> Unavailable until further notice<< </strong></p>

In the current version of the code, this configuration has several limitations that are as follows
   + the gas mixture must be composed of neutral particles only  
   + the electronic mode of all particles must be turned off (see [A. §2.2](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-thermophysical/#22-disablingenabling-the-electronic-mode-of-a-particle))
   + the molecules must be planar  

If the above conditions are fulfilled, then the <dict>thermophysicalProperties</dict> dictionary setup is
  
```c++
    downgradeToSingleTv          no;
    downgradeToSingleTemperature no;
```

In addition to the energy exchange processes described in [§2.1](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-nonequilibrium/#21-single-vibro-electronic-energy-pool), the <subdict>thermalRelaxationModels</subdict> subdictionary is complemented with vibrational-vibrational (V—V) and electron-vibrational (e—V) energy transfers and the <subdict>thermalRelaxationModels</subdict> takes the following form  

```c++
thermalRelaxationModels
{
    VV
    {
        relaxationType        KnabVV;
        model                 Knab;
        overwriteDefault      on;
        speciesDependent      on;
        collidingPair         on;
    }
      
    eV
    {
        relaxationType        noeVEnergyTransfer; // not available yet
        model                 BourdonVervisch;
        overwriteDefault      off;
        speciesDependent      off;
    }
}
```

V—V energy transfer presented in Knab _et al._ (1992) is the unique V—V model implemented. [Similarly to the V—T model](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-nonequilibrium/#21-single-vibro-electronic-energy-pool), it can be made collision-pair specific by switching on the <dictkey>collidingPair</dictkey> key. V—V energy exchange can also be disabled by setting the <dictkey>relaxationType</dictkey> to <dictval>noVVEnergyTransfer</dictval>.  

e—V energy transfer is not tested and should not be used.  

In this variant of _hy2Foam_, species are grouped into several vibro-electronic energy pools.
This is done in the <dict>hTCReactions#name</dict> dictionary by using the <dictkey>vibTempAssociativity()</dictkey> list. The elements' order in <dictkey>vibTempAssociativity()</dictkey> is similar to the <dictkey>species()</dictkey> list and the integer value <dictval>0</dictval> is reserved to neutral molecules. For a 5-species air:  

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

    vibTempAssociativity (0 0 0 1 2);
```
A value of <dictval>1</dictval> in 4th position means that the 4th species in the <dictkey>species()</dictkey> list, <dictval>N</dictval>, is grouped into the same vibro-electronic energy pool as the <dictval>1</dictval>st molecule appearing in the list, here <dictval>N2</dictval>. 

<br>

---  
## 3) Mean free path and breakdown parameter

These two quantities are calculated according to the entries specified in the <dict>transportProperties/</dict><subdict>rarefiedParameters</subdict> dictionary.

### 3.1 Mean free path  

There are three <dictkey>mfpModel</dictkey> models available for the computation of the mean free path (mfp): <dictval>maxwellian</dictval>, <dictval>hardSphere</dictval>, and <dictval>variableHardSphere</dictval>.   

You may want to compute the mfp at boundary patches only to speed-up the calculations: indeed, knowledge of the mfp at boundary patches is enough to use the [Smoluchowski temperature jump boundary condition](https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-initial-conditions/#31-trans-rotational-temperature). To this aim, two switches (<dictkey>computeFieldAndBoundaries</dictkey> and <dictkey>computeMfpBoundaries</dictkey>) are implemented and the correct combination is shown below

```c++
rarefiedParameters
{
    computeFieldAndBoundaries      off;
    computeMfpBoundaries           on;
    
    mfpModel                       variableHardSphere;
    writeMfpSpecies                off;
    writeMfpMixture                on;  
}
```
<div style="line-height:50%;">
    <br>
</div>
    
> <b>NB</b>: Always switch <dictkey>computeMfpBoundaries</dictkey> on when using the Smoluchowski temperature jump and the Maxwell velocity slip boundary conditions.

To compute the mfp in the entire domain, <dictkey>computeFieldAndBoundaries</dictkey> must be switched <dictval>on</dictval>.
The species and mixture mfp can be printed using the <dictkey>writeMfpSpecies</dictkey> and <dictkey>writeMfpMixture</dictkey> switches.  

### 3.2 Knudsen number 

#### 3.2.1 Overall Knudsen number

The overall Knudsen number, defined as the ratio of the local mean free path to the characteristic length of the problem (<dictkey>characteristicLength</dictkey>, in meters) can be computed and printed using the following settings

```c++
rarefiedParameters
{
    computeFieldAndBoundaries      on;
 
    characteristicLength           2.0;
    writeKn_overall                on;
}
```

&nbsp;  

#### 3.2.2 Breakdown parameter: gradient-length Knudsen number 

The gradient-length Knudsen number, _**KnGLL**_, serves as the breakdown parameter in _hy2Foam_. It is defined as the maximum of four gradient-length Knudsen numbers (called _components_) based on trans-rotational and vibro-electronic temperatures, density, and velocity. It can be printed using the following setup

```c++
rarefiedParameters
{
    computeFieldAndBoundaries      on;
 
    writeKnGLL                     on;
    writeKnGLL_components          off;   
}
```

<br>

---  
## 4) Chemistry-vibration coupling

There are two chemistry-vibration models implemented but it is strongly recommended to use the Park TTv model.

### 4.1 Park TTv model

#### 4.1.1 General settings

The subdictionary <subdict>chemistryVibrationCoupling</subdict> is added to the <dict>chemistryProperties</dict> dict and the use of the Park TTv model is illustrated below  

```c++
chemistryVibrationCoupling
{
    model ParkTTv;
    
    ParkTTvCoeffs
    {
        exponentTtr         0.7;
        sourceTermModel     preferential;
        
        preferentialModel
        {
            factorType      constant;
            constantFactor  0.3;   
        }
    } 
}
```

<p>Park's temperature, defined as $$T_{tr}^{\color{magenta}{\textrm{exponentTtr}}} * T_{ve}^{1 - \color{magenta}{\textrm{exponentTtr}}}$$ is utilised for dissociation reactions if need be and a value of 0.7 is usually employed for <dictkey>exponentTtr</dictkey>. In this example, the <dictval>preferential</dictval> model is retained (the other <dictkey>sourceTermModel</dictkey> being <dictval>nonPreferential</dictval>).   
</p>

#### 4.1.2 Reactions dictionary

A controlling temperature, <dictkey>controlT</dictkey>, is added to the <dict>hTCReactions#name</dict> dictionary. For example, Park's temperature <dictkey>exponentTtr</dictkey> will be used for forward reaction rate calculations if <dictkey>controlT</dictkey> is defined as follows  

```c++
controlT dissociation;
```

Other accepted values for <dictkey>controlT</dictkey> can be found in <dict>hTCReactionsEarth93</dict>.


### 4.2 Coupled vibration-dissociation-vibration (CVDV) model

The default settings of the <dictval>CVDV</dictval> model are as follows 

```c++
chemistryVibrationCoupling
{
    model CVDV;
    
    CVDVCoeffs
    {
        reciprocalU     3;
        simpleHarmonicOscillatorVibCutOff
        {
            N2   34;
            O2   27;
            NO   28;
            N2+  34;
            O2+  27;
            NO+  28;
        }
    }
}
```

and there should be no need to edit them.
