---
layout: page
title: Flow Solvers
nav-short: true
---

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()"><i class='fa fa-times'></i></a>
  <header>FLOW SOLVERS</header>
  <a href="https://hystrath.github.io/solvers/fleming/hy2foam/"><center><img src="/docs/img/logos/hy2FoamLogo.png" width="60"></center></a>
  <a href="https://hystrath.github.io/guides/fleming/cfd/toc/">Guide</a>
  <a href="https://hystrath.github.io/tutos/fleming/hy2foam/toc/">Tutorials</a>
  <a href="https://github.com/hystrath/hyStrath/tree/master/applications/solvers/compressible/hy2Foam">Source code</a>
  <a href="https://hystrath.github.io/publications/hy2foam/">Publications</a>
  <a href="https://hystrath.github.io/people/#cfd-module--hyfoam-hy2foam">Developers</a>
  <a href="https://hystrath.github.io/disclaimer/">Disclaimer</a>
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
{: #hy2Foam }
<p align="center">
  <img src="/docs/img/logos/hy2FoamLogo.png" width="200"/>
</p>

_hy2Foam_ is an open-source two-temperature computational fluid dynamics (CFD)
solver that has been developed to tackle the highly complex flow physics of the hypersonic planetary
atmospheric entry. Implemented within the OpenFOAM framework, the code has the capability to model physical phenomena relative to the high-speed chemically-reacting environment surrounding a spacecraft. The core of the solver initially relied on OpenFOAM solvers _rhoCentralFoam_ and _reactingFoam_ and it has been complemented with the many new features listed below  

<h5>THERMAL NON-EQUILIBRIUM</h5>
* addition of the electronic and electron energy modes  
* implementation of Park's two-temperature model for a single vibro-electronic energy pool
* modelling of energy transfers between the different energy pools
  + Vibrational-Translational (V—T): Landau-Teller
  + Heavy-particle — electron (H—e): Appleton-Bray
* modifications to the Smoluchowski temperature jump and Maxwell velocity slip boundary conditions
* computation of the mean free path and breakdown parameter
&nbsp;
<h5>CHEMICAL NON-EQUILIBRIUM</h5>
* finite-rate volume chemistry
* customizable chemistry databases (Park 1993, Park 1994, Dunn & Kang 1973, Scanlon 2015) including dissociation, electron impact dissociation, electron impact ionization, associative ionization, exchange and charge exchange reactions  
* chemistry-vibration coupling: Park TTv model, coupled vibration-dissociation-vibration (CVDV) model
* polyatomics species (_e.g._, CO2 for the Mars atmospheric entry)
&nbsp;
<h5>TRANSPORT</h5>
* species viscosity: Blottner, power law, Sutherland, constant
* species thermal conductivity: Eucken
* mixing rules: Wilke, Armaly & Sutton
* species diffusion models: Lewis number, generalised Fick's law, SCEBD model, inclusion of pressure gradient effects
* computation of the convective & diffusive wall heat flux
&nbsp;
<h5>TURBULENCE</h5>
* no changes made to OF-v1706: laminar, k-omega SST, k-Epsilon, Spalart Allmaras, etc
&nbsp;
<h5>MAGNETOHYDRODYNAMICS (MHD)</h5>
* low magnetic Reynolds number model  
* MHD source terms added to the Navier-Stokes-Fourier equations: Lorentz force & Joule heating  
* various electrical conductivity models: Bush, Chapman-Cowling, Raizer, Spitzer-Harm  
* Hall effect
<!--* Ongoing or planned developments-->
<!--  + Ion slip  -->
<!--  + Artificial ionization  -->
<!--  + P-1 radiation model -->
&nbsp;
<h5>MISCELLANEOUS</h5>
* inlet boundary condition to gradually increase the free-stream flow velocity  
* dictionaries that can be re-read on-the-fly (_e.g._, for high-performance computing)  
* adaptive mesh refinement (DyM) based on the Mach number gradient or normalised gradients of density or pressure
* layer functions for the strongly-coupled hybrid CFD-DSMC code _hyperFoam_  

&nbsp;

<table cellspacing="0" cellpadding="0">
<tr>
  <td>This work was initiated at the University of Strathclyde (Glasgow, UK) and was funded by the <a href="https://www.epsrc.ac.uk/">Engineering and Physical Sciences Research Council</a> (EPSRC) from February 2014 until early 2017.</td>
</tr>
<tr>
  <td>The first version of the MHD module was developed at the Ioffe Institute & Peter the Great St. Petersburg Polytechnic University (St Petersburg, Russia) in 2017-2018.</td>
</tr>
<tr>
<td style="text-align:center" colspan="2"> Volunteering work from mid-2017 onwards.
</td>
</tr>
</table>
