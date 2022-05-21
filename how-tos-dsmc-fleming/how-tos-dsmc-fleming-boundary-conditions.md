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

  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-boundary-conditions" style="background-color:#FFCCCC"><b>D. BOUNDARY CONDITIONS</b></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-boundary-conditions/#1-generalities"  style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Generalities</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-boundary-conditions/#2-inflow--outflow-boundary-conditions"  style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Inflow & Outflow</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-boundary-conditions/#3-wall-boundary-conditions"  style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Wall</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-boundary-conditions/#4-cyclic-boundary-conditions"  style="background-color:#FFE6E6; padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) Cyclic</span></a>
  
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-coordinate-system/"><b>E. COORDINATE SYSTEM</b></a>
  
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-initialisation/"><b>F. INITIALISATION</b></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-initialisation/#1-the-dsmcinitialisedict-dictionary"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) <i>dsmcInitialiseDict</i></span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-initialisation/#2-dsmc-parcel-vs-real-particles"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Parcel vs. particles</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-initialisation/#3-creating-the-0-folder"  style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Creating the <i>0/</i> folder</span></a>
  
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-sampling/"><b>G. SAMPLING</b></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-sampling/#1-the-fieldpropertiesdict-dictionary"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) <i>fieldPropertiesDict</i></span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-sampling/#2-steady-state-simulations"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Steady-state simulations</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-sampling/#3-transient-simulations" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Transient simulations</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-sampling/#4-mean-free-path-computation"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) MFP computation</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-sampling/#5-resume-sampling" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 5) Resume sampling</span></a>
  
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-load-balancing/"><b>H. LOAD BALANCING</b></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming/#i-adaptive-mesh-refinement"><b>I. ADAPTIVE MESH REFINEMENT</b></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming/#j-monitoring--post-processing"><b>J. MONITORING & POST-PROCESSING</b></a>
</div>

<span style="position: fixed;font-size:30px;cursor:pointer; margin:0px; top:60px;left:30px;" onclick="reopenNav()">&#9776;</span>

<script>
function openNav() {
  document.getElementById("mySidenav").style.width = "225px";
  document.getElementById("mySidenav").style.transition = "0s";
  document.getElementById('mySidenav').scrollTop = "700";
}

function closeNav() {
  document.getElementById("mySidenav").style.width = "0px";
}

function reopenNav() {
  document.getElementById("mySidenav").style.width = "225px";
  document.getElementById("mySidenav").style.transition = "0.5s";
  document.getElementById('mySidenav').scrollTop = "700";
}

openNav()

</script>

&nbsp; 

# Boundary conditions

---
## 1) Generalities

Boundary conditions are defined in <dirname>system/</dirname><dict>boundariesDict</dict> and divided into three groups as shown below 

```c++
dsmcGeneralBoundaries
(
    [...]
);

dsmcPatchBoundaries
(
    [...]
);

dsmcCyclicBoundaries
(
    [...]
);
```

<br>
  
--- 
## 2) Inflow & Outflow boundary conditions

Inflow & Outflow boundary conditions are set in the `dsmcGeneralBoundaries()` list.

### 2.1 Supersonic inflow

The supersonic inflow model is named <dictval>dsmcFreeStreamInflowPatch</dictval> and can be setup as follows

```c++
dsmcGeneralBoundaries
(
    boundary
    {
        generalBoundaryProperties
        {
            patchName   inlet;
        }

        boundaryModel   dsmcFreeStreamInflowPatch;

        dsmcFreeStreamInflowPatchProperties
        {
            typeIds                       (N2 O2);
            velocity                 (6053.4 0 0);
            translationalTemperature       217.63;
            rotationalTemperature          217.63;
            vibrationalTemperature         217.63;
            electronicTemperature               0;
            numberDensities
            {
                N2      2.318e18;
                O2      6.161e17;
            };
        }
    }
);
```

In <subdict>dsmcFreeStreamInflowPatchProperties</subdict>, the same species defined in [A.1 Species thermophysical properties](https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming-thermophysical/#1-species-thermophysical-properties)) should be recalled in the <dictkey>typeIds()</dictkey> list. As is customary, the inflow velocity, modal temperatures and number densities must be prescribed as well.


### 2.2 Vacuum outlet

The vacuum outlet boundary condition implementation is shown below. The boundary model is called <dictval>dsmcDeletionPatch</dictval> and any particle hitting this patch (whether it is an inflow or an outflow in this example) is deleted.

```c++
dsmcPatchBoundaries
(
    boundary
    {
        patchBoundaryProperties
        {
            patchName   inlet;
        }

        boundaryModel   dsmcDeletionPatch;

        dsmcDeletionPatchProperties
        {
            allSpecies  yes;
        }
    }

    boundary
    {
        patchBoundaryProperties
        {
            patchName   outlet;
        }

        boundaryModel   dsmcDeletionPatch;

        dsmcDeletionPatchProperties
        {
            allSpecies  yes;
        }
    }
);
```

<br>
  
--- 
## 3) Wall boundary conditions

Wall boundary conditions are set in the `dsmcPatchBoundaries()` list.

### 3.1 Specular wall

The boundary model for specular walls is <dictval>dsmcSpecularWallPatch</dictval>. There are no other parameters to tune.

```c++
dsmcPatchBoundaries
(
    boundary
    {
        patchBoundaryProperties
        {
            patchName   plate;
        }

        boundaryModel   dsmcSpecularWallPatch;
    }
);
```

&nbsp;

### 3.2 Diffuse wall

The boundary model for diffuse walls is <dictval>dsmcDiffuseWallPatch</dictval>. The wall velocity and temperature are given in <subdict>dsmcDiffuseWallPatchProperties</subdict>.

```c++
dsmcPatchBoundaries
(
    boundary
    {
        patchBoundaryProperties
        {
            patchName   cylinder;
        }

        boundaryModel   dsmcDiffuseWallPatch;

        dsmcDiffuseWallPatchProperties
        {
            velocity      (0 0 0);
            temperature      1000;
        }
    }
);
```

<br>
  
--- 
## 4) Cyclic boundary conditions

Cyclic boundary conditions are set in the `dsmcCyclicBoundaries()` list.

They are defined using the <dictval>dsmcReflectiveParticleMembranePatch</dictval> boundary model, and that for both patches.
An example is given hereafter where all Argon DSMC parcels hitting the membrane are mapped onto the corresponding cyclic patch. The species-dependent reflection probabilities can be controlled using <dictkey>reflectionProbabilities </dictkey> in the boundary model's properties dictionary, and a value of <dictval>1</dictval> would correspond to a specular wall.

```c++
dsmcCyclicBoundaries
(
    boundary
    {
        cyclicBoundaryProperties
        {
            patchName   leftPatch;
        }

        boundaryModel   dsmcReflectiveParticleMembranePatch;

        dsmcReflectiveParticleMembranePatchProperties
        {
            typeIds (Ar);

            reflectionProbabilities
            {
                Ar   0;
            }
        }
     }

    boundary
    {
        cyclicBoundaryProperties
        {
            patchName   rightPatch;
        }

        boundaryModel   dsmcReflectiveParticleMembranePatch;

        dsmcReflectiveParticleMembranePatchProperties
        {
            typeIds (Ar);

            reflectionProbabilities
            {
                Ar   0;
            }
        }
    }
);
```
