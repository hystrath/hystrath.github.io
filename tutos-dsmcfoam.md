---
layout: page
title: Tutorials
subtitle: DSMC Module - Fleming release
nav-short: true
---

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()"><i class='fa fa-times'></i></a>
  <header>TUTORIALS</header>
  <a href="https://hystrath.github.io/tutos-dsmcfoam"><center><b><i>dsmcFoam+</i></b></center></a>
  <a href="https://hystrath.github.io/tutos-dsmcfoam/#1-supersonic-flat-plate">Supersonic flat plate</a>
  <a href="https://hystrath.github.io/tutos-dsmcfoam/#2-hypersonic-corner">Hypersonic corner</a>
  <a href="https://hystrath.github.io/tutos-dsmcfoam/#3-couette-flow">Couette flow</a>
  <a href="https://hystrath.github.io/tutos-dsmcfoam/#4-orion-capsule-non-reacting-107-km">Orion capsule</a>
  <a href="https://hystrath.github.io/tutos-dsmcfoam/#5-axially-symmetric-blunt-cylinder">Axially-symmetric blunt cylinder</a>
  <a href="https://hystrath.github.io/tutos-dsmcfoam/#6-chemically-reacting-heat-bath">Chemically-reacting heat bath</a>
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
  
<p align="center">
  <span style="font-size:36px"><i><strong>dsmcFoam+</strong></i></span>
</p>

---  

# 1) Supersonic flat plate

<p align="center">

</p>

<p><img src="/docs/img/working_folder.png" width="40"> &nbsp; Working directory located <a href="https://github.com/hystrath/hyStrath/tree/master/run/hyStrath/dsmcFoam%2B/supersonicFlatPlate"> here</a></p>

<p><img src="/docs/img/publis.png" width="40"> &nbsp; T. J. Scanlon, E. Roohi, C. White, M. Darbandi, and J. M. Reese, "An open source, parallel DSMC code for rarefied gas flows in arbitrary geometries," <i>Computer & Fluids</i>, vol. 39, no. 10, pp. 2078-2089, <b>2010</b> &nbsp; <a href="https://www.research.ed.ac.uk/portal/files/17079048/ScanlonEtAlCandF2010.pdf" target="_blank" style="color:orange"> [PDF→]</a></p>

<p>Adapted from: G. A. Bird, Molecular gas dynamics and the direct simulation of gas flows, Clarendon, Oxford, UK, pp. 340-348, <b>1994</b></p>

<br>

---  

# 2) Hypersonic corner

<p align="center">

</p>

<p><img src="/docs/img/working_folder.png" width="40"> &nbsp; Working directory located <a href="https://github.com/hystrath/hyStrath/tree/master/run/hyStrath/dsmcFoam%2B/hypersonicCorner"> here</a></p>

<p><img src="/docs/img/publis.png" width="40"> &nbsp; T. J. Scanlon, E. Roohi, C. White, M. Darbandi, and J. M. Reese, "An open source, parallel DSMC code for rarefied gas flows in arbitrary geometries," <i>Computer & Fluids</i>, vol. 39, no. 10, pp. 2078-2089, <b>2010</b> &nbsp; <a href="https://www.research.ed.ac.uk/portal/files/17079048/ScanlonEtAlCandF2010.pdf" target="_blank" style="color:orange"> [PDF→]</a></p>

<p>Adapted from: G. A. Bird, Molecular gas dynamics and the direct simulation of gas flows, Clarendon, Oxford, UK, pp. 394-401, <b>1994</b></p>

<br>

---  

# 3) Couette flow

<p align="center">

</p>

<p><img src="/docs/img/working_folder.png" width="40"> &nbsp; Working directory located <a href="https://github.com/hystrath/hyStrath/tree/master/run/hyStrath/dsmcFoam%2B/couette_N2-O2"> here</a></p>

