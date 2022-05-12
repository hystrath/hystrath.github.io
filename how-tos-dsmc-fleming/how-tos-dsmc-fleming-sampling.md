---
layout: page
title: How-tos
subtitle: DSMC Module - Fleming release
nav-short: true
---

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()"><i class='fa fa-times'></i></a>
  <header>HOW-TOS — DSMC</header>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-thermophysical/"><b>A. THERMOPHYSICAL</b></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-thermophysical/#1-species-thermophysical-properties" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Species properties</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-thermophysical/#2-addingremoving-energy-modes"  style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) +/- energy modes</span></a>

  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-collision-dynamics"><b>B. COLLISION DYNAMICS</b></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-collision-dynamics/#1-collision-partner-selection"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Collision partner selection</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-collision-dynamics/#2-binary-collision"  style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Binary collision</span></a>

  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-chemistry/"><b>C. CHEMISTRY</b></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-chemistry/#1-chemical-reaction-models"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Chemical reaction models</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-chemistry/#2-dissociation-reaction"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Dissociation reaction</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-chemistry/#3-exchange-reaction"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Exchange reaction</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-chemistry/#4-combined-reactions"  style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) Combined reactions</span></a>

  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-boundary-conditions"><b>D. BOUNDARY CONDITIONS</b></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-boundary-conditions/#1-generalities"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Generalities</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-boundary-conditions/#2-inflow--outflow-boundary-conditions"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Inflow & Outflow</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-boundary-conditions/#3-wall-boundary-conditions"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Wall</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-boundary-conditions/#4-cyclic-boundary-conditions"  style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) Cyclic</span></a>
  
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-coordinate-system/"><b>E. COORDINATE SYSTEM</b></a>
  
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-initialisation/"><b>F. INITIALISATION</b></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-initialisation/#1-the-dsmcinitialisedict-dictionary"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) <i>dsmcInitialiseDict</i></span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-initialisation/#2-dsmc-parcel-vs-real-particles"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Parcel vs. particles</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-initialisation/#3-creating-the-0-folder"  style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Creating the <i>0/</i> folder</span></a>
  
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-sampling/" style="background-color:#FFCCCC"><b>G. SAMPLING</b></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-sampling/#1-the-fieldpropertiesdict-dictionary"  style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) <i>fieldPropertiesDict</i></span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-sampling/#2-steady-state-simulations"  style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Steady-state simulations</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-sampling/#3-transient-simulations" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Transient simulations</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-sampling/#4-mean-free-path-computation"  style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) MFP computation</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-sampling/#5-resume-sampling" style="background-color:#FFE6E6; padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 5) Resume sampling</span></a>
  
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-load-balancing/"><b>H. LOAD BALANCING</b></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming/#i-adaptive-mesh-refinement"><b>I. ADAPTIVE MESH REFINEMENT</b></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming/#j-monitoring--post-processing"><b>J. MONITORING & POST-PROCESSING</b></a>
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

&nbsp;   

# Sampling

---
## 1) The _fieldPropertiesDict_ dictionary

This dictionary located in the <dirname>system</dirname> folder is responsible for computing macroscopic quantities from microscopic particle information and for sampling species and mixture properties to obtain a statistical average. It is composed a list called `dsmcFields()` inside which a <dict>field</dict> dictionary can be repeated as many times as desired. The single field model available is <dictval>dsmcVolFields</dictval> to average volume and boundary fields in the entire domain. Other models are deprecated at present (WIP).

```c++
dsmcFields
(
    field
    {
        fieldModel          	dsmcVolFields;

        [...]
    }

    field
    {
        fieldModel          	dsmcVolFields;
        
        [...]
    }
     
);
```

The `dsmcFields()` list should be left empty when there is no need to reconstruct macroscopic fields.


For the N2 species, the macroscopic fields printed by default are:
- `dsmcN_N2`: instantaneous number of DSMC parcels
- `dsmcNMean_N2`: sampled number of DSMC parcels
- `rhoN_N2`: number density
- `rhoM_N2`: density
- `U_N2`: velocity vector
- `Ma_N2`: mach number
- `p_N2`: pressure (or partial pressure for a mixture)
- `Ttra_N2`: translational temperature
- `Trot_N2`: rotational temperature
- `Tvib_N2`: vibrational temperature
- `Telec_N2`: electronic temperature
- `Tov_N2`: overall temperature
- `fD_N2`: force density
- `wallShearStress_N2`: wall shear stress
- `wallHeatFlux_N2`: wall heat flux

