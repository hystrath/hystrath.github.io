---
layout: page
title: How-tos
subtitle: DSMC Module - Dev release
nav-short: true
---

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()"><i class='fa fa-times'></i></a>
  <header>HOW-TOS — DSMC</header>
  <a href="https://hystrath.github.io/how-tos-dsmc-dev/how-tos-dsmc-dev-thermophysical/"><b>A. THERMOPHYSICAL</b></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-dev/how-tos-dsmc-dev-thermophysical/#1-species-thermophysical-properties" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Species properties</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-dev/how-tos-dsmc-dev-thermophysical/#2-addingremoving-energy-modes"  style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) +/- energy modes</span></a>

  <a href="https://hystrath.github.io/how-tos-dsmc-dev/how-tos-dsmc-dev-collision-dynamics"><b>B. COLLISION DYNAMICS</b></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-dev/how-tos-dsmc-dev-collision-dynamics/#1-collision-partner-selection"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Collision partner selection</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-dev/how-tos-dsmc-dev-collision-dynamics/#2-binary-collision"  style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Binary collision</span></a>

  <a href="https://hystrath.github.io/how-tos-dsmc-dev/how-tos-dsmc-dev-chemistry/" style="background-color:#FFCCCC"><b>C. CHEMISTRY</b></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-dev/how-tos-dsmc-dev-chemistry/#1-chemical-reaction-models"  style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Chemical reaction models</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-dev/how-tos-dsmc-dev-chemistry/#2-dissociation-reaction" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Dissociation reaction</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-dev/how-tos-dsmc-dev-chemistry/#3-exchange-reaction" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Exchange reaction</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-dev/how-tos-dsmc-dev-chemistry/#4-combined-reactions" style="background-color:#FFE6E6; padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) Combined reactions</span></a>

  <a href="https://hystrath.github.io/how-tos-dsmc-dev/how-tos-dsmc-dev-boundary-conditions"><b>D. BOUNDARY CONDITIONS</b></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-dev/how-tos-dsmc-dev-boundary-conditions/#1-generalities"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) Generalities</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-dev/how-tos-dsmc-dev-boundary-conditions/#2-inflow--outflow-boundary-conditions"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Inflow & Outflow</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-dev/how-tos-dsmc-dev-boundary-conditions/#3-wall-boundary-conditions"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Wall</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-dev/how-tos-dsmc-dev-boundary-conditions/#4-cyclic-boundary-conditions"  style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) Cyclic</span></a>
  
  <a href="https://hystrath.github.io/how-tos-dsmc-dev/how-tos-dsmc-dev-coordinate-system/"><b>E. COORDINATE SYSTEM</b></a>
  
  <a href="https://hystrath.github.io/how-tos-dsmc-dev/how-tos-dsmc-dev-initialisation/"><b>F. INITIALISATION</b></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-dev/how-tos-dsmc-dev-initialisation/#1-the-dsmcinitialisedict-dictionary"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) <i>dsmcInitialiseDict</i></span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-dev/how-tos-dsmc-dev-initialisation/#2-dsmc-parcel-vs-real-particles"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Parcel vs. particles</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-dev/how-tos-dsmc-dev-initialisation/#3-creating-the-0-folder"  style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Creating the <i>0/</i> folder</span></a>
  
  <a href="https://hystrath.github.io/how-tos-dsmc-dev/how-tos-dsmc-dev-sampling/"><b>G. SAMPLING</b></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-dev/how-tos-dsmc-dev-sampling/#1-the-fieldpropertiesdict-dictionary"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 1) <i>fieldPropertiesDict</i></span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-dev/how-tos-dsmc-dev-sampling/#2-steady-state-simulations"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 2) Steady-state simulations</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-dev/how-tos-dsmc-dev-sampling/#3-transient-simulations" style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 3) Transient simulations</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-dev/how-tos-dsmc-dev-sampling/#4-mean-free-path-computation"  style="padding-top:4px; padding-bottom:4px"><span style="font-size:13px">&nbsp;&nbsp; 4) MFP computation</span></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-dev/how-tos-dsmc-dev-sampling/#5-resume-sampling" style="padding-top:4px"><span style="font-size:13px">&nbsp;&nbsp; 5) Resume sampling</span></a>
  
  <a href="https://hystrath.github.io/how-tos-dsmc-dev/how-tos-dsmc-dev-load-balancing/"><b>H. LOAD BALANCING</b></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-dev/how-tos-dsmc-dev/#i-adaptive-mesh-refinement"><b>I. ADAPTIVE MESH REFINEMENT</b></a>
  <a href="https://hystrath.github.io/how-tos-dsmc-dev/how-tos-dsmc-dev/#j-monitoring--post-processing"><b>J. MONITORING & POST-PROCESSING</b></a>
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

&nbsp; 

# Chemistry

---  
## 1) Chemical reaction models

_dsmcFoam+_ implements the Quantum-Kinetics (QK) reaction model and chemical reactions are defined in the <dirname>system/</dirname><dict>chemReactDict</dict> dictionary.  

A chemically-frozen gas is obtained by leaving the `reactions()` list empty.  
For chemically reacting flows, the available reaction models are
 - <dictval>dissociationQK</dictval>
 - <dictval>exchangeQK</dictval>
 - <dictval>ionisationQK</dictval>
 - <dictval>chargeExchangeQK</dictval>
 - <dictval>associativeIonisationQK</dictval>

