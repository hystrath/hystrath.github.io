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

  <a href="https://hystrath.github.io/guides/dev/dsmc/boundary-conditions"><b>D. BOUNDARY CONDITIONS</b></a>
  <a href="https://hystrath.github.io/guides/dev/dsmc/boundary-conditions/#1-generalities"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Generalities</span></a>
  <a href="https://hystrath.github.io/guides/dev/dsmc/boundary-conditions/#2-inflow--outflow-boundary-conditions"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Inflow & Outflow</span></a>
  <a href="https://hystrath.github.io/guides/dev/dsmc/boundary-conditions/#3-wall-boundary-conditions"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Wall</span></a>
  <a href="https://hystrath.github.io/guides/dev/dsmc/boundary-conditions/#4-cyclic-boundary-conditions"  style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) Cyclic</span></a>
  
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
  
  <a href="https://hystrath.github.io/guides/dev/dsmc/load-balancing/" style="background-color:#FFCCCC"><b>H. LOAD BALANCING</b></a>
  <a href="https://hystrath.github.io/guides/dev/dsmc/toc/#i-adaptive-mesh-refinement"><b>I. ADAPTIVE MESH REFINEMENT</b></a>
  <a href="https://hystrath.github.io/guides/dev/dsmc/toc/#j-monitoring--post-processing"><b>J. MONITORING & POST-PROCESSING</b></a>
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

# Load balancing

Load imbalance can be monitored in the _log.dsmcFoam+_ logfile at `writeTime`.

```c++
Time = 0.14

    Collisions                      = 8948

    Number of DSMC particles        = 775997
    Number of stuck particles       = 0
    Number of free particles        = 775997
    Average linear kinetic energy   = 7.404581292e-19
    Average rotational energy       = 2.317800406e-20
    Average vibrational energy      = 4.740872058e-22
    Average electronic energy       = 0
    Total energy                    = 1583.643485

Stage 1.0  ExecutionTime = 20600.77 s  ClockTime = 21680 s  Iteration 20000 (7.67 s)

    Maximum imbalance = 6.174121807%
```

In the <dirname>system/</dirname><dict>loadBalanceDict</dict> dictionary, the maximum imbalance that is tolerated is prescribed using the key <dictkey>maximumAllowableImbalance</dictkey> and it is a scalar ranging between 0 and 1. <dictval>0.1</dictval> thus means a 10% imbalance and in the log shown above, domain repartitioning would not have been triggered.

```c++
enableBalancing                true;

maximumAllowableImbalance       0.1;

balanceUntilTime               0.01; // in seconds

weightField       dsmcNMean_mixture;

limitTimeDirBackups               2; 
```

Once steady-state is reached, it is recommended to perform domain repartitioning one last time and <dictkey>balanceUntilTime</dictkey> could be set to match the value of <dictkey>resetAtOutputUntilTime</dictkey> in <dict>fieldPropertiesDict</dict> (see [F.2 Sampling/Steady-state simulations](https://hystrath.github.io/guides/dev/dsmc/sampling/#2-steady-state-simulations)). The field used as a weight for domain repartitioning is called <dictkey>weightField</dictkey> and <dictkey>limitTimeDirBackups</dictkey> is an optional entry to limit the number of concurrent time directory backups (the default value is <dictval>-1</dictval> meaning there is no restriction on the total number of stored directories). 

Finally, the `Stage number` in _log.dsmcFoam+_ is incremented every time domain repartitioning is called

```c++
Stage 2.0  ExecutionTime = 28.47 s  ClockTime = 33 s  Iteration 50 (0.59 s)
```
