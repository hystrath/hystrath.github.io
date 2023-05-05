---
layout: page
title: Tutorials
subtitle: CFD Module - Dev release
nav-short: true
---

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()"><i class='fa fa-times'></i></a>
  <header>TUTORIALS</header>
  <a href="https://hystrath.github.io/tutos/dev/hy2foam/toc/"><center><img src="/docs/img/logos/hy2FoamLogo.png" width="60"></center></a>
  <a href="https://hystrath.github.io/tutos/dev/hy2foam/heatbath">Adiabatic heat bath</a>
  <a href="https://hystrath.github.io/tutos/dev/hy2foam/bluntedcone">Blunted cone</a>
  <a href="https://hystrath.github.io/tutos/dev/hy2foam/ramcii">RAM C-II spacecraft</a>
  <a href="https://hystrath.github.io/tutos/dev/hy2foam/toc/#4-nasa-msl-forebody">NASA MSL forebody</a>
  <a href="https://hystrath.github.io/tutos/dev/hy2foam/toc/#5-running-your-own-case">Running your own case</a>
  <br>
  <a href="https://hystrath.github.io/tutos/dev/hyfoam/toc/"><center><img src="/docs/img/logos/hyFoamLogo.png" width="50"></center></a>
  <a href="https://hystrath.github.io/tutos/dev/hyfoam/laminarflatplatelts">Mach 2 laminar flat plate (LTS)</a>
  <a href="https://hystrath.github.io/tutos/dev/hyfoam/axisymmetrichb2">Mach 9.59 HB2 configuration</a>
  <a href="https://hystrath.github.io/tutos/dev/hyfoam/lorrainscramjet">Lorrain's scramjet</a>
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
  <img src="/docs/img/logos/hy2FoamLogo.png" width="210">
</p>

<p align="center">
  <a class="btn btn-outline-dark" href="https://hystrath.github.io/tutos/fleming/hy2foam/toc/" role="button">Fleming release</a>
  <a class="btn btn-warning" href="https://hystrath.github.io/tutos/dev/hy2foam/toc/" role="button"><b>Dev release</b></a>
</p>

---  

# 1) Adiabatic heat bath

<p align="center">
Zero-dimensional | Thermal non-equilibrium | Chemistry-vibration coupling  
</p>

<p><img src="/docs/img/working_folder.png" width="40"> &nbsp; Working directory located <a href="https://github.com/hystrath/hyStrath/tree/OF-v2112/run/hyStrath/hy2Foam/heatBath"> here</a>.</p>

<p><img src="/docs/img/publis.png" width="40"> &nbsp; See Section 3.4. <i>Relaxation of a Chemically-Reacting Mixture</i> in <br> V. Casseau, R. C. Palharini, T. J. Scanlon, and R. E. Brown, "A Two-Temperature Open-Source CFD Model for Hypersonic Reacting Flows, Part One: Zero-Dimensional Analysis," <i>Aerospace</i>, vol. 3, no. 4, p. 34, <b>2016</b> &nbsp; <a href="http://www.mdpi.com/2226-4310/3/4/34/html" target="_blank" style="color:orange"> [Full HTML→]</a></p>  

