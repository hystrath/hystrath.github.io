---
layout: page
title: People
nav-short: true
---

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()"><i class='fa fa-times'></i></a>
  <header>PEOPLE</header>
  <a href="https://hystrath.github.io/people/#cfd-module--hyfoam-hy2foam">CFD module</a>
  <a href="https://hystrath.github.io/people/#ablation-module--arc-not-released">Ablation module</a>
  <a href="https://hystrath.github.io/people/#dsmc-module--dsmcfoam">DSMC module</a>
  <a href="https://hystrath.github.io/people/#hybrid-modules--hyperfoam-pdfoam">Hybrid modules</a>
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

---
## CFD module &nbsp;—&nbsp; __*hyFoam*__, __*hy2Foam*__  
_Lead developer_:   
* <a style="text-decoration: none" href="https://uk.linkedin.com/in/vincentcasseau" target="_blank">
    <span class="fa-stack" aria-hidden="true">
      <i class="fas fa-circle fa-stack-2x" style='color:#0072B1'></i>
      <i class="fab fa-linkedin fa-stack-1x fa-inverse"></i>
    </span>
    <span class="sr-only">LinkedIn</span>
  </a> &nbsp; **Dr Vincent Casseau** 

_Contributors_:  
* <a style="text-decoration: none" href="https://uk.linkedin.com/in/daniel-espinoza-52862452" target="_blank">
    <span class="fa-stack" aria-hidden="true">
      <i class="fas fa-circle fa-stack-2x" style='color:#0072B1'></i>
      <i class="fab fa-linkedin fa-stack-1x fa-inverse"></i>
    </span>
    <span class="sr-only">LinkedIn</span>
  </a> &nbsp; **Dr Daniel E.R. Espinoza**    