These models can also be combined as follows:
 - <dictval>dissociationExchangeQK</dictval>
 - <dictval>dissociationIonisationQK</dictval>
 - <dictval>dissociationIonisationExchangeQK</dictval>
 - <dictval>dissociationIonisationChargeExchangeQK</dictval>
 - <dictval>dissociationIonisationExchangeChargeExchangeQK</dictval>
 - <dictval>ionisationExchangeQK</dictval>
 - <dictval>ionisationChargeExchangeQK</dictval>
 - <dictval>ionisationExchangeChargeExchangeQK</dictval>
 - <dictval>ionisationAssociativeIonisationQK</dictval>


For example, if a species pair can undergo both dissociation and exchange reactions (as it is the case for N2 and O), then the `dissociationExchangeQK` model should be selected.  

The four primitive models can also be used to isolate a specific reaction and compute its forward reaction rate.  

The dissociation and ionisation temperatures, given in the <subdict>moleculesProperties</subdict>/<subdict>#speciesName</subdict> subdictionary of the <dirname>constant/</dirname><dict>dsmcProperties</dict> dictionary, have already been introduced in [A.1 Species thermophysical properties](https://hystrath.github.io/how-tos-dsmc-dev/how-tos-dsmc-dev-thermophysical/#1-species-thermophysical-properties).  

<b>NB</b>: An example for 5-species air is given in the [chemically-reacting heat bath tutorial](https://hystrath.github.io/tutos-dsmcfoam/#6-chemically-reacting-heat-bath), [on this page](https://github.com/hystrath/hyStrath/blob/master/run/hyStrath/dsmcFoam%2B/heatBath-5species/system/chemReactDict).

&nbsp;

<p style="text-align:center; color:Tomato"><strong> >> Because the electronic energy is unavailable, only dissociation and exchange reactions are introduced in the DSMC How-tos << </strong></p>

<br>

---  
## 2) Dissociation reaction

In the `reactions()` list, a dissociation reaction can be defined as

```c++
reactions
(
    oxygen_atomicOxygen_reaction
    {
        reactionModel   dissociationQK;

        reactants           (O2 O);
        allowSplitting        yes;
        writeRatesToTerminal   no;
        
        dissociationQKProperties
        {
            dissociationProducts  ((O O) ());
        }
    }
);    
```  

where the products of the reaction can be found in the properties of the reaction model, here <subdict>dissociationQKProperties</subdict>. <dictkey>allowSplitting</dictkey> is a switch to allow or not the collision partners to split. To compute the forward reaction rate of a reaction, this switch needs to be turned <dictval>off</dictval> and <dictkey>writeRatesToTerminal</dictkey> must be turned <dictval>on</dictval>. Otherwise, the setup shown above should be preferred.
  
    
In the next example, two dissociation reactions are defined at once for the pair `(O2 N2)`, and there is thus no need to redefine another reaction for `(N2 O2)`  

```c++
reactions
(
    oxygen_nitrogen_reaction
    {
        reactionModel   dissociationQK;

        reactants          (O2 N2);
        allowSplitting        yes;
        writeRatesToTerminal   no;
        
        dissociationQKProperties
        {
            dissociationProducts  ((O O) (N N));
        }
    }
);    
```

<br>

--- 
## 3) Exchange reaction

In the `reactions()` list, a exchange reaction can be defined as

```c++
reactions
(
    nitrogen_atomicOxygen_reaction
    {
        reactionModel   exchangeQK;
        
        reactants           (N2 O);
        allowSplitting        yes;
        writeRatesToTerminal   no;

        exchangeQKProperties
        {
            exchangeProducts       (NO N);
            heatOfReactionExchange -37482; // in kelvin (endothermic)
            aCoeff                   0.15; // Scanlon 2015
            bCoeff                   0.15; // Scanlon 2015
        }
    }
);    
```

There are three additional coefficients defined for this reaction type in <subdict>exchangeQKProperties</subdict>: the heat of reaction (in kelvin, negative for endothermic reactions and positive for exothermic reactions), and two parameters `aCoeff` and `bCoeff` to ensure that the equilibrium constant follows that given by statistical mechanics. In <dict>chemReactDict</dict>, the values provided are taken from T. J. Scanlon _et al._, 06/2015: [Open-Source Direct Simulation Monte Carlo Chemistry
Modeling for Hypersonic Flows](https://pdfs.semanticscholar.org/5819/1acfdf18b4c0ca3905b161fb65829aadd89c.pdf), while slighty different values can be found in Bird's 2013 book.     

<br>

---  
## 4) Combined reactions

Combining two reaction models is simply obtained by modifying the <dictkey>reactionModel</dictkey> and defining both <subdict>dissociationQKProperties</subdict> and <subdict>exchangeQKProperties</subdict> subdictionaries in <subdict>#reactionName</subdict>

```c++
reactions
(
    nitrogen_atomicOxygen_reaction
    {
        reactionModel   dissociationExchangeQK;
        
        reactants           (N2 O);
        allowSplitting        yes;
        writeRatesToTerminal   no;

        dissociationQKProperties
        {
            dissociationProducts  ((N N) ());
        }
        
        exchangeQKProperties
        {
            exchangeProducts       (NO N);
            heatOfReactionExchange -37482; // in kelvin (endothermic)
            aCoeff                   0.15; // Scanlon 2015
            bCoeff                   0.15; // Scanlon 2015
        }
    }
);    
```
