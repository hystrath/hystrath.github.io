---
layout: page
title: Compatibility
nav-short: true
--- 

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()"><i class='fa fa-times'></i></a>
  <header>DOWNLOAD</header>
  <a href="https://hystrath.github.io/download/compatibility/" style="background-color:#FFCCCC">Compatibility</a>
  <a href="https://hystrath.github.io/download/maintenance/">Maintenance</a>
  <a href="https://hystrath.github.io/download/fleming/installation/">Installation</a>
  <a href="https://hystrath.github.io/download/fleming/sync/">Sync</a>
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

The OpenFOAM versions listed below are the <strong>only ones</strong> that are supported by this platform.  

### Master branch  
+ OF-v1706: [https://www.openfoam.com/releases/openfoam-v1706](https://www.openfoam.com/releases/openfoam-v1706)  

<div style="line-height:50%;">
    <br>
</div> 

### OF-v2112 branch (coming soon)
+ OF-v2112: [https://www.openfoam.com/releases/openfoam-v2112](https://www.openfoam.com/releases/openfoam-v2112)  

<div style="line-height:50%;">
    <br>
</div> 

### OF-v1612+ branch (deprecated)
+ OF-v1612+: [https://www.openfoam.com/releases/openfoam-v1612+](https://www.openfoam.com/releases/openfoam-v1612+) 

<div style="line-height:50%;">
    <br>
</div>  

### OF-2.4.0 branch (deprecated)   
+ OF-2.4.0-MNF: [https://github.com/MicroNanoFlows/OpenFOAM-2.4.0-MNF](https://github.com/MicroNanoFlows/OpenFOAM-2.4.0-MNF)  
+ OF-2.4.0: [http://openfoam.org/download/2-4-0-ubuntu](http://openfoam.org/download/2-4-0-ubuntu)  
+ OF-2.3.0: [http://openfoam.org/download/2-3-0-ubuntu](http://openfoam.org/download/2-3-0-ubuntu)  
