---
layout: page
title: Guides
subtitle: DSMC Module - Dev release
nav-short: true
---

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()"><i class='fa fa-times'></i></a>
  <header>GUIDE — DSMC</header>
  <a href="https://hystrath.github.io/guides/dev/dsmc/thermophysical/"><b>A. THERMOPHYSICAL</b></a>
  <a href="https://hystrath.github.io/guides/dev/dsmc/thermophysical/#1-species-thermophysical-properties" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Species properties</span></a>
  <a href="https://hystrath.github.io/guides/dev/dsmc/thermophysical/#2-addingremoving-energy-modes"  style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) +/- energy modes</span></a>

  <a href="https://hystrath.github.io/guides/dev/dsmc/collision-dynamics"><b>B. COLLISION DYNAMICS</b></a>
  <a href="https://hystrath.github.io/guides/dev/dsmc/collision-dynamics/#1-collision-partner-selection"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Collision partner selection</span></a>
  <a href="https://hystrath.github.io/guides/dev/dsmc/collision-dynamics/#2-binary-collision"  style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Binary collision</span></a>

  <a href="https://hystrath.github.io/guides/dev/dsmc/chemistry/"><b>C. CHEMISTRY</b></a>
  <a href="https://hystrath.github.io/guides/dev/dsmc/chemistry/#1-chemical-reaction-models"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Chemical reaction models</span></a>
  <a href="https://hystrath.github.io/guides/dev/dsmc/chemistry/#2-dissociation-reaction"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Dissociation reaction</span></a>
  <a href="https://hystrath.github.io/guides/dev/dsmc/chemistry/#3-exchange-reaction"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Exchange reaction</span></a>
  <a href="https://hystrath.github.io/guides/dev/dsmc/chemistry/#4-combined-reactions"  style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) Combined reactions</span></a>

  <a href="https://hystrath.github.io/guides/dev/dsmc/boundary-conditions" style="background-color:#FFCCCC"><b>D. BOUNDARY CONDITIONS</b></a>
  <a href="https://hystrath.github.io/guides/dev/dsmc/boundary-conditions/#1-generalities"  style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Generalities</span></a>
  <a href="https://hystrath.github.io/guides/dev/dsmc/boundary-conditions/#2-inflow--outflow-boundary-conditions"  style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Inflow & Outflow</span></a>
  <a href="https://hystrath.github.io/guides/dev/dsmc/boundary-conditions/#3-wall-boundary-conditions"  style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Wall</span></a>
  <a href="https://hystrath.github.io/guides/dev/dsmc/boundary-conditions/#4-cyclic-boundary-conditions"  style="background-color:#FFE6E6; padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) Cyclic</span></a>
  
  <a href="https://hystrath.github.io/guides/dev/dsmc/coordinate-system/"><b>E. COORDINATE SYSTEM</b></a>
  
  <a href="https://hystrath.github.io/guides/dev/dsmc/initialisation/"><b>F. INITIALISATION</b></a>
  <a href="https://hystrath.github.io/guides/dev/dsmc/initialisation/#1-the-dsmcinitialisedict-dictionary"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) <i>dsmcInitialiseDict</i></span></a>
  <a href="https://hystrath.github.io/guides/dev/dsmc/initialisation/#2-dsmc-parcel-vs-real-particles"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Parcel vs. particles</span></a>
  <a href="https://hystrath.github.io/guides/dev/dsmc/initialisation/#3-creating-the-0-folder"  style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Creating the <i>0/</i> folder</span></a>
  
  <a href="https://hystrath.github.io/guides/dev/dsmc/sampling/"><b>G. SAMPLING</b></a>
  <a href="https://hystrath.github.io/guides/dev/dsmc/sampling/#1-the-fieldpropertiesdict-dictionary"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) <i>fieldPropertiesDict</i></span></a>
  <a href="https://hystrath.github.io/guides/dev/dsmc/sampling/#2-steady-state-simulations"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Steady-state simulations</span></a>
  <a href="https://hystrath.github.io/guides/dev/dsmc/sampling/#3-transient-simulations" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Transient simulations</span></a>
  <a href="https://hystrath.github.io/guides/dev/dsmc/sampling/#4-mean-free-path-computation"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) MFP computation</span></a>
  <a href="https://hystrath.github.io/guides/dev/dsmc/sampling/#5-resume-sampling" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 5) Resume sampling</span></a>
  
  <a href="https://hystrath.github.io/guides/dev/dsmc/load-balancing/"><b>H. LOAD BALANCING</b></a>
  <a href="https://hystrath.github.io/guides/dev/dsmc/toc/#i-adaptive-mesh-refinement"><b>I. ADAPTIVE MESH REFINEMENT</b></a>
  <a href="https://hystrath.github.io/guides/dev/dsmc/toc/#j-monitoring--post-processing"><b>J. MONITORING & POST-PROCESSING</b></a>
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
        boundaryModel   dsmcFreeStreamInflowPatch;
        
        generalBoundaryProperties
        {
            patchName   inlet;
        }

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

