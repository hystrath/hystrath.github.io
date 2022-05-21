---
layout: home
title: hyStrath
subtitle: the hypersonic valley
nav-short: true
---

<p>
The <i>hyStrath</i> GitHub repository is featuring hypersonic and rarefied gas dynamics code developments released under license GPL-3.0. It is the only platform to conjointly host open-source CFD and DSMC codes designed for atmospheric entry analysis.
</p>

<p>
The platform is meant to be collaborative: if you would like to <a href="https://hystrath.github.io/contributions/">contribute</a>, use it for educational purposes or need support in the form of consulting services, please <a href="https://hystrath.github.io/contact">get in touch</a>. 
</p>

<br>

 <!-- Slideshow container -->
<div class="slideshow-container">

  <!-- Full-width images with number and caption text -->
  <div class="hyStrathSlides">
    <div class="solvernametext">rhoCentralFoam</div>
    <img src="/docs/img/gallery/Espinoza15-SodShockTube.png" style="width:100%">
    <div class="text">Espinoza et al. (2015) - Sod shock tube simulation with Adaptive Mesh Refinement (AMR)</div>
  </div>

  <div class="hyStrathSlides">
    <div class="solvernametext">pdFoam</div>
    <img src="/docs/img/gallery/Capon17-TempContours.png" style="height:350px">
    <div class="text">Capon et al. (2017) - Mach 10 flow of Argon around a 2-D cylinder</div>
  </div>

  <div class="hyStrathSlides">
    <div class="solvernametext">pdFoam</div>
    <img src="/docs/img/gallery/Capon17-PotentialEnergyContours.png" style="height:350px">
    <div class="text">Capon et al. (2017) - Ion Orbital Motion Structures in LEO</div>
  </div>
  
  <div class="hyStrathSlides">
    <div class="solvernametext">hy2Foam</div>
    <img src="/docs/img/gallery/Casseau16-Mach20NitrogenCylinder.png" style="height:325px">
    <div class="text">Casseau et al. (2016) - Mach 20 flow of Nitrogen around a 2-D cylinder</div>
  </div>
  
  <div class="hyStrathSlides">
    <div class="solvernametext">hyFoam</div>
    <img src="/docs/img/gallery/Hoste17-LorrainsScramjet.png" style="height:350px">
    <div class="text">Hoste et al. (2017) - Experimental Schlieren and CFD results for Lorrain's Scramjet</div>
  </div>
  
  <div class="hyStrathSlides">
    <div class="solvernametext">hyFoam</div>
    <img src="/docs/img/gallery/Hoste17-LorrainsScramjetCp.png" style="height:350px">
    <div class="text">Hoste et al. (2017) - Pressure coefficient for Lorrain's Scramjet, fuel-off conditions</div>
  </div>
  
  <div class="hyStrathSlides">
    <div class="solvernametext">ARC</div>
    <img src="/docs/img/gallery/Renato17-PathfinderMesh.png" style="height:325px">
    <div class="text">Renato and Scanlon (2017) - 3-D ablation and thermal response for the Pathfinder capsule</div>
  </div>
  
  <div class="hyStrathSlides">
    <div class="solvernametext">ARC</div>
    <img src="/docs/img/gallery/Renato17-PathfinderHeatFlux.png" style="height:300px">
    <div class="text">Renato and Scanlon (2017) - 3-D ablation and thermal response for the Pathfinder capsule</div>
  </div>
  
  <div class="hyStrathSlides">
    <div class="solvernametext">dsmcFoam+</div>
    <img src="/docs/img/gallery/Casseau18-PorousMedia.png" style="height:350px">
    <div class="text">Casseau and White (2018) - Porous media generation</div>
  </div>
  
  <div class="hyStrathSlides">
    <div class="solvernametext">dsmcFoam+</div>
    <div class="row">
      <div class="column">
        <img src="/docs/img/gallery/Casseau18-PorousMediaPlot.png" style="height:275px">
      </div>
      <div class="column">
        <img src="/docs/img/gallery/Casseau18-PorousMediaDeff.png" style="height:275px">
      </div>
    </div>
    <div class="text">Casseau and White (2018) - Porous media generation</div>
  </div>
  
  <div class="hyStrathSlides">
    <div class="solvernametext">hyFoam</div>
    <div class="row">
      <div class="column">
        <img src="/docs/img/gallery/Hoste21-HB2FlareGeometry.png" style="height:150px">
      </div>
      <div class="column">
        <img src="/docs/img/gallery/Hoste21-HB2FlareHeatflux.png" style="height:275px">
      </div>
    </div>
    <div class="text">Hoste and Casseau (2021) - HB-2 flare simulation</div>
  </div>

  <!-- Next and previous buttons -->
  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>
</div>

<br>

<!-- The dots/circles -->
<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span>
  <span class="dot" onclick="currentSlide(2)"></span>
  <span class="dot" onclick="currentSlide(3)"></span>
  <span class="dot" onclick="currentSlide(4)"></span>
  <span class="dot" onclick="currentSlide(5)"></span>
  <span class="dot" onclick="currentSlide(6)"></span>
  <span class="dot" onclick="currentSlide(7)"></span>
  <span class="dot" onclick="currentSlide(8)"></span>
  <span class="dot" onclick="currentSlide(9)"></span>
  <span class="dot" onclick="currentSlide(10)"></span>
  <span class="dot" onclick="currentSlide(11)"></span>
</div> 



<script>
let slideIndex = 1;
showSlides(slideIndex);

<!-- Next/previous controls-->
function plusSlides(n) {
  showSlides(slideIndex += n);
}

<!--Thumbnail image controls-->
function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  let i;
  let slides = document.getElementsByClassName("hyStrathSlides");
  let dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";
  }
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";
  dots[slideIndex-1].className += " active";
} 
</script>
