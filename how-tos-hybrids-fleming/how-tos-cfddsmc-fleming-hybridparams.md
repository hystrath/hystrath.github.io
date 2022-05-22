---
layout: page
title: How-tos
subtitle: Hybrid Modules - Fleming release
nav-short: true
---

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()"><i class='fa fa-times'></i></a>
  <header>HOW-TOS — HYBD</header>
  <a href="https://hystrath.github.io/how-tos-hybrids-fleming/how-tos-cfddsmc-fleming-folderstructure/"><b>A. FOLDER STRUCTURE</b></a>
<!--  <a href="https://hystrath.github.io/how-tos-hybrids-fleming/how-tos-cfddsmc-fleming-folderstructure/#1-species-thermophysical-properties"><span style="font-size:13px">&nbsp;&nbsp; 1) Species thermo props</span></a>-->
<!--  <a href="https://hystrath.github.io/how-tos-hybrids-fleming/how-tos-cfddsmc-fleming-folderstructure/#2-addingremoving-energy-modes" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) +/- energy modes</span></a>-->
<!--  <a href="https://hystrath.github.io/how-tos-hybrids-fleming/how-tos-cfddsmc-fleming-folderstructure/#3-choosing-a-thermodem-dictionary" style="background-color:#FFE6E6; padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) <i>thermoDEM</i> dictionary</span></a>-->

  <a href="https://hystrath.github.io/how-tos-hybrids-fleming/how-tos-cfddsmc-fleming-hybridparams/" style="background-color:#FFCCCC"><b>B. HYBRID PARAMETERS</b></a>
  <a href="https://hystrath.github.io/how-tos-hybrids-fleming/how-tos-cfddsmc-fleming-hybridparams/#1-zone-names"  style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Zone names</span></a>
  <a href="https://hystrath.github.io/how-tos-hybrids-fleming/how-tos-cfddsmc-fleming-hybridparams/#2-breakdown-parameter" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Breakdown parameter</span></a>
  <a href="https://hystrath.github.io/how-tos-hybrids-fleming/how-tos-cfddsmc-fleming-hybridparams/#3-buffer-layers"  style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Buffer layers</span></a>
</div>

<span style="position: fixed;font-size:30px;cursor:pointer; margin:0px; top:60px;left:30px;" onclick="reopenNav()">&#9776;</span>

<script>
function openNav() {
  document.getElementById("mySidenav").style.width = "225px";
  document.getElementById("mySidenav").style.transition = "0s";
}

function closeNav() {
  document.getElementById("mySidenav").style.width = "0px";
}

function reopenNav() {
  document.getElementById("mySidenav").style.width = "225px";
  document.getElementById("mySidenav").style.transition = "0.5s";
}

openNav()
</script>


# Hybrid parameters

The hybrid parameters are provided in the <foldername>system/dsmc/<foldername><dict>hybridDict</dict> dictionary and the meaning of its entries is explained in the following sections.

```c++
FoamFile
{
    version         2.0;
    format          ascii;
    class           dictionary;
    object          "hybridDict";
}

// * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * //

dsmcZoneName                "DSMC";
innerBufferZoneName         "InnerBuffer";
outerBufferZoneName         "OuterBuffer";
cfdZoneName                 "CFD";
mixtureName                 "Mixture";

dtRatioCFD                  1000000;// * 200

dtRatioDSMC                 500000;
iterPerBufferReset          1;

nFirstBufferCells           5;
nSecondBufferCells          5;

breakdown                   0.05;

updateZones                 false;

characteristicLength        1.0;

zoneNoDSMC                  false;

resetDSMC                   true;
```


---  
## 1) Zone names

```c++
dsmcZoneName                "DSMC";
innerBufferZoneName         "InnerBuffer";
outerBufferZoneName         "OuterBuffer";
cfdZoneName                 "CFD";
mixtureName                 "Mixture";
```

---  
## 2) Breakdown parameter


```c++
breakdown                   0.05;
```

---  
## 3) Buffer layers