<p><img src="/docs/img/publis.png" width="40"> &nbsp; D. E.R. Espinoza, "An Open-Source Hybrid CFD-DSMC Solver for High-Speed Flows," PhD thesis, University of Strathclyde, Glasgow (UK), <b>2018</b> &nbsp; <a href="https://github.com/hystrath/hyStrath/blob/master/doc/PhDthesis-danielespinoza.pdf" target="_blank" style="color:orange"> [PDF→]</a></p>

<br>

---  

# 4) Orion capsule (non-reacting, 107 km)

<p align="center">

</p>

<p><img src="/docs/img/working_folder.png" width="40"> &nbsp; Working directory located <a href="https://github.com/hystrath/hyStrath/tree/master/run/hyStrath/dsmcFoam%2B/orion107kmNR"> here</a></p>

<p><img src="/docs/img/publis.png" width="40"> &nbsp; See pp. 86-99 in <br> R. C. Palharini, "Atmospheric Reentry Modelling Using an Open-Source DSMC Code," PhD thesis, University of Strathclyde, Glasgow (UK), <b>2014</b> &nbsp; <a href="https://github.com/hystrath/hyStrath/blob/master/doc/PhDthesis-rodrigopalharini.pdf" target="_blank" style="color:orange"> [PDF→]</a></p>

<p>Adapted from: J. N. Moss, K. A. Boyles, and F. A. Greene, "Orion aerodynamics for hypersonic free molecular to continuum conditions," <i>14th AIAA/AHI International Space Planes and Hypersonic Systems and Technologies Conference</i> (Canberra, Australia, 6-9 Nov. 2006), AIAA Paper 2006-8081, <b>2006</b> &nbsp; <a href="https://arc.aiaa.org/doi/10.2514/6.2006-8081" target="_blank" style="color:red"> [AIAA Portal→]</a></p>

<br>

---  

# 5) Axially-symmetric blunt cylinder

<p align="center">
<!--Radial Weighting Factor-->
</p>

<p><img src="/docs/img/working_folder.png" width="40"> &nbsp; Working directory located <a href="https://github.com/hystrath/hyStrath/tree/master/run/hyStrath/dsmcFoam%2B/axisymmetricFlatnosedCylinder"> here</a></p>

<p><img src="/docs/img/publis.png" width="40"> &nbsp; See p. 29 in <br> C. White, M. K. Borg, T. J. Scanlon, S. M. Longshaw, B. John, D. R. Emerson, and J. M. Reese, "dsmcFoam+: An OpenFOAM based direct simulation Monte Carlo solver," <i>Computer Physics Communications</i>, vol. 224, no. 1, pp. 22-43, <b>2018</b> &nbsp; <a href="https://pure.strath.ac.uk/portal/files/81235392/White_etal_CPC_2017_an_OpenFOAM_based_direct_simulation_Monte_Carlo_solver.pdf" target="_blank" style="color:orange"> [PDF→]</a></p>

<p>Adapted from: G. A. Bird, Molecular gas dynamics and the direct simulation of gas flows, Clarendon, Oxford, UK, pp. 374-377, <b>1994</b></p>

<br>

---  

# 6) Chemically-reacting heat bath

<p align="center">
<!--5-species air | Dissociation | Exchange-->
</p>

<p><img src="/docs/img/working_folder.png" width="40"> &nbsp; Working directory located <a href="https://github.com/hystrath/hyStrath/tree/master/run/hyStrath/dsmcFoam%2B/heatBath-5species"> here</a></p>

<p><img src="/docs/img/publis.png" width="40"> &nbsp; T. J. Scanlon, C. White, M. K. Borg, R. C. Palharini, E. Farbar, I. D. Boyd, J. M. Reese, and R. E. Brown, "Open-Source Direct Simulation Monte Carlo Chemistry Modeling for Hypersonic Flows," <i>AIAA Journal</i>, vol. 53, no. 6, pp. 1670-1681, <b>2015</b> &nbsp; <a href="https://deepblue.lib.umich.edu/bitstream/handle/2027.42/140685/1.J053370.pdf?sequence=1" target="_blank" style="color:orange"> [PDF→]</a></p>
