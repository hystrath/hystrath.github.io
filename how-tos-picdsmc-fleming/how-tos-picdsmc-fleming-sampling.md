---
layout: page
title: How-tos
subtitle: Hybrid Modules - Fleming release
nav-short: true
---

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()"><i class='fa fa-times'></i></a>
  <header>HOW-TOS — HYBD</header>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-thermophysical/"><b>A. THERMOPHYSICAL</b></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-thermophysical/#1-species-thermophysical-properties" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Species properties</span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-thermophysical/#2-addingremoving-energy-modes"  style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) +/- energy modes</span></a>

  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-collision-dynamics"><b>B. COLLISION DYNAMICS</b></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-collision-dynamics/#1-binary-collision-model"  style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Binary collision model</span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-collision-dynamics/#2-collision-partner-selection"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Collision partner selection</span></a>

  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-boundary-conditions"><b>C. BOUNDARY CONDITIONS</b></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-boundary-conditions/#1-generalities"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Generalities</span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-boundary-conditions/#2-inflow--outflow-boundary-conditions"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Inflow & Outflow</span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-boundary-conditions/#3-wall-boundary-conditions"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Wall</span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-boundary-conditions/#4-cyclic-boundary-conditions"  style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) Cyclic</span></a>
  
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-initialisation/"><b>D. INITIALISATION</b></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-initialisation/#1-the-pdinitialisedict-dictionary"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) <i>pdInitialiseDict</i></span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-initialisation/#2-parcel-vs-real-particles"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Parcel vs. particles</span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-initialisation/#3-creating-the-0-folder"  style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Creating the <i>0/</i> folder</span></a>
  
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-sampling/" style="background-color:#FFCCCC"><b>E. SAMPLING</b></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-sampling/#1-the-fieldpropertiesdict-dictionary"  style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) <i>fieldPropertiesDict</i></span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-sampling/#2-steady-state-simulations"  style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Steady-state simulations</span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-sampling/#3-transient-simulations" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Transient simulations</span></a>
  
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming/#f-monitoring--post-processing"><b>F. MONITORING & POST-PROCESSING</b></a>
</div>

<span style="position: fixed;font-size:30px;cursor:pointer; margin:0px; top:60px;left:30px;" onclick="reopenNav()">&#9776;</span>

<script>
function openNav() {
  document.getElementById("mySidenav").style.width = "225px";
  document.getElementById("mySidenav").style.transition = "0s";
  document.getElementById('mySidenav').scrollTop = "480";
}

function closeNav() {
  document.getElementById("mySidenav").style.width = "0px";
}

function reopenNav() {
  document.getElementById("mySidenav").style.width = "225px";
  document.getElementById("mySidenav").style.transition = "0.5s";
  document.getElementById('mySidenav').scrollTop = "480";
}

openNav()
</script>

&nbsp;   

# Sampling

---
## 1) The _fieldPropertiesDict_ dictionary

This dictionary located in the <dirname>system</dirname> folder is responsible for computing macroscopic quantities from microscopic particle information and for sampling species and mixture properties to obtain a statistical average. It is composed a list called `pdFields()` inside which a <dict>field</dict> dictionary can be repeated as many times as desired. The single field model available is <dictval>pdVolFields</dictval> to average volume and boundary fields in the entire domain. Other models are deprecated at present (WIP).

```c++
pdFields
(
    field
    {
        fieldModel          	pdVolFields;

        [...]
    }

    field
    {
        fieldModel          	pdVolFields;
        
        [...]
    }
     
);
```

The `pdFields()` list should be left empty when there is no need to reconstruct macroscopic fields.


For the O+ species, the macroscopic fields printed by default are:
- `pdRhoN_O+`: instantaneous number of parcels
- `pdRhoNMean_O+`: sampled number of parcels
- `rhoN_O+`: number density
- `rhoM_O+`: density
- `U_O+`: velocity vector
- `Ma_O+`: mach number
- `p_O+`: pressure (or partial pressure for a mixture)
- `translationalT_O+`: translational temperature
- `rotationalT_O+`: rotational temperature
- `vibrational_O+`: vibrational temperature
- `overallT_O+`: overall temperature
- `fD_O+`: force density
- `wallShearStress_O+`: wall shear stress
- `wallHeatFlux_O+`: wall heat flux

The field `pdSigmaTcRMax` has already been introduced in [D.2.2 Initial volume fields](https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-initialisation/#22-initial-volume-fields).

<br>

---
## 2) Steady-state simulations

In the example below, macroscopic quantities are computed for the O+ and O species (see the <subdict>pdVolFieldsProperties</subdict>/<dictkey>typeIds()</dictkey> list) and are given the suffix `_O+` and `_O` (<subdict>pdVolFieldsProperties</subdict>/<dictkey>fieldName</dictkey>) in the results folders. The same operation is repeated for the mixture `(O+ O)`, providing that these species are the ones defined in [A.1 Species thermophysical properties](https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-thermophysical/#1-species-thermophysical-properties). The suffix is set to be `_mixture`.

```c++
pdFields
(
    field
    {
        fieldModel          	pdVolFields;

        timeProperties
        {
            timeOption               write;
            resetAtOutput               on;
        }

        pdVolFieldsProperties
        {
            fieldName           O+;
            typeIds             (O+);
        }
    }
    
    field
    {
        fieldModel          	pdVolFields;

        timeProperties
        {
            timeOption               write;
            resetAtOutput               on;
        }

        pdVolFieldsProperties
        {
            fieldName           O;
            typeIds             (O);
        }
    }

    field
    {
        fieldModel          	pdVolFields;

        timeProperties
        {
            timeOption               write;
            resetAtOutput               on;
        }

        pdVolFieldsProperties
        {
            fieldName           mixture;
            typeIds             (O+ O);
        }
    }
     
);
```

<dictkey>resetAtOutput</dictkey> is the key parameter controlling sampling: it is a switch that indicates whether or not cumulative fields recording microscopic information are reset at the end of each iteration. If it is <dictval>on</dictval>, the instantaneous solution is printed.

<br>

---
## 3) Transient simulations
 
&nbsp; <dictkey>resetAtOutput</dictkey> must be <dictval>on</dictval> for all <dict>field</dict> dictionaries at all times.