[**[View more]**](https://hystrath.github.io/tutos/fleming/hy2foam/heatbath/)

<br>

---  

# 2) Blunted cone

<p align="center">
Axially-symmetric mesh | Thermal non-equilibrium | Slip boundary conditions  
</p>

<p><img src="/docs/img/working_folder.png" width="40"> &nbsp; Working directory located <a href="https://github.com/hystrath/hyStrath/tree/OF-v2112/run/hyStrath/hy2Foam/bluntedCone"> here</a></p>

<p><img src="/docs/img/publis.png" width="40"> &nbsp; See Section 3.1. <i>Mach 11.3 Blunted Cone</i> in <br> V. Casseau, D. E.R. Espinoza, T. J. Scanlon, and R. E. Brown, "A Two-Temperature Open-Source CFD Model for Hypersonic Reacting Flows, Part Two: Multi-Dimensional Analysis," <i>Aerospace</i>, vol. 3, no. 4, p. 45, <b>2016</b> &nbsp; <a href="http://www.mdpi.com/2226-4310/3/4/45/html" target="_blank" style="color:orange"> [Full HTML→]</a></p>

[**[View more]**](https://hystrath.github.io/tutos/dev/hy2foam/bluntedcone/)

<br>

---  

# 3) RAM C-II spacecraft

<p align="center">
Axially-symmetric mesh | Weakly-ionised flow
</p>

<p><img src="/docs/img/working_folder.png" width="40"> &nbsp; Will soon be available</p>
<!--Working directory located <a href="https://github.com/hystrath/hyStrath/tree/OF-v2112/run/hyStrath/hy2Foam/fireII/fireII_NRadia"> here</a>-->

<p><img src="/docs/img/publis.png" width="40"> &nbsp; See Section 5.3. <i>RAM-C Spacecraft</i> in <br> G. Yang, "Finite Element Simulation of Weakly Ionized Hypersonic Flows," Master's thesis, McGill University, Montreal (Canada), <b>2022</b> 
&nbsp; <a href="https://escholarship.mcgill.ca/downloads/bc386q61m?locale=en" target="_blank" style="color:orange"> [PDF→]</a></p>

[**[View more]**](https://hystrath.github.io/tutos/dev/hy2foam/ramcii/)


<br>

---

# 4) NASA MSL forebody

<p align="center">
Hypervelocity flow | MHD flow control 
</p>

<p><img src="/docs/img/working_folder.png" width="40"> &nbsp; Working directory located <a href="https://github.com/hystrath/hyStrath/tree/OF-v2112/run/hyStrath/hy2Foam/NASA_MSL_forebody/NASA_MSL_forebody_NR-MHD"> here</a></p>


<!--# 4) 2D cylinder-->

<!--<p align="center">-->
<!--Hypervelocity flow | Thermo-chemical non-equilibrium | Adiabatic wall-->
<!--</p>-->

<!--+ The working directory for the 2D axisymmetric FireII capsule forebody is located [here](https://github.com/hystrath/hyStrath/tree/OF-v2112/run/hyStrath/hy2Foam/fireII/fireII_NRadia).-->
<!--+ A description can be found in: V. Casseau _et al._, 12/2016: [A Two-Temperature Open-Source CFD Model for Hypersonic Reacting Flows, Part Two: Multi-Dimensional Analysis](http://www.mdpi.com/2226-4310/3/4/45/html), Section _3.2. Mach 20 Cylinder_.  -->

<!--+ [**[View more]**](https://hystrath.github.io/tutos/dev/hy2foam/2dcylinder/)-->


<br>

--- 

# 5) Running your own case 

When simulating the complex physics around a re-entry body, it is often necessary to break down the full problem into a sequence of stages and gradually build the case up in complexity. Indeed, convergence can become difficult because of the presence of steep gradients, flow chemistry, thermal non-equilibrium effects, etc, and different strategies must then be adopted to get the desired simulation setup to run.  
Some of these strategies are listed hereafter:  
  1- different levels of mesh refinement as the simulation progresses;  
  2- [non-reacting vs. reacting](https://hystrath.github.io/guides/dev/cfd/chemistry/#2-non-reacting-flow);  
  3- [continuum vs. rarefied boundary conditions](https://hystrath.github.io/guides/dev/cfd/initial-conditions/#3-temperature-fields);   
  4- [bounding the temperature field](https://hystrath.github.io/guides/dev/cfd/advanced/#2-bounding-the-temperature-field);  
  5- [Mach ramp](https://hystrath.github.io/guides/dev/cfd/initial-conditions/#42-linear-inlet-ramp) at the inlet;  
  6- [inviscid vs. viscous flow](https://hystrath.github.io/guides/dev/cfd/transport/#transport-modelling);  
  7- [no diffusion vs. species diffusion](https://hystrath.github.io/guides/dev/cfd/transport/#3-mass-diffusion);  
  8- use of the [continuum solver *hyFoam* vs. thermal non-equilibrium solver *hy2Foam*](https://hystrath.github.io/guides/dev/cfd/nonequilibrium/#1-thermal-equilibrium);  
  9- progressive increase in the [degree of rarefaction](https://hystrath.github.io/guides/dev/cfd/nonequilibrium/#32-knudsen-number);  
  10- gradual increase in the maximum CFL number.
  

