---
layout: page
title: Guides
subtitle: CFD Module - Dev release
nav-short: true
---

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()"><i class='fa fa-times'></i></a>
  <header>GUIDE — CFD</header>
  <a href="https://hystrath.github.io/guides/dev/cfd/thermophysical/"><b>A. THERMOPHYSICAL</b></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/thermophysical/#1-species-thermophysical-properties" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Species thermo props</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/thermophysical/#2-addingremoving-energy-modes" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) +/- energy modes</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/thermophysical/#3-choosing-a-thermodem-dictionary" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) <i>thermoDEM</i> dictionary</span></a>

  <a href="https://hystrath.github.io/guides/dev/cfd/transport/"><b>B. TRANSPORT</b></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/transport/#1-species-shear-viscosity-and-thermal-conductivity" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Species transport props</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/transport/#2-mixing-rules" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Mixing rules</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/transport/#3-mass-diffusion" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Mass diffusion</span></a>

  <a href="https://hystrath.github.io/guides/dev/cfd/chemistry/"><b>C. CHEMISTRY</b></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/chemistry/#1-multi-species-flow" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Multi-species flow</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/chemistry/#2-non-reacting-flow" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Non-reacting flow</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/chemistry/#3-chemically-reacting-flow" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Chemically-reacting flow</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/chemistry/#4-to-go-further-chemistry-vibration-coupling" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) To go further</span></a>
  
  <a href="https://hystrath.github.io/guides/dev/cfd/nonequilibrium/"><b>D. NONEQUILIBRIUM</b></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/nonequilibrium/#1-thermal-equilibrium" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Thermal equilibrium</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/nonequilibrium/#2-thermal-non-equilibrium" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Thermal non-equilibrium</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/nonequilibrium/#3-mean-free-path-and-breakdown-parameter" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) MFP & Breakdown</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/nonequilibrium/#4-chemistry-vibration-coupling" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) Chem.-vib. coupling</span></a>
  
  <a href="https://hystrath.github.io/guides/dev/cfd/turbulence/"><b>E. TURBULENCE</b></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/turbulence/#1-laminar-flow-simulation" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Laminar</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/turbulence/#2-turbulent-flow-simulation" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Turbulent</span></a>
  
  <a href="https://hystrath.github.io/guides/dev/cfd/mhd/"><b>F. MHD</b></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/mhd/#1-enablingdisabling-mhd" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Enabling/disabling MHD</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/mhd/#2-mhd-models" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) MHD models</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/mhd/#3-electrical-conductivity-models" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Electrical conductivity</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/mhd/#4-hall-parameter" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) Hall parameter</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/mhd/#5-creation-of-an-initial-magnetic-field-and-electric-potential" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 5) Initial <i>B</i> & electric pot.</span></a>


  <a href="https://hystrath.github.io/guides/dev/cfd/initial-conditions/"><b>G. INITIAL CONDITIONS</b></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/initial-conditions/#1-the-include-sub-folder" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) The <i>include/</i> sub-folder</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/initial-conditions/#2-species-mass-or-molar-fractions" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Mass or molar fractions</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/initial-conditions/#3-temperature-fields" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Temperature fields</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/initial-conditions/#4-velocity-field" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) Velocity field</span></a>
  
  <a href="https://hystrath.github.io/guides/dev/cfd/numerics/" style="background-color:#FFCCCC"><b>H. NUMERICS</b></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/numerics/#1-time-schemes" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Time schemes</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/numerics/#2-flux-schemes" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Flux schemes</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/numerics/#3-other-spatial-schemes" style="background-color:#FFE6E6; padding-top:4px;"><span style="font-size:13px">&nbsp;&nbsp; 3) Other spatial schemes</span></a>
  
  <a href="https://hystrath.github.io/guides/dev/cfd/advanced/"><b>I. ADVANCED</b></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/advanced/#1-on-the-fly-dictionary-editing" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) On-the-fly editing</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/advanced/#2-bounding-the-temperature-field" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Bounding the temperature</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/advanced/#3-adaptive-mesh-refinement" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Adaptive mesh refinement</span></a>
  
  <a href="https://hystrath.github.io/guides/dev/cfd/monitoring-post-processing"><b>J. MONITORING & POST-PROCESSING</b></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/monitoring-post-processing/#1-monitoring" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Monitoring</span></a>
  <a href="https://hystrath.github.io/guides/dev/cfd/monitoring-post-processing/#2-post-processing" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Post-processing</span></a>