The fields `cellLevel` and `dsmcSigmaTcRMax` have already been introduced in [F.2.2 Initial volume fields](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-initialisation/#22-initial-volume-fields).

<br>

---
## 2) Steady-state simulations

In the example below, macroscopic quantities are computed for the N2 species (see the <subdict>dsmcVolFieldsProperties</subdict>/<dictkey>typeIds()</dictkey> list) and are given the suffix `_N2` (<subdict>dsmcVolFieldsProperties</subdict>/<dictkey>fieldName</dictkey>) in the results folders. The same operation is repeated for the mixture `(N2 O2 NO N O)`, providing that these species are the ones defined in [A.1 Species thermophysical properties](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-thermophysical/#1-species-thermophysical-properties). The suffix is set to be `_mixture`.

```c++
dsmcFields
(
    field
    {
        fieldModel          	dsmcVolFields;

        timeProperties
        {
            timeOption               write;
            resetAtOutput               on;
            resetAtOutputUntilTime    1e-3;
        }

        dsmcVolFieldsProperties
        {
            fieldName           N2;
            typeIds             (N2);
        }
    }

    field
    {
        fieldModel          	dsmcVolFields;

        timeProperties
        {
            timeOption               write;
            resetAtOutput               on;
            resetAtOutputUntilTime    1e-3;
        }

        dsmcVolFieldsProperties
        {
            fieldName           mixture;
            typeIds             (N2 O2 NO N O);
        }
    }
     
);
```

There are two important parameters in <dict>field</dict>/<subdict>timeProperties</subdict> to control sampling: <dictkey>resetAtOutput</dictkey> and <dictkey>resetAtOutputUntilTime</dictkey>. The former is a switch that indicates whether or not cumulative fields recording microscopic information are reset at the end of each iteration. If it is <dictval>on</dictval>, the instantaneous solution is printed. <dictkey>resetAtOutputUntilTime</dictkey> controls the time when sampling starts, in seconds, and for times greater than this value cumulative fields will not be reset to 0.

<br>

---
## 3) Transient simulations
 
&nbsp; <dictkey>resetAtOutput</dictkey> must be <dictval>on</dictval> for all <dict>field</dict> dictionaries and the entry <dictkey>resetAtOutputUntilTime</dictkey> should either be deleted or set to a value greater than the end simulation time.

<br>

---
## 4) Mean free path computation
 
To compute the mean free path and related fields, the <dictkey>measureMeanFreePath</dictkey> entry must be added to <dict>field</dict>/<subdict>dsmcVolFieldsProperties</subdict> and be swiched <dictval>on</dictval> for all <dict>field</dict> dictionaries. Here is the list of additional fields that are printed in the results folders when this switch is activated:

- mean free path: `mfp`
- mean free path to cell size ratio: `mfpToDx`
- mean free path to mean collision separation ratio: `SOFP`
- mean collision time: `mct`
- mean collision time to time-step ratio: `mctToDt`

<br>

---
## 5) Resume sampling
 
Sampling can be resumed even when the simulation has stopped, providing that the <dictkey>averagingAcrossManyRuns</dictkey> switch had been defined in <subdict>dsmcVolFieldsProperties</subdict> and set to <dictval>true</dictval> before launching the first run. Here are the steps to follow at the end of the first run:
- `reconstrucPar -latestTime`
- delete everything but the <dirname>time/uniform/</dirname> sub-folder in the processors directories and store them in <dirname>backup-processors</dirname>
- prior to resuming the simulation: `cp -r backup-processors/processor* . && decomposePar -force -latestTime`

<b>NB</b>: the same number of CPUs must be used throughout the entire simulation as the `resumeSampling_#fieldName` files located in <dirname>time/uniform/</dirname> cannot be reconstructed.

For more information, please read Issue [#73](https://github.com/vincentcasseau/hyStrath/issues/73).
