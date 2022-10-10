---
layout: page
title: How-tos
subtitle: CFD Module - Dev release
nav-short: true
---

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()"><i class='fa fa-times'></i></a>
  <header>HOW-TOS — CFD</header>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-thermophysical/"><b>A. THERMOPHYSICAL</b></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-thermophysical/#1-species-thermophysical-properties" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Species thermo props</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-thermophysical/#2-addingremoving-energy-modes" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) +/- energy modes</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-thermophysical/#3-choosing-a-thermodem-dictionary" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) <i>thermoDEM</i> dictionary</span></a>

  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-transport/"><b>B. TRANSPORT</b></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-transport/#1-species-shear-viscosity-and-thermal-conductivity" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Species transport props</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-transport/#2-mixing-rules" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Mixing rules</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-transport/#3-mass-diffusion" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Mass diffusion</span></a>

  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-chemistry/"><b>C. CHEMISTRY</b></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-chemistry/#1-multi-species-flow" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Multi-species flow</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-chemistry/#2-non-reacting-flow" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Non-reacting flow</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-chemistry/#3-chemically-reacting-flow" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Chemically-reacting flow</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-chemistry/#4-to-go-further-chemistry-vibration-coupling" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) To go further</span></a>
  
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-nonequilibrium/"><b>D. NONEQUILIBRIUM</b></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-nonequilibrium/#1-thermal-equilibrium" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Thermal equilibrium</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-nonequilibrium/#2-thermal-non-equilibrium" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Thermal non-equilibrium</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-nonequilibrium/#3-mean-free-path-and-breakdown-parameter" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) MFP & Breakdown</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-nonequilibrium/#4-chemistry-vibration-coupling" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) Chem.-vib. coupling</span></a>
  
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-turbulence/"><b>E. TURBULENCE</b></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-turbulence/#1-laminar-flow-simulation" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Laminar</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-turbulence/#2-turbulent-flow-simulation" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Turbulent</span></a>
  
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-mhd/" style="background-color:#FFCCCC"><b>F. MHD</b></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-mhd/#1-enablingdisabling-mhd" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Enabling/disabling MHD</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-mhd/#2-mhd-models" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) MHD models</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-mhd/#3-electrical-conductivity-models" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Electrical conductivity</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-mhd/#4-hall-parameter" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) Hall parameter</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-mhd/#5-creation-of-an-initial-magnetic-field-and-electric-potential" style="background-color:#FFE6E6; padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 5) Initial <i>B</i> & electric pot.</span></a>


  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-initial-conditions/"><b>G. INITIAL CONDITIONS</b></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-initial-conditions/#1-the-include-sub-folder" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) The <i>include/</i> sub-folder</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-initial-conditions/#2-species-mass-or-molar-fractions" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Mass or molar fractions</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-initial-conditions/#3-temperature-fields" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Temperature fields</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-initial-conditions/#4-velocity-field" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) Velocity field</span></a>
  
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-advanced/"><b>H. ADVANCED</b></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-advanced/#1-local-time-stepping" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Local time stepping</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-advanced/#2-on-the-fly-dictionary-editing" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) On-the-fly editing</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-advanced/#3-bounding-the-temperature-field" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Bounding the temperature</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-advanced/#4-adaptive-mesh-refinement" style="background-color:#FFE6E6; padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) Adaptive mesh refinement</span></a>
  
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-monitoring-post-processing"><b>I. MONITORING & POST-PROCESSING</b></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-monitoring-post-processing/#1-monitoring" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Monitoring</span></a>
  <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-monitoring-post-processing/#2-post-processing" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Post-processing</span></a>
</div>

<span style="position: fixed;font-size:30px;cursor:pointer; margin:0px; top:60px;left:30px;" onclick="reopenNav()">&#9776;</span>

<script>
function openNav() {
  document.getElementById("mySidenav").style.width = "225px";
  document.getElementById("mySidenav").style.transition = "0s";
  document.getElementById('mySidenav').scrollTop = "820";
}

function closeNav() {
  document.getElementById("mySidenav").style.width = "0px";
}

function reopenNav() {
  document.getElementById("mySidenav").style.width = "225px";
  document.getElementById("mySidenav").style.transition = "0.5s";
  document.getElementById('mySidenav').scrollTop = "820";
}

openNav()
</script>

