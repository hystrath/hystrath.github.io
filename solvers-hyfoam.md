---
layout: page
title: Flow Solvers
nav-short: true
---

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()"><i class='fa fa-times'></i></a>
  <header>FLOW SOLVERS</header>
  <a href="https://hystrath.github.io/solvers-hyfoam/"><center><img src="/docs/img/logos/hyFoamLogo.png" width="50"></center></a>
  <a href="https://hystrath.github.io/how-tos-cfd-fleming/how-tos-cfd-fleming/">How-tos</a>
  <a href="https://hystrath.github.io/tutos-hyfoam/">Tutorials</a>
  <a href="https://github.com/hystrath/hyStrath/tree/master/applications/solvers/compressible/hy2Foam">Source code</a>
  <a href="https://hystrath.github.io/publications-hyfoam/">Publications</a>
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
{: #hyFoam }
<p align="center"> 
  <img src="/docs/img/logos/hyFoamLogo.png" width="190"/>
</p>

_hyFoam_ is an open-source computational fluid dynamics (CFD)
solver that derives from [_hy2Foam_](https://hystrath.github.io/solvers-hy2foam/). The trans-rotational and vibro-electronic energy modes are considered to be in thermal equilibrium, thus producing a single-temperature CFD solver with capabilities to model the high-speed chemically-reacting environment inside a scramjet. Most of _hy2Foam_ features remain accessible and _hyFoam_ further receives the addition of

<h5>CHEMICAL NON-EQUILIBRIUM</h5>
* customizable chemistry databases: Evans & Schexnayder 1980, Jachimowski 1992
* hydrogen compounds in the thermochemical database
&nbsp;
<h5>TRANSPORT</h5>
* CEA2 (Chemical Equilibrium with Applications, NASA) transport model

&nbsp;

<table cellspacing="0" cellpadding="0">
<tr>
  <td>This work was initiated at the University of Strathclyde and was funded by the <a href="https://www.epsrc.ac.uk/">Engineering and Physical Sciences Research Council</a> (EPSRC) from February 2014 until early 2017.</td>
</tr>
<tr>
<td style="text-align:center" colspan="2"> Volunteering work from mid-2017 onwards.
</td>
</tr>
</table>
