---
layout: page
title: Flow Solvers
nav-short: true
---

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()"><i class='fa fa-times'></i></a>
  <header>FLOW SOLVERS</header>
  <a href="https://hystrath.github.io/solvers/fleming/pdfoam/"><center><b><i>pdFoam</i></b></center></a>
  <a href="https://hystrath.github.io/guides/fleming/dsmc/toc/">DSMC Guide</a>
  <a href="https://hystrath.github.io/guides/fleming/picdsmc/toc/">HYBD Guide</a>
  <a href="https://hystrath.github.io/tutos/fleming/pdfoam/toc/">Tutorials</a>
  <a href="https://github.com/hystrath/hyStrath/tree/master/applications/solvers/hybridMethods/pdFoam">Source code</a>
  <a href="https://hystrath.github.io/publications/pdfoam/">Publications</a>
  <a href="https://hystrath.github.io/about/people/#pic-dsmc">Developers</a>
  <a href="https://hystrath.github.io/download/disclaimer/">Disclaimer</a>
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
{: #pdFoam }
<p align="center">
  <span style="font-size:36px"><i><strong>pdFoam</strong></i></span>
</p>

_pdFoam_ is a hybrid electrostatic particle-in-cell (PIC) — direct simulation Monte Carlo (DSMC) code for near-Earth plasma-body interactions. Understanding the interaction of the near-Earth space environment with orbiting bodies is critical, both from a design and scientific perspective. In low-Earth orbit (LEO), the interaction between the ionosphere and orbiting objects is well studied from a charging perspective. Not well understood is the effect of the ionosphere on the motion of LEO objects, _i.e._, ionospheric aerodynamics. _pdFoam_ is the self-consistent modelling tool to take up these challenges. 

&nbsp;

<table cellspacing="0" cellpadding="0">
<tr>
  <td>This code has been developed at the University of New South Wales (UNSW) in Canberra, Australia.</td>
</tr>
<tr>
<td style="text-align:center" colspan="2"> Volunteering work from 2018 onwards.
</td>
</tr>
</table>
