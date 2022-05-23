---
layout: page
title: How-tos
subtitle: CFD Module - Fleming release
nav-short: true
---

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()"><i class='fa fa-times'></i></a>
  <header>HOW-TOS — CFD</header>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-thermophysical/" style="background-color:#FFCCCC"><b>A. THERMOPHYSICAL</b></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-thermophysical/#1-species-thermophysical-properties" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Species thermo props</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-thermophysical/#2-addingremoving-energy-modes" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) +/- energy modes</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-thermophysical/#3-choosing-a-thermodem-dictionary" style="background-color:#FFE6E6; padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) <i>thermoDEM</i> dictionary</span></a>

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

# Thermophysical modelling

---  
## 1) Species thermophysical properties

The species thermophysical properties are given in the <dict>thermoDEM</dict> dictionary. Each species presents three subdictionaries: <subdict>specie</subdict>, <subdict>thermodynamics</subdict>, and <subdict>transport</subdict>.
For the nitrogen molecule, it is defined as follows
    
```c++
N2
{
    specie
    {
        molWeight       28.0134;
        particleType    2;
        charge          0;
        diameter        4.17e-10;
        dissocEnergy    3.36e7;
        iHat            2.89e7;
        omega           0.74;
        eta_s           1.2;
        noVibTemp       1;
        noElecLevels    15; 
    }
    thermodynamics
    {
        decoupledCvCoeffs    ( 1.5 1 1 0 0 0 0 );
        vibrationalList      ( 1  3371 );
        electronicList       (  
                                1  0
                                3  7.223157e4
                                6  8.577863e4
                                6  8.605027e4
                                3  9.535119e4
                                1  9.805636e4
                                2  9.968268e4
                                2  1.048976e5
                                5  1.116490e5
                                1  1.225836e5
                                6  1.248857e5
                                6  1.282476e5
                                10 1.338061e5
                                6  1.404296e5
                                6  1.504959e5
                             );               
    }
    transport
    {}
}
```

The entries of the <subdict>transport</subdict> subdictionary are omitted as they will be discussed in <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-transport/"><b>B. TRANSPORT</b></a>.
The Table below lists the meaning of the different keys present in the <subdict>specie</subdict> subdictionary. 

<table>
  <tr>
    <td align="center" colspan="3"><b><subdict>specie</subdict> subdictionary</b></td>
  </tr>
  <tr>
    <td align="center"><b>Key</b></td>
    <td align="center"><b>Units</b></td>
    <td align="center"><b>Meaning</b></td>
  </tr>
  <tr>
    <td align="center"><dictkey>molWeight</dictkey></td>
    <td align="center"> g/mol </td>
    <td align="center">molecular weight</td>
  </tr>
  <tr>
    <td align="center"><dictkey>particleType</dictkey></td>
    <td align="center"> - </td>  
    <td align="center">type of particle (<dictval>0</dictval>: electron, <dictval>1</dictval>: neutral atom, <dictval>2</dictval>: neutral molecule, <dictval>3</dictval>: positively-charged particle) </td>
  </tr>
  <tr>
    <td align="center"><dictkey>charge</dictkey></td>
    <td align="center"> - </td>  
    <td align="center">charge of the particle (<dictval>-1</dictval>: electron, <dictval>0</dictval>: neutral atom and molecule, <dictval>+1</dictval>: charged atom and molecule) </td>
  </tr>
  <tr>
    <td align="center"><dictkey>diameter</dictkey></td>
    <td align="center"> m </td>  
    <td align="center">diameter of the particle </td>
  </tr>
  <tr>
    <td align="center"><dictkey>omega</dictkey></td>
    <td align="center"> - </td>  
    <td align="center">temperature exponent of viscosity, see also: <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-transport/#13-other-transport-models">B. Transport</a></td>
  </tr>
  <tr>
    <td align="center"><dictkey>eta_s</dictkey></td>
    <td align="center"> - </td>  
    <td align="center">factor that enters in the calculation of the <a href="https://github.com/vincentcasseau/hyStrath/commit/f036d74297d3f91fcbeb05fa531a1c07ba71bde1">vibrational thermal conductivity</a> (this key is optional and is equal to <dictval>1.2</dictval> by default) </td>
  </tr>
  <tr>
    <td align="center"><dictkey>noVibTemp</dictkey></td>
    <td align="center"> - </td>  
    <td align="center"> number of vibrational energy modes </td>
  </tr>
  <tr>
    <td align="center"><dictkey>noElecLevels</dictkey></td>
    <td align="center"> - </td>  
    <td align="center"> number of electronic energy levels </td>
  </tr>
  <tr>
    <td align="center"><dictkey>dissocEnergy</dictkey></td>
    <td align="center"> J/kg </td>  
    <td align="center"> species dissociation potential, used in the <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-nonequilibrium/#411-general-settings">preferential model</a> </td>
  </tr>
  <tr>
    <td align="center"><dictkey>iHat</dictkey></td>
    <td align="center"> J/kg </td>  
    <td align="center"> first ionization energy of the species, used in the free-electron impact ionization vibro-electronic source term</td>
  </tr>
