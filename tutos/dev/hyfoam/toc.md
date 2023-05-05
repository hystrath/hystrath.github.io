---
layout: page
title: Tutorials
subtitle: CFD Module - Fleming release
nav-short: true
---

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()"><i class='fa fa-times'></i></a>
  <header>TUTORIALS</header>
  <a href="https://hystrath.github.io/tutos/fleming/hyfoam/toc/"><center><img src="/docs/img/logos/hyFoamLogo.png" width="50"></center></a>
  <a href="https://hystrath.github.io/tutos/fleming/hyfoam/laminarflatplatelts">Mach 2 laminar flat plate (LTS)</a>
  <a href="https://hystrath.github.io/tutos/fleming/hyfoam/axisymmetrichb2">Mach 9.59 HB2 configuration</a>
  <a href="https://hystrath.github.io/tutos/fleming/hyfoam/lorrainscramjet">Lorrain's scramjet</a>
  <br>
  <a href="https://hystrath.github.io/tutos/fleming/hy2foam/toc/"><center><img src="/docs/img/logos/hy2FoamLogo.png" width="60"></center></a>
  <a href="https://hystrath.github.io/tutos/fleming/hy2foam/heatbath">Adiabatic heat bath</a>
  <a href="https://hystrath.github.io/tutos/fleming/hy2foam/bluntedcone">Blunted cone</a>
  <a href="https://hystrath.github.io/tutos/fleming/hy2foam/ramcii">RAM C-II spacecraft</a>
  <a href="https://hystrath.github.io/tutos/fleming/hy2foam/toc/#4-nasa-msl-forebody">NASA MSL forebody</a>
  <a href="https://hystrath.github.io/tutos/fleming/hy2foam/toc/#5-running-your-own-case">Running your own case</a>
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
  <img src="/docs/img/logos/hyFoamLogo.png" width="200">
</p>

<p align="center">
  <a class="btn btn-outline-dark" href="https://hystrath.github.io/tutos/fleming/hyfoam/toc/" role="button"><b>Fleming release</b></a>
  <a class="btn btn-warning" href="https://hystrath.github.io/tutos/dev/hyfoam/toc/" role="button"><i>Dev release</i></a>
</p>

---  

# 1) Mach 2 laminar flat plate (LTS)

<p align="center">
Attached shock wave | Laminar flow  | Local Time Stepping
</p>

<p><img src="/docs/img/working_folder.png" width="40"> &nbsp; Working directory located <a href="https://github.com/hystrath/hyStrath/tree/OF-v2112/run/hyStrath/hyFoam/laminarFlatPlateLTS"> here</a></p>

<p><img src="/docs/img/publis.png" width="40"> &nbsp; J.-J. O.E. Hoste and V. Casseau, "Verification and Validation of <i>hyFoam</i> for Supersonic External Flows," TechReport-HS1, <b>05/2021</b> &nbsp; <a href="https://github.com/hystrath/hyStrath/blob/OF-v2112/doc/TechReport-HS1-hostecasseau.pdf" target="_blank" style="color:orange"> [PDF→]</a></p>

[**[View more]**](https://hystrath.github.io/tutos/fleming/hyfoam/laminarflatplatelts/)

<br>

---  

# 2) Mach 9.59 HB2 configuration

<p align="center">
Axially-symmetric flow-field | Cold hypersonics
</p>

<p><img src="/docs/img/working_folder.png" width="40"> &nbsp; Working directory located <a href="https://github.com/hystrath/hyStrath/tree/OF-v2112/run/hyStrath/hyFoam/axisymmetric-HB2"> here</a></p>

<p><img src="/docs/img/publis.png" width="40"> &nbsp; J.-J. O.E. Hoste and V. Casseau, "Verification and Validation of <i>hyFoam</i> for Supersonic External Flows," TechReport-HS1, <b>05/2021</b> &nbsp; <a href="https://github.com/hystrath/hyStrath/blob/OF-v2112/doc/TechReport-HS1-hostecasseau.pdf" target="_blank" style="color:orange"> [PDF→]</a></p>

[**[View more]**](https://hystrath.github.io/tutos/fleming/hyfoam/axisymmetrichb2/)

<br>

---  

# 3) Lorrain's scramjet

<p align="center">
Scramjet flow-field | RAS turbulence modelling  
</p>

<p><img src="/docs/img/working_folder.png" width="40"> &nbsp; Working directory located <a href="https://github.com/hystrath/hyStrath/tree/OF-v2112/run/hyStrath/hyFoam/LorrainStageI"> here</a></p>

<p><img src="/docs/img/publis.png" width="40"> &nbsp; J.-J. O.E. Hoste, V. Casseau, M. Fossati, I. J. Taylor, and R. Gollan, "Numerical Modeling and Simulation of Supersonic Reacting Flows in Propulsion Systems by Open-Source Solvers," <i>21st AIAA International Space Planes and Hypersonic Systems and Technologies Conference</i> (Xiamen, China, 6-9 March 2017), AIAA Paper 2017-2411, <b>2017</b> &nbsp; <a href="http://eprints.gla.ac.uk/140369/1/140369.pdf" target="_blank" style="color:orange"> [PDF Preprint→]</a></p>

[**[View more]**](https://hystrath.github.io/tutos/fleming/hyfoam/lorrainscramjet/)

