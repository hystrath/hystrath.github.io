---
layout: page
title: Flow Solvers
nav-short: true
---

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()"><i class='fa fa-times'></i></a>
  <header>FLOW SOLVERS</header>
  <a href="https://hystrath.github.io/solvers-dsmcfoam/"><center><b><i>dsmcFoam+</i></b></center></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-fleming/how-tos-dsmc-fleming/">How-tos</a>
  <a href="https://hystrath.github.io/tutos-dsmcfoam/">Tutorials</a>
  <a href="https://github.com/vincentcasseau/hyStrath/tree/master/applications/solvers/discreteMethods/dsmc/dsmcFoam%2B">Source code</a>
  <a href="https://hystrath.github.io/disclaimer/">Disclaimer</a>
  <a href="https://hystrath.github.io/people/#dsmc-module--dsmcfoam">Developers</a>
</div>

<span style="position: fixed;font-size:30px;cursor:pointer; margin:0px; top:60px;left:30px;" onclick="reopenNav()">&#9776;</span>

<script>
function openNav() {
  document.getElementById("mySidenav").style.width = "210px";
  document.getElementById("mySidenav").style.transition = "0s";
}

function closeNav() {
  document.getElementById("mySidenav").style.width = "0px";
  localStorage.removeItem('show_sidenav');
}

function reopenNav() {
  document.getElementById("mySidenav").style.width = "210px";
  document.getElementById("mySidenav").style.transition = "0.5s";
  localStorage.setItem("show_sidenav", true);
}

if (localStorage.getItem("show_sidenav")) openNav()
</script>

--- 

###### &nbsp;
{: #dsmcFoam+ }
<p align="center">
  <span style="font-size:36px"><i><strong>dsmcFoam+</strong></i></span>
</p>

The original <i>dsmcFoam+</i> code, that is referred to as <i>dsmcFoam+ MNF</i>, is available on the [MicroNanoFlows Github page](https://github.com/MicroNanoFlows/OpenFOAM-2.4.0-MNF/tree/devel-craig). The modified version featured on _hyStrath_ branched out in December 2015 with the new features being as follows

<h5>CODE STRUCTURE / IMPROVEMENTS</h5>
* improved load balancing feature
* improved axially-symmetric capability
* wall boundary condition classes rewritten
* QK reaction classes rewritten
* corrections made to the calculation of macroscopic properties
&nbsp;
<h5>THERMAL NON-EQUILIBRIUM</h5>
* new model for vibrational energy redistribution: constant vibrational collision number
&nbsp;
<h5>POROUS MEDIA</h5>
* new wall boundary conditions to model absorption & adsorption/desorption mechanisms
* measurement of the mean squared displacement (thus effective diffusivity) and particle transit time
&nbsp;
<h5>MISCELLANEOUS</h5>
* capability to run steady normal shock wave computations
* layer functions for the strongly-coupled hybrid CFD-DSMC code _hyperFoam_
&nbsp;
<h5>ONGOING OR PLANNED DEVELOPMENTS</h5>
* adaptive mesh refinement (AMR)  
* variable time-step method
* modelling of free-electrons
* extension of the QK reaction classes to Martian entry problems   
  
&nbsp;
  
<table cellspacing="0" cellpadding="0">
<tr>
  <td>This work was initiated at the Universities of Strathclyde and Glasgow (2017 — June 2018).</td>
</tr>
<tr>
<td style="text-align:center"> Volunteering work from mid-2018 onwards.
</td>
</tr>
</table>  