</div>

<span style="position: fixed;font-size:30px;cursor:pointer; margin:0px; top:60px;left:30px;" onclick="reopenNav()">&#9776;</span>

<script>
function openNav() {
  document.getElementById("mySidenav").style.width = "225px";
  document.getElementById("mySidenav").style.transition = "0s";
  document.getElementById('mySidenav').scrollTop = "1100";
}

function closeNav() {
  document.getElementById("mySidenav").style.width = "0px";
}

function reopenNav() {
  document.getElementById("mySidenav").style.width = "225px";
  document.getElementById("mySidenav").style.transition = "0.5s";
  document.getElementById('mySidenav').scrollTop = "1100";
}

openNav()
</script>

These guidelines are based on the working folder located [here](https://github.com/hystrath/hyStrath/tree/OF-v2112/run/hyStrath/hy2Foam/genericCase).  

# Numerics

---  
## 1) Time schemes

### 1.1 Euler time scheme  

The implicit first-order Euler time scheme can be selected in <dirname>system/</dirname><dict>fvSchemes</dict> as follows

```c++
ddtSchemes
{
    default           Euler;
}
```

For more information, please check the [official documentation](https://www.openfoam.com/documentation/guides/v2112/doc/guide-schemes-time-euler.html).

&nbsp;  

### 1.2 Local time stepping scheme  

To select the first-order local time stepping (LTS) scheme, open the <dirname>system/</dirname><dict>fvSchemes</dict> dictionary and set

```c++
ddtSchemes
{
    default           localEuler rDeltaT;
}
```

The [Lorrain scramjet tutorial](https://hystrath.github.io/tutos/dev/hyfoam/toc/#3-lorrains-scramjet) is a suitable case to use LTS and the aforementioned time discretisation scheme is the only modification to be made.  

> Local time stepping is currently inappropriate for axisymmetric and chemically-reacting simulations.

For more information, please check the [official documentation](https://www.openfoam.com/documentation/guides/v2112/doc/guide-schemes-time-local-euler.html).

&nbsp;

### 1.3 Other time schemes

For other time schemes, please refer to the [official documention](https://www.openfoam.com/documentation/guides/v2112/doc/guide-schemes-time.html). 

<br>

---  
## 2) Flux schemes  

### 2.1 Kurganov and Tadmor

Kurganov-Noelle-Petrova (KNP) and Kurganov-Tadmor (KT) flux schemes do not have any model coefficients.
In <dirname>system/</dirname><dict>fvSchemes</dict>, they can be selected as follows

```c++
fluxScheme            Kurganov;
```

and

```c++
fluxScheme            Tadmor;
``` 

<p><img src="/docs/img/publis.png" width="40"> &nbsp; A. Kurganov, S. Noelle, and G. Petrova, "Semi-Discrete Central-Upwind Scheme for Hyperbolic Conservation Laws and Hamilton-Jacobi Equations," <i>SIAM Journal on Scientific Computing</i>, Vol. 23, No. 3, pp. 707-740, <b>2001</b> &nbsp; <a href="https://doi.org/10.1137/S1064827500373413" style="color:red"> [SIAM Portal→]</a></p>

&nbsp;

### 2.2 AUSM+up

The final AUSM<sup>+</sup>-up algorithm given by Liou (2006) is recalled hereafter.
The left and right Mach number states are equal to

<p style="text-align:center">
    `M_{L&#8725;R} = \frac{u_{L&#8725;R}}{a_{1&#8725;2}}`,
</p>

where <i>a<sub>1&#8725;2</sub></i> is the interface speed of sound defined as

<p style="text-align:center">
    `a_{1&#8725;2} = min \left(a&#770;_L, a&#770;_R\right)`,
</p>

with

<p style="text-align:center">
    `a&#770;_L = \frac{(a^&#8727;)^2}{max(a^&#8727;, u_L)}`,
</p>

<p style="text-align:center">
    `a&#770;_R = \frac{(a^&#8727;)^2}{max(a^&#8727;, -u_R)}`,
</p>

and

<p style="text-align:center">
    `(a^&#8727;)^2 = \frac{2 (&#947; - 1)}{&#947; + 1} h`.
</p>


The scaling factor, <i>f<sub>a</sub></i>, can either be set to a value between 0 and 1 or according to the following formula:
<p style="text-align:center">
    `f_a = M_o \left(2 - M_o\right)`.
</p>

where

<p style="text-align:center">
    `M_o^2 = min(1, max(\bar{M}^2, M_&infin;^2))`.
</p>

The interface Mach number, <i>Ma<sub>1&#8725;2</sub></i>, is expressed as

<p style="text-align:center">
    `Ma_{1&#8725;2} = \mathcal{M}_{(4)}^{+}(Ma_L) + \mathcal{M}_{(4)}^{-}(Ma_R) - \frac{K_p}{f_a} max (1 - σ \bar{M}^2)\mathcal{M}_{(4)}^{+} \frac{p_R - p_L}{ρ_{1&#8725;2}a_{1&#8725;2}^2}`,
</p>

where

<p style="text-align:center">
    `\mathcal{M}_{(1)}^&plusmn;(M) = \frac{1}{2} (M &plusmn; |M|)`,
</p>

<p style="text-align:center">
    `\mathcal{M}_{(2)}^&plusmn;(M) = &plusmn;\frac{1}{4}(M &plusmn; 1)^2`,
</p>

<p style="text-align:center">
    `\mathcal{M}_{(4)}^&plusmn;(M) = \mathcal{M}_{(2)}^&plusmn; (1 &mnplus; 16 &#946; \mathcal{M}_{(2)}^&mnplus;)^2`,
</p>

and 

<p style="text-align:center">
    `σ &#8804; 1`.
</p>

The interface mass flux is given by

<p style="text-align:center">
<ul>
    <li>`\dot{m}_{1&#8725;2} = a_{1&#8725;2} M_{1&#8725;2} ρ_L` &nbsp; if `M_{1&#8725;2} > 0`</li> 
    <li>`\dot{m}_{1&#8725;2} = a_{1&#8725;2} M_{1&#8725;2} ρ_R` &nbsp; otherwise</li>
</ul>
</p>


The pressure flux at the interface, <i>p<sub>1&#8725;2</sub></i>, can be written as

<p style="text-align:center">
    `p_{1&#8725;2} = \mathcal{P}_{(5)}^{+} p_L + \mathcal{P}_{(5)}^{-} p_R - K_u \mathcal{P}_{(5)}^{+} \mathcal{P}_{(5)}^{-} (f_a + a_{1&#8725;2}) \times (u_L + u_R)`,
</p>

where

<p style="text-align:center">
    `\mathcal{P}_{(5)}^&plusmn;(M) = \mathcal{M}_{(2)}^&plusmn;  [ (&plusmn; 2 - M) &mnplus; 16 &#945; M \mathcal{M}_{(2)}^&mnplus; ].`
</p>


<p><img src="/docs/img/publis.png" width="40"> &nbsp; M.-S. Liou, "A Sequel to AUSM, Part II: AUSM<sup>+</sup>-up for All Speeds," <i>Journal of Computational Physics</i>, Vol. 214, No. 1, pp. 137-170, <b>2006</b> &nbsp; <a href="https://www.sciencedirect.com/science/article/abs/pii/S0021999105004274" style="color:red"> [ScienceDirect Portal→]</a></p>

A flux scheme dictionary is created in <dirname>system/</dirname><dict>fvSchemes</dict> to store the AUSM<sup>+</sup>-up coefficients, whose default values are shown in the following listing

```c++
fluxScheme            AUSM+up;

fluxSchemeCoefficients
{
    AUSM+upCoefficients
    {
        MachInf       1.0e-6;
        
        alpha         0.1875;
        beta           0.125;
        sigma            1.0;
        Kp              0.25;
        Ku              0.75;
    }
}
```

For info, this flux scheme is used in [Sod's subsonic and supersonic shock tube tutorials](https://hystrath.github.io/tutos/dev/hy2foam/sod/).

<br>

---  
## 3) Other spatial schemes  

For other spatial schemes, please refer to the [official documention](https://www.openfoam.com/documentation/guides/v2112/doc/guide-schemes.html#sec-schemes-spatial). 