In <subdict>dsmcFreeStreamInflowPatchProperties</subdict>, the same species defined in [A.1 Species thermophysical properties](https://hystrath.github.io/guides/dev/dsmc/thermophysical/#1-species-thermophysical-properties)) should be recalled in the <dictkey>typeIds()</dictkey> list. As is customary, the inflow velocity, modal temperatures and number densities must be prescribed as well.


### 2.2 Vacuum outlet

The vacuum outlet boundary condition implementation is shown below. The boundary model is called <dictval>dsmcDeletionPatch</dictval> and any particle hitting this patch (whether it is an inflow or an outflow in this example) is deleted.

```c++
dsmcPatchBoundaries
(
    boundary
    {
        boundaryModel   dsmcDeletionPatch;
        
        patchBoundaryProperties
        {
            patchName   inlet;
        }

        dsmcDeletionPatchProperties
        {
            allSpecies  yes;
        }
    }

    boundary
    {
        boundaryModel   dsmcDeletionPatch;
        
        patchBoundaryProperties
        {
            patchName   outlet;
        }

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
        boundaryModel   dsmcSpecularWallPatch;
        
        patchBoundaryProperties
        {
            patchName   plate;
        }
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
        boundaryModel   dsmcDiffuseWallPatch;
        
        patchBoundaryProperties
        {
            patchName   cylinder;
        }

        dsmcDiffuseWallPatchProperties
        {
            velocity      (0 0 0);
            temperature      1000;
        }
    }
);
```

&nbsp;

### 3.3 Diffuse-Specular wall

The boundary model for mixed diffuse-specular wall interactions is <dictval>dsmcDiffuseSpecularWallPatch</dictval>. The wall velocity and temperature are given in <subdict>dsmcDiffuseWallPatchProperties</subdict> (see [3.2](https://hystrath.github.io/guides/dev/dsmc/boundary-conditions/#32-diffuse-wall)), while the fraction of wall interactions that are diffuse, <dictkey>diffuseFraction</dictkey>, is given in <subdict>dsmcDiffuseSpecularWallPatchProperties</subdict>. For each particle-wall interaction, a random number is drawn and compared to <dictkey>diffuseFraction</dictkey> to decide on the type of reflection to perform.

```c++
dsmcPatchBoundaries
(
    boundary
    {
        boundaryModel   dsmcDiffuseSpecularWallPatch;
        
        patchBoundaryProperties
        {
            patchName   cone;
        }

        dsmcDiffuseWallPatchProperties
        {
            velocity      (0 0 0);
            temperature      1000;
        }
        
        dsmcSpecularWallPatchProperties {}
        
        dsmcDiffuseSpecularWallPatchProperties
        {
            diffuseFraction   0.5;
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
        boundaryModel   dsmcReflectiveParticleMembranePatch;
        
        cyclicBoundaryProperties
        {
            patchName   leftPatch;
        }

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
        boundaryModel   dsmcReflectiveParticleMembranePatch;
        
        cyclicBoundaryProperties
        {
            patchName   rightPatch;
        }

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
