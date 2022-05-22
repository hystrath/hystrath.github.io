---
layout: page
title: Tutorials
subtitle: Hybrid Modules - Fleming release
nav-short: true
---

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()"><i class='fa fa-times'></i></a>
  <header>TUTORIALS</header>
  <a href="https://hystrath.github.io/tutos-pdfoam"><center><b><i>pdFoam</i></b></center></a>
  <a href="https://hystrath.github.io/tutos-pdfoam/#1-planar-sheath">Planar sheath</a>
  <a href="https://hystrath.github.io/tutos-pdfoam/#2-two-stream-instability">Two-stream instability</a>
<!--  <br>-->
<!--  <a href="https://hystrath.github.io/tutos-hyperfoam"><center><b><i>hyperFoam</i></b></center></a>-->
<!--  <a href="https://hystrath.github.io/tutos-hyperfoam/#1-supersonic-flat-plate">Supersonic flat plate</a>-->
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
  <span style="font-size:36px"><i><strong>pdFoam</strong></i></span>
</p>

---  

# 1) Planar sheath

<p align="center">
 
</p>

<p><img src="/docs/img/working_folder.png" width="40"> &nbsp; Working directory located <a href="https://github.com/vincentcasseau/hyStrath/tree/master/run/hyStrath/pdFoam/2D_sheath"> here</a></p>

<p><img src="/docs/img/publis.png" width="40"> &nbsp; See Section 3.3.1. <i>EF Validation: Planar Sheath Structure</i>, pp. 8-9, in <br> C. J. Capon, M. Brown, C. White, T. J. Scanlon, and R. R. Boyce, "pdFOAM: A PIC-DSMC code for near-Earth plasma-body interactions," <i>Computers and Fluids</i>, vol. 149, no. 1, pp. 160-171, <b>2017</b> &nbsp; <a href="http://eprints.gla.ac.uk/138700/7/138700.pdf" target="_blank" style="color:orange"> [PDF Preprint→]</a></p>

<br>

---  

# 2) Two-stream instability

<p align="center">

</p>

<p><img src="/docs/img/working_folder.png" width="40"> &nbsp; Working directory located <a href="https://github.com/vincentcasseau/hyStrath/tree/master/run/hyStrath/pdFoam/twoStream"> here</a></p>

<p><img src="/docs/img/publis.png" width="40"> &nbsp; See Appendix B, pp. 236-238, in <br> C. J. Capon, "Ionospheric Aerodynamics in Low Earth Orbit," PhD thesis, University of New South Wales, Canberra (Australia), <b>2017</b> &nbsp; <a href="http://unsworks.unsw.edu.au/fapi/datastream/unsworks:46528/SOURCE01?view=true" target="_blank" style="color:orange"> [PDF→]</a></p>