* <a style="text-decoration: none" href="https://uk.linkedin.com/in/jimmy-john-hoste-17278644" target="_blank">
    <span class="fa-stack" aria-hidden="true">
      <i class="fas fa-circle fa-stack-2x" style='color:#0072B1'></i>
      <i class="fab fa-linkedin fa-stack-1x fa-inverse"></i>
    </span>
    <span class="sr-only">LinkedIn</span>
  </a> <a style="text-decoration: none" href="https://www.researchgate.net/profile/Jimmy_John_Hoste" target="_blank">
    <span class="fa-stack" aria-hidden="true">
      <i class="fab fa-researchgate fa-stack-2x" style='color:#00D0AF'></i>
    </span>
    <span class="sr-only">ResearchGate</span>
  </a> &nbsp; **Dr Jimmy-John O.E. Hoste**, Aerothermodynamics Engineer at [Destinus](https://destinus.ch), Vaud, Switzerland
* **Dr Alexey Ryakhovskiy**  
* <a style="text-decoration: none" href="https://de.linkedin.com/in/maximilian-maigler-262bb6114" target="_blank">
    <span class="fa-stack" aria-hidden="true">
      <i class="fas fa-circle fa-stack-2x" style='color:#0072B1'></i>
      <i class="fab fa-linkedin fa-stack-1x fa-inverse"></i>
    </span>
    <span class="sr-only">LinkedIn</span>
  </a> &nbsp; **Maximilian Maigler**, PhD Student at Bundeswehr University Munich  
* <a style="text-decoration: none" href="https://it.linkedin.com/in/valentina-pessina" target="_blank">
    <span class="fa-stack" aria-hidden="true">
      <i class="fas fa-circle fa-stack-2x" style='color:#0072B1'></i>
      <i class="fab fa-linkedin fa-stack-1x fa-inverse"></i>
    </span>
    <span class="sr-only">LinkedIn</span>
  </a> &nbsp; **Valentina Pessina**, Researcher at Bundeswehr University Munich 

_Testers_: 
* <a style="text-decoration: none" href="https://uk.linkedin.com/in/rodrigo-palharini-59316775" target="_blank">
    <span class="fa-stack" aria-hidden="true">
      <i class="fas fa-circle fa-stack-2x" style='color:#0072B1'></i>
      <i class="fab fa-linkedin fa-stack-1x fa-inverse"></i>
    </span>
    <span class="sr-only">LinkedIn</span>
  </a> <a style="text-decoration: none" href="https://www.researchgate.net/profile/Rodrigo_Palharini" target="_blank">
    <span class="fa-stack" aria-hidden="true">
      <i class="fab fa-researchgate fa-stack-2x" style='color:#00D0AF'></i>
    </span>
    <span class="sr-only">ResearchGate</span>
  </a> &nbsp; **Dr Rodrigo C. Palharini**, Lecturer in Fluid Mechanics at [Universidad Técnica Federico de Santa María](http://www.mecanica.usm.cl/), Santiago, Chile

_Advisers_: 
* <a style="text-decoration: none" href="https://www.researchgate.net/profile/Thomas_Scanlon" target="_blank">
    <span class="fa-stack" aria-hidden="true">
      <i class="fab fa-researchgate fa-stack-2x" style='color:#00D0AF'></i>
    </span>
    <span class="sr-only">ResearchGate</span>
  </a> &nbsp; **Dr Thomas J. Scanlon** BEng PhD CEng MIMechE, Lead Consultant at [MTS-CFD](https://www.mts-cfd.com/), Glasgow, UK
* <a style="text-decoration: none" href="https://uk.linkedin.com/in/richard-brown-05520726" target="_blank">
    <span class="fa-stack" aria-hidden="true">
      <i class="fas fa-circle fa-stack-2x" style='color:#0072B1'></i>
      <i class="fab fa-linkedin fa-stack-1x fa-inverse"></i>
    </span>
    <span class="sr-only">LinkedIn</span>
  </a> &nbsp; **Dr Richard E. Brown** CEng FIMechE FRAeS, Specialist Mathematical Modeller at [Sophrodyne Ltd](http://www.sophrodyne.com/), Glasgow, UK  


<br>

---
## Ablation module &nbsp;—&nbsp; __*ARC*__ (not released)
_Lead developer_: 
* <a style="text-decoration: none" href="https://uk.linkedin.com/in/viola-renato-bbbb18102" target="_blank">
    <span class="fa-stack" aria-hidden="true">
      <i class="fas fa-circle fa-stack-2x" style='color:#0072B1'></i>
      <i class="fab fa-linkedin fa-stack-1x fa-inverse"></i>
    </span>
    <span class="sr-only">LinkedIn</span>
  </a> &nbsp; **Dr Viola Renato**  
  
_Advisers_: 
* **Dr Thomas J. Scanlon**  
* **Dr Richard E. Brown**

<br> 

---   
## DSMC module &nbsp;—&nbsp; __*dsmcFoam+*__        
_Current developers_: 
* **Dr Vincent Casseau**
* **Dr Daniel E.R. Espinoza**  
* **Tim Teichmann**, PhD student in the [Institute for Technical Physics](http://www.itep.kit.edu/english/), Karlsruhe Institute of Technology (KIT), Eggenstein-Leopoldshafen, Germany  
* <a style="text-decoration: none" href="https://uk.linkedin.com/in/craig-white-53b70387" target="_blank">
    <span class="fa-stack" aria-hidden="true">
      <i class="fas fa-circle fa-stack-2x" style='color:#0072B1'></i>
      <i class="fab fa-linkedin fa-stack-1x fa-inverse"></i>
    </span>
    <span class="sr-only">LinkedIn</span>
  </a> &nbsp; **Dr Craig White**, Lecturer in Aerospace Sciences at the [University of Glasgow](https://www.gla.ac.uk/schools/engineering/staff/craigwhite/), Glasgow, UK
* **Maximilian Maigler**  
* **Valentina Pessina**  
 
 
_Past contributors_:  
* **Dr Rodrigo C. Palharini**  
* **Dr Thomas J. Scanlon**  
* **Dr Richard E. Brown**  
* **All contributors to the *dsmcFoam* solver in the official OpenFOAM release** 

<br>

---
## Hybrid modules &nbsp;—&nbsp; __*hyperFoam*__, __*pdFoam*__  
&nbsp;

#### CFD-DSMC (not released yet)
_Lead developer_:  
* **Dr Daniel E.R. Espinoza** 

_Contributor_:  
* **Dr Vincent Casseau**  

_Advisers_:    
* **Dr Thomas J. Scanlon**  
* **Dr Richard E. Brown** 

&nbsp;

#### PIC-DSMC  
_Lead developer_:  
* <a style="text-decoration: none" href="https://uk.linkedin.com/in/c-capon" target="_blank">
    <span class="fa-stack" aria-hidden="true">
      <i class="fas fa-circle fa-stack-2x" style='color:#0072B1'></i>
      <i class="fab fa-linkedin fa-stack-1x fa-inverse"></i>
    </span>
    <span class="sr-only">LinkedIn</span>
  </a> &nbsp; **Dr Christopher J. Capon**, CEO at [Nominal Systems](https://www.nominalsys.com/) & Research Fellow at [UNSW Canberra Space](https://www.unsw.adfa.edu.au/space-research/mr-christopher-capon), Canberra, Australia

_Code integration_:  
* **Dr Vincent Casseau**  

_Advisors_:  
* **Prof Russell R. Boyce**, Chair for Space Engineering at [UNSW Canberra Space](https://research.unsw.edu.au/people/professor-russell-robert-boyce), Canberra, Australia  
* **Dr Melrose Brown**, Lecturer at [UNSW Canberra Space](https://www.unsw.adfa.edu.au/space-research/dr-melrose-brown), Canberra, Australia    
* **Dr Craig White**  
* **Dr Thomas J. Scanlon**  
* **Dr Richard E. Brown**
