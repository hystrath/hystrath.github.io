---
layout: page
title: Flow Solvers
nav-short: true
---

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()"><i class='fa fa-times'></i></a>
  <header>FLOW SOLVERS</header>
  <a href="#"><center><b><i>hyperFoam</i></b></center></a>
  <a href="https://hystrath.github.io/guides/fleming/cfd/toc/">CFD Guide</a>
  <a href="https://hystrath.github.io/guides/fleming/dsmc/toc/">DSMC Guide</a>
  <a href="https://hystrath.github.io/guides/fleming/cfddsmc/toc/">HYBD Guide</a>
  <a href="https://hystrath.github.io/publications/hyperfoam/">Publications</a>
  <a href="https://hystrath.github.io/people/#cfd-dsmc-not-released-yet">Developers</a>
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
{: #hyperFoam }
<p align="center">
  <span style="font-size:36px"><i><strong>hyperFoam</strong></i></span>
</p>

_hyperFoam_ is a hybrid CFD-DSMC solver that uses _hy2Foam_ (CFD) and _dsmcFoam+_ (DSMC) to resolve flow-fields in the slip-transition regime. Using a mixture of Boyd's gradient-length local Knudsen number (KnGLL) and a modified generalised Chapman-Enskog parameter, _hyperFoam_ is capable of identifying continuum and rarefied zones within the computational domain and solve each with its respective CFD or DSMC solver. _hyperFoam_ has been used to simulate several Couette flows, each of different complexity, and good agreement was shown between the DSMC and hybrid results for these simulations. Furthermore, reasonably similar accuracy was found between the DSMC and hybrid results for a Mach 6 Knudsen 0.01 flow over a cylinder.

<br>

The source code will be released open-source after journal publication.

<br>

<table cellspacing="0" cellpadding="0">
<tr>
  <td>This work was initiated at the University of Strathclyde (Glasgow, UK) and was funded by the <a href="https://www.epsrc.ac.uk/">Engineering and Physical Sciences Research Council</a> (EPSRC) from February 2014 until early 2017.</td>
</tr>
<tr>
<td style="text-align:center"> Volunteering work from 2019 onwards.
</td>
</tr>
</table>