</table>

In the <subdict>thermodynamics</subdict> subdictionary, the first entry is a list of coefficients called <dictkey>decoupledCvCoeffs()</dictkey>. The heat capacity at constant volume, _Cv_, is decomposed into the contributions of the different energy modes that are translational (element \#1), rotational (element \#2), vibrational (element \#3), electronic (element \#4), and electron (element \#5). For a planar molecule,   
<p>
$$Cv_t = 1.5*R_m$$
</p>
<p>and</p>
<p>
$$Cv_r = 1.0*R_m$$
</p>
 
<p>where `R_m` is the specific gas constant of molecule `m`. Thus, the first two elements in the <dictkey>decoupledCvCoeffs()</dictkey> list are the coefficients by which `R_m` should be multiplied.</p>

<p>For the vibrational and electronic modes, the expressions of `Cv_v` and `Cv_{el}` are a function of the values provided in the <dictkey>vibrationalList()</dictkey> and <dictkey>electronicList()</dictkey> lists. Hence, elements \#3 and \#4 can be regarded as switches (see <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-thermophysical/#21-disablingenabling-the-vibrational-mode-of-a-molecule">§2.1</a> and <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming-thermophysical/#22-disablingenabling-the-electronic-mode-of-a-particle">§2.2</a>). The elements in these two lists are grouped by pairs with the first column being the degeneracy and the second column being the characteristic vibrational/electronic temperature, in Kelvins.</p>   

The 6th element of the <dictkey>decoupledCvCoeffs()</dictkey> list is the ratio of the species chemical enthalpy taken at 298 K (in J/mol) to the universal gas constant, while the 7th element is currently not used.  

&nbsp;

---  
## 2) Adding/removing energy modes

### 2.1 Disabling/enabling the vibrational mode of a molecule 

In the <dict>thermoDEM/</dict><subdict>#speciesName/thermodynamics</subdict> dictionary, edit the 3rd element of the <dictkey>decoupledCvCoeffs</dictkey> list to either be <dictval>0</dictval> (disabled) or <dictval>1</dictval> (enabled).  

In the following example, the vibrational energy mode of the N2 molecule is enabled  

```c++
        decoupledCvCoeffs    ( 1.5 1 1 0 0 0 0 );
```

&nbsp;

### 2.2 Disabling/enabling the electronic mode of a particle  

In the <dict>thermoDEM/</dict><subdict>#speciesName/thermodynamics</subdict> dictionary, edit the 4th element of the <dictkey>decoupledCvCoeffs()</dictkey> list to either be <dictval>0</dictval> (disabled) or <dictval>1</dictval> (enabled).  

In the following example, the electronic energy mode of the N atom is enabled  

```c++
        decoupledCvCoeffs    ( 1.5 0 0 1 0 56852 0 );
```

&nbsp;

---  
## 3) Choosing a thermoDEM dictionary

Three <dict>thermoDEM</dict> dictionaries are provided in the [generic *hy2Foam* test case](https://github.com/vincentcasseau/hyStrath/tree/master/run/hyStrath/hy2Foam/genericCase/constant)  
  + to include the rotational energy mode only: <dict>thermoDEM_TR</dict>;
  + to include the rotational and vibrational internal energy modes: <dict>thermoDEM_TRV</dict>;
  + to include all internal energy modes: <dict>thermoDEM_TRVE</dict>.  

<b>NB</b>: All species can be left uncommented at all times.
