---
layout: page
title: Home
---

<style>


/* Slideshow container */
.slideshow-container {
  max-width: 1200px;
  position: relative;
  margin: auto;
}

/* Caption text */
.text {
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active {
  background-color: #717171;
}

/* Fading animation */
.fade {
  -webkit-animation-name: fade;
  -webkit-animation-duration: 1.5s;
  animation-name: fade;
  animation-duration: 1.5s;
}

.slidebox {
  width:1200px; 
  height: 400px;
}

@media only screen and (max-width: 800px;) {
  .slidesbox {
    max-width: 600px;
    max-height: 200px;
  }

@-webkit-keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 800px;) {
  .text {font-size: 11px}
}


}
</style>


<div class="slideshow-container">

<div class="mySlides fade">
  <img src="/img/Quantum_Computing.jpg" class="">
</div>

<div class="mySlides fade">
  <img src="/img/IISc_building.jpg" class= "">
</div>

<div class="mySlides fade">
  <img src="/img/q1.jpg" class = "" >
</div>
<div class="mySlides fade">
  <img src="/img/qbit.jpeg" class ="">
</div>

<div class="mySlides fade">
  <img src="/img/singlephoton.png" class ="">
</div>

<div class="mySlides fade">
  <img src="/img/QP.png" class="">
</div>

</div>
<br>

<div style="text-align:center">
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 

</div>

<script>
var slideIndex = 0;
showSlides();

function showSlides() {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("dot");
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }
  slideIndex++;
  if (slideIndex > slides.length) {slideIndex = 1}    
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
  setTimeout(showSlides, 2000); // Change image every 2 seconds
}
</script>

<br>
<br>
<h2>Initiative on Quantum Technology (IQT@IISc)</h2>
<h3 style="color: #bb9065">The Initiative:</h3>
<p>The Indian Institute of Science (IISc) has been declared an Institute of Eminence (IOE) by the Government of India in July 2018. One of the cutting-edge research areas that IISc seeks to explore seriously under IOE is the field of “Quantum Technology.” IISc has several faculty members, in physics, engineering, and computer science, who have started working together on such technologies.</p>
<h3 style="color: #bb9065">Background:</h3>
<p>The field of quantum technology is poised for significant breakthroughs in the coming years. The essential features that contribute to these technologies are superposition, entanglement, squeezing and tunneling of quantum states. Practical applications are expected to appear first in sensing and metrology, then in communications and simulations, then as feedback to foundations of quantum theory, and ultimately in quantum computing. The field is multi-disciplinary, combining physics+computer science on the theoretical side, and physics+engineering on the experimental side.</p>
<p>Compared to the world-wide development, the existing expertise and facilities available in India are limited on the theoretical side and severely lacking on the experimental side. To build up the field of quantum technologies from this stage, even in carefully selected areas, is a significant challenge. IISc plans to bring the Indian pursuit in this field on par with the rest of the world, with a dedicated and focused effort.</p>
<h3 style="color: #bb9065">Structure of the Research Centre:</h3>
<p>A worthwhile effort in this high-risk-high-reward field has to blend both concrete deliverables and open-ended research investigations. Also, simultaneous explorations of competing technologies must complement each other, by contrasting their advantages and limitations. To make the best use of the available expertise, IISc has put together a structure involving people from different departments.</p>
<p>This centre aims to deliver quantum enhanced technologies. Its experimental program will focus on superconducting qubit devices, single photon sources and detectors for quantum communications, integrated photonic quantum networks, and quantum sensors. It will benefit from the dedicated national nano-fabrication facility at IISc. The theoretical effort will certainly support the experimental program, while being broad-based enough to explore other open areas in this rapidly advancing field, in particular quantum algorithms and simulations, and post-quantum cryptography. The developments in quantum technologies will also push classical technologies in new directions.</p>

<h3 style="color: #bb9065">Funding Support:</h3>

<img src="/img/MEIT.png" style="width: 200px; height: 90px; margin-left:80px;"> 

<style>

.column {
  float: left;
  width: 20%;
  padding: 10px;
  margin-left: 70px
}

/* Clearfix (clear floats) */
.row::after {
  content: "";
  clear: both;
  display: table;
}
</style>

<h3 style="color: #bb9065"> Partner Institutes: </h3>
<div class = "row">
  <div class = "column">
        <a href="http://www.rri.res.in/"><img src="/img/RRI_Logo.png" style="width: 90px; height: 150px; "></a>
  </div>
  <div class = "column">
        <a href="https://www.cdac.in/index.aspx?id=bangalore"><img src="/img/CDAC_Logo.png"></a>
  </div>
</div>
