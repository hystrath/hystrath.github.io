---
layout: page
title: Maintenance
nav-short: true
--- 

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()"><i class='fa fa-times'></i></a>
  <header>DOWNLOAD</header>
  <a href="https://hystrath.github.io/download/compatibility/">Compatibility</a>
  <a href="https://hystrath.github.io/download/maintenance/" style="background-color:#FFCCCC">Maintenance</a>
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

<table>
  <tr>
    <td ><b><i>hyStrath</i> branch</b></td>
    <td style="text-align:center"><b>OpenFOAM version</b></td>
    <td style="text-align:center"><b>Initial release</b></td>
    <td style="text-align:center"><b>Code updates until</b></td>
    <td style="text-align:center"><b>Support until</b></td>
  </tr>
  <tr>
    <td >OF-2.4.0</td>
    <td style="text-align:center">OF-2.4.0-MNF, OF-2.4.0, OF-2.3.0</td>
    <td style="text-align:center">5 Dec 2016</td>
    <td style="text-align:center">4 Dec 2017</td>
    <td style="text-align:center">31 Mar 2018</td>
  </tr>
  <tr>
    <td >OF-v1612+</td>
    <td style="text-align:center">OF-v1612+</td>
    <td style="text-align:center">5 Dec 2017</td>
    <td style="text-align:center">29 Aug 2018</td>
    <td style="text-align:center">30 Nov 2019</td>
  </tr>
  <tr>  
    <td >OF-v1706<a href="https://hystrath.github.io/contributions/#list-of-external-contributions">*</a></td>
    <td style="text-align:center">OF-v1706</td>
    <td style="text-align:center">12 May 2018</td>
    <td style="text-align:center" colspan="2">29 Aug 2018, merged into Master</td>
  </tr>
  <tr>
    <td ><b>Master</b></td>
    <td style="text-align:center">OF-v1706</td>
    <td style="text-align:center" colspan="3"> </td>
  </tr>
</table>
