---
permalink: /venue/
title: "Venue"
---
<html>
<head>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.buttonload {
  background-color: #faebd7; 
  border: none; /* Remove borders */
  color: black;
  padding: 12px 24px; /* Some padding */
  font-size: 16px; /* Set a font-size */
}

/* Add a right margin to each icon */
.fa {
  margin-left: -12px;
  margin-right: 8px;
}
</style>
</head>
<body>

<button class="buttonload">
  <i class="fa fa-circle-o-notch fa-spin"></i>Coming Soon...
</button>


George Fox building
<style>
* {box-sizing: border-box;}
body {font-family: 'Candara';}
.mySlides {display: none;}
img {vertical-align: middle;}


/* Slideshow container */
.slideshow-container {
  max-width: 600px;
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
  color: #2f2c2c;
  font-size: 8px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  height: 8px;
  width: 8px;
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
  animation-name: fade;
  animation-duration: 3600s;
}

@keyframes fade {
  from {opacity: .8} 
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 400px) {
  .text {font-size: 10px}
}
</style>
</head>
<body>

<!-- <h2>Automatic Slideshow</h2>
<p>Change image every 2 seconds:</p> -->

<div class="slideshow-container">

<div class="mySlides fade">
    <div class="numbertext">1 / 3</div>
    <img src="/assets/images/venue_1.jpg" style="width:100%">
    <div class="text">George Fox</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">2 / 3</div>
  <img src="/assets/images/venue_2.jpg" style="width:100%">
  <div class="text">George Fox</div>
</div>

<div class="mySlides fade">
  <div class="number text">3 / 3</div>
  <img src="/assets/images/venue_2.jpg" style="width:100%">
  <div class="text">George Fox</div>
</div>

</div>
<br>

<div style="text-align:center">
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
</div>

<script>
let slideIndex = 0;
showSlides();

function showSlides() {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  let dots = document.getElementsByClassName("dot");
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



</body>
</html>
