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
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-collision-dynamics/#1-collision-partner-selection"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Collision partner selection</span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-collision-dynamics/#2-binary-collision"  style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Binary collision</span></a>

  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-chemistry/"><b>C. CHEMISTRY</b></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-chemistry/#1-chemical-reaction-models"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Chemical reaction models</span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-chemistry/#2-dissociation-reaction"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Dissociation reaction</span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-chemistry/#3-exchange-reaction"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Exchange reaction</span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-chemistry/#4-combined-reactions"  style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) Combined reactions</span></a>

  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-boundary-conditions" style="background-color:#FFCCCC"><b>D. BOUNDARY CONDITIONS</b></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-boundary-conditions/#1-generalities"  style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Generalities</span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-boundary-conditions/#2-inflow--outflow-boundary-conditions"  style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Inflow & Outflow</span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-boundary-conditions/#3-wall-boundary-conditions"  style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Wall</span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-boundary-conditions/#4-cyclic-boundary-conditions"  style="background-color:#FFE6E6; padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) Cyclic</span></a>
  
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-coordinate-system/"><b>E. COORDINATE SYSTEM</b></a>
  
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-initialisation/"><b>F. INITIALISATION</b></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-initialisation/#1-the-dsmcinitialisedict-dictionary"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) <i>dsmcInitialiseDict</i></span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-initialisation/#2-dsmc-parcel-vs-real-particles"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Parcel vs. particles</span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-initialisation/#3-creating-the-0-folder"  style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Creating the <i>0/</i> folder</span></a>
  
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-sampling/"><b>G. SAMPLING</b></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-sampling/#1-the-fieldpropertiesdict-dictionary"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) <i>fieldPropertiesDict</i></span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-sampling/#2-steady-state-simulations"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Steady-state simulations</span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-sampling/#3-transient-simulations" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Transient simulations</span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-sampling/#4-mean-free-path-computation"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) MFP computation</span></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-sampling/#5-resume-sampling" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 5) Resume sampling</span></a>
  
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-load-balancing/"><b>H. LOAD BALANCING</b></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming/#i-adaptive-mesh-refinement"><b>I. ADAPTIVE MESH REFINEMENT</b></a>
  <a href="https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming/#j-monitoring--post-processing"><b>J. MONITORING & POST-PROCESSING</b></a>
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
pdGeneralBoundaries
(
    [...]
);

pdPatchBoundaries
(
    [...]
);

pdCyclicBoundaries
(
    [...]
);
```

<br>
  
--- 
## 2) Inflow & Outflow boundary conditions

Inflow & Outflow boundary conditions are set in the `pdGeneralBoundaries()` list.

### 2.1 Supersonic inflow

The supersonic inflow model is named <dictval>pdFreeStreamInflowPatch</dictval> and can be setup as follows

```c++
pdGeneralBoundaries
(
    boundary
    {
        boundaryModel   pdFreeStreamInflowPatch;
        
        generalBoundaryProperties
        {
            patchName   inlet;
        }

        pdFreeStreamInflowPatchProperties
        {
            typeIds                        (O+ O);
            velocity                   (7768 0 0);
            translationalTemperature         2000;
            rotationalTemperature               0;
            vibrationalTemperature              0;
            numberDensities
            {
                O+      2.318e12;
                O              0;
            };
        }
    }
);
```

In <subdict>pdFreeStreamInflowPatchProperties</subdict>, the same species defined in [A.1 Species thermophysical properties](https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-thermophysical/#1-species-thermophysical-properties)) should be recalled in the <dictkey>typeIds()</dictkey> list. As is customary, the inflow velocity, modal temperatures and number densities must be prescribed as well.


### 2.2 Vacuum outlet

The vacuum outlet boundary condition implementation is shown below. The boundary model is called <dictval>pdDeletionPatch</dictval> and any particle hitting this patch (whether it is an inflow or an outflow in this example) is deleted.

```c++
pdPatchBoundaries
(
    boundary
    {
        boundaryModel   pdDeletionPatch;
        
        patchBoundaryProperties
        {
            patchName   inlet;
        }

        pdDeletionPatchProperties
        {
            allSpecies  yes;
        }
    }

    boundary
    {
        boundaryModel   pdDeletionPatch;
        
        patchBoundaryProperties
        {
            patchName   outlet;
        }

        pdDeletionPatchProperties
        {
            allSpecies  yes;
        }
    }
);
```

<br>
  
--- 
## 3) Wall boundary conditions

Wall boundary conditions are set in the `pdPatchBoundaries()` list.

### 3.1 Specular wall

The boundary model for specular walls is <dictval>pdSpecularWallPatch</dictval>. There are no other parameters to tune.

```c++
pdPatchBoundaries
(
    boundary
    {
        boundaryModel   pdSpecularWallPatch;
        
        patchBoundaryProperties
        {
            patchName   plate;
        }
    }
);
```

&nbsp;

### 3.2 Diffuse wall

The boundary model for diffuse walls is <dictval>pdDiffuseWallPatch</dictval>. The wall velocity and temperature are given in <subdict>pdDiffuseWallPatchProperties</subdict>.

```c++
pdPatchBoundaries
(
    boundary
    {
        boundaryModel   pdDiffuseWallPatch;
        
        patchBoundaryProperties
        {
            patchName   cylinder;
        }

        pdDiffuseWallPatchProperties
        {
            velocity      (0 0 0);
            temperature      1000;
        }
    }
);
```

&nbsp;

### 3.3 Diffuse-Neutralising wall

<!--The boundary model for mixed diffuse-specular wall interactions is <dictval>dsmcDiffuseSpecularWallPatch</dictval>. The wall velocity and temperature are given in <subdict>pdDiffuseWallPatchProperties</subdict> (see [3.2](https://hystrath.github.io/how-tos-picdsmc-fleming/how-tos-picdsmc-fleming-boundary-conditions/#32-diffuse-wall)), while the fraction of wall interactions that are diffuse, <dictkey>diffuseFraction</dictkey>, is given in <subdict>dsmcDiffuseSpecularWallPatchProperties</subdict>. For each particle-wall interaction, a random number is drawn and compared to <dictkey>diffuseFraction</dictkey> to decide on the type of reflection to perform.-->

```c++
pdPatchBoundaries
(
    boundary
    {
        boundaryModel   pdDiffuseNeutralisingWallPatch;

        pdDiffuseNeutralisingWallPatchProperties
        {
            typeElec 			                0;
            
            velocity 			          (0 0 0);
            temperature 			          350;

            ionsToNeutralise		       (O+);
            productsOfNeutralisation	((O));
        }
    }
);
```

<br>
  
---  
## 4) Cyclic boundary conditions

Cyclic boundary conditions are set in the `pdCyclicBoundaries()` list.

They are defined using the <dictval>pdReflectiveParticleMembranePatch</dictval> boundary model, and that for both patches.
An example is given hereafter where all Argon parcels hitting the membrane are mapped onto the corresponding cyclic patch. The species-dependent reflection probabilities can be controlled using <dictkey>reflectionProbabilities </dictkey> in the boundary model's properties dictionary, and a value of <dictval>1</dictval> would correspond to a specular wall.

```c++
pdCyclicBoundaries
(
    boundary
    {
        boundaryModel   pdReflectiveParticleMembranePatch;
        
        cyclicBoundaryProperties
        {
            patchName   leftPatch;
        }

        pdReflectiveParticleMembranePatchProperties
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
        boundaryModel   pdReflectiveParticleMembranePatch;
        
        cyclicBoundaryProperties
        {
            patchName   rightPatch;
        }

        pdReflectiveParticleMembranePatchProperties
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