This how-to is based on the working folder located [here](https://github.com/vincentcasseau/hyStrath/tree/master/run/hyStrath/hy2Foam/NASA_MSL_forebody/NASA_MSL_forebody_NR-MHD).  

# MHD modelling

---
## 1) Enabling/disabling MHD

In the <dirname>constant/</dirname> folder, add the optional <dictkey>mhdDictFile</dictkey> key to the <dict>thermophysicalProperties</dict> dictionary as

```c++
twoTemperatureDictFile "<constant>/thermo2TModel";

mhdDictFile "<constant>/mhdProperties";

temperatureBounds
{
    Tlow    200;
    Thigh   15000;
}
```

This <dict>mhdProperties</dict> dictionary is listing all the MHD parameters 

```c++
active          true;

mhdModel        lowReMag;

hallEffect      false;

electricalConductivityModel Bush;

constantElectricalConductivityCoeffs
{
    value           5100;
}

BushCoeffs
{
    sigma0          5100;
    T0              12000;
    n               2;
}
```

The first switch, <dictkey>active</dictkey>, can be used to enable or disable MHD. If it is set to <dictval>false</dictval>, then none of the other keys matter.

<br>

---
## 2) MHD models

<p>The electric current density, j (in A/m<sup>2</sup>), is given by Ohm's law</p>

<p style="text-align:center">
 `j = σ (E + U &#215; B)`
</p>

where  
<ul>
  <li>`σ` is the scalar or tensor electrical conductivity in S/m (see <a href="https://hystrath.github.io/how-tos-cfd-dev/how-tos-cfd-dev-mhd/#3-electrical-conductivity-models">§3</a>)</li>
  <li>`E` is the electric field (in V/m)</li>
  <li>`B` is the total magnetic field, sum of the imposed and induced magnetic fields (in T)</li>
  <li>`U` is the velocity field.</li>
</ul> 

The Lorentz force appearing as a source term in the momemtum equations is then defined as

<p style="text-align:center">
`F^{L} = j &#215; B`
</p>

and the Joule heating source term appearing in the total energy equation can be expressed as

<p style="text-align:center">
`Q^{J} = j ⋅ E`
</p>


### 2.1 Low magnetic Reynolds number model

The low magnetic Reynolds number model can be selected as follows  

```c++
mhdModel        lowReMag;
```

<p>Under the inductionless approximation, `Re_{m}` << 1, the influence of the velocity field on the magnetic field can be neglected.
The total magnetic field is thus the imposed magnetic field.</p>

<p>
<b>Current limitations:</b>
<ul>
  <li> constant total magnetic field (the magnetic induction equation is not solved) </li>
  <li> Poisson equation not solved for the electric potential </li>
</ul>
</p>
  

<br>

---
## 3) Electrical conductivity models

### 3.1 Constant electrical conductivity

<p>A constant electrical conductivity, in S/m, can be prescribed using 
the <dictval>constantElectricalConductivity</dictval> model as</p>

```c++
electricalConductivityModel constantElectricalConductivity;

constantElectricalConductivityCoeffs
{
    value           5100;
}
```

<br>

### 3.2 Bush  

This model can be implemented as  

```c++
electricalConductivityModel Bush;

BushCoeffs
{
    sigma0          5100;
    T0              12000;
    n               2;
}
```

<p>In the <dictval>Bush</dictval> model, the electrical conductivity field, `σ`, is given by</p>

<p style="text-align:center">
`σ = σ_{0}*(T/T_{0})^n`
</p>

where  
<ul>
  <li>`σ_{0}` is a reference electrical conductivity in S/m</li>
  <li>`T_{0}` is a reference temperature in K</li>
  <li>`n` is a temperature exponent</li>
  <li>`T` is the local trans-rotational temperature in K.</li>
</ul> 
 
<br>

### 3.3 Chapman-Cowling  

This model can be implemented as  

```c++
electricalConductivityModel ChapmanCowling;
```

<p>In the <dictval>ChapmanCowling</dictval> model, the electrical conductivity field, `σ`, is given by</p>

<p style="text-align:center">
`σ = 4.0227904*10^{-18}*n_{e^{-}}/sqrt(T)`
</p>

where  
<ul>
  <li>`T` is the local trans-rotational temperature in K</li>
  <li>`n_{e^{-}}` is the local electron number density in m<sup>-3</sup> defined as</li>
</ul>

<p style="text-align:center">
`n_{e^{-}} = p_{e^{-}}/(k_{B}*T)`
</p>

where  
<ul>
  <li>`k_{B}` is the Bolzmann constant in J/K</li>
  <li>`p_{e^{-}}` is the local electron pressure in Pa</li>
</ul>

<br>

### 3.4 Raizer 

This model can be implemented as  

```c++
electricalConductivityModel Raizer;
```

<p>In the <dictval>Raizer</dictval> model, the electrical conductivity field, `σ`, is given by</p>

<p style="text-align:center">
`σ = 83.0*exp({-3.6*10^{4}}/T)`
</p>

<p>
where `T` is the local trans-rotational temperature in K.
</p>

<br>

### 3.5 Spitzer-Harm  

This model can be implemented as  

```c++
electricalConductivityModel SpitzerHarm;
```

<p>In the <dictval>SpitzerHarm</dictval> model, the electrical conductivity field, `σ`, is given by</p>

<p style="text-align:center">
`σ = 1.56*10^{-4}*T^{1.5}/ln(1.23*10^{4}*T^{1.5}/sqrt(n_{e^{-}}))`
</p>

where  
<ul>
  <li>`T` is the local trans-rotational temperature in K</li>
  <li>`n_{e^{-}}` is the local electron number density in m<sup>-3</sup> defined as</li>
</ul>

<p style="text-align:center">
`n_{e^{-}} = p_{e^{-}}/(k_{B}*T)`
</p>

where  
<ul>
  <li>`k_{B}` is the Bolzmann constant in J/K</li>
  <li>`p_{e^{-}}` is the local electron pressure in Pa</li>
</ul>

<br>

---
## 4) Hall parameter

Hall effects can be accounted for using the <dictkey>hallEffect</dictkey> switch

```c++
hallEffect      true;
constantHallParameter   1.0; // optional, default: -1.0
```

When the optional key <dictkey>constantHallParameter</dictkey> isn't provided (i.e., left negative), the Hall parameter field is calculated as  

<p style="text-align:center">
`β = σ*B/(e*n_{e^{-}}`
</p>

and the scalar electrical conductivity is multiplied by the following tensor to 
yield the tensor electrical conductivity

<p style="text-align:center">
 <td>  `1/D`
        <math>
          <mrow>
            <mo>(</mo>
            <mtable>
              <mtr>
                <mtd>
                  <mi>B² + β²⋅Bx²</mi>
                </mtd>
                <mtd>
                  <mi>β⋅(β⋅By⋅Bx + B⋅Bz)</mi>
                </mtd>
                <mtd>
                  <mi>β⋅(β⋅Bz⋅Bx + B⋅By)</mi>
                </mtd>
              </mtr>
              <mtr>
                <mtd>
                  <mi>β⋅(β⋅By⋅Bx - B⋅Bz)</mi>
                </mtd>
                <mtd>
                  <mi>B² + β²⋅By²</mi>
                </mtd>
                <mtd>
                  <mi>β⋅(β⋅Bz⋅By + B⋅Bx)</mi>
                </mtd>
              </mtr>
              <mtr>
                <mtd>
                  <mn> β*(β⋅Bz⋅Bx - B⋅By)
                  </mn>
                </mtd>
                <mtd>
                  <mn> β⋅(β⋅Bz⋅By + B⋅Bx)</mn>
                </mtd>
                <mtd>
                  <mn> B² + β²⋅Bz² </mn>
                </mtd>
              </mtr>
            </mtable>
            <mo>)</mo>
          </mrow>
        </math>
      </td>
</p>

where 

<p style="text-align:center">
`D = B^2 (1 + β^2)`
</p>

<br>

---
## 5) Creation of an initial magnetic field and electric potential

You can set-up the initial magnetic field and electric potential field manually or by either using [funkySetFields](https://openfoamwiki.net/index.php/Contrib/funkySetFields) or `foamCalc`.  

For the magnetic field, the file header is

```c++
FoamFile
{
    version     2.0;
    format      ascii;
    class       volVectorField;
    location    "0";
    object      B;
}
// * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * //

dimensions      [1 0 -2 0 0 -1 0];

```

while it is as follows for the electric potential

```c++
FoamFile
{
    version     2.0;
    format      ascii;
    class       volScalarField;
    location    "0";
    object      elecPot;
}
// * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * //

dimensions	[1 2 -3 0 0 -1 0];

```
