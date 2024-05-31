---
permalink: /venue/
---
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
<meta name='viewport' content='width=device-width, initial-scale=1'>
<script src='https://kit.fontawesome.com/a076d05399.js' crossorigin='anonymous'></script>
<style>
body {
    font-family: Times New Roman;
} 
* {
  box-sizing: border-box;
}
.header {
  text-align: center;
  padding: 32px;
}
.row {
  display: -ms-flexbox; /* IE10 */
  display: flex;
  -ms-flex-wrap: wrap; /* IE10 */
  flex-wrap: wrap;
  padding: 0 4px;
}
.header {
  text-align: center;
  padding: 32px;
}
.row {
  display: -ms-flexbox; /* IE10 */
  display: flex;
  -ms-flex-wrap: wrap; /* IE10 */
  flex-wrap: wrap;
  padding: 0 4px;
}
/* Create four equal columns that sits next to each other */
.column {
  -ms-flex: 25%; /* IE10 */
  flex: 25%;
  max-width: 25%;
  padding: 0 4px;
}
.column img {
  margin-top: 8px;
  vertical-align: middle;
  width: 100%;
}
div.scroll-container {
  background-color: white;
  overflow: auto;
  white-space: nowrap;
  padding: 5px;
}
div.scroll-container img {
  padding: 2px;
}
* {box-sizing: border-box;}
body {font-family: Verdana, sans-serif;}
.mySlides {display: none;}
img {vertical-align: middle;}
/* Slideshow container */
.slideshow-container {
  max-width: 1000px;
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
  animation-name: fade;
  animation-duration: 1.5s;
}
@keyframes fade {
  from {opacity: .6} 
  to {opacity: 1}
}
/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .text {font-size: 11px}
}
</style>
</head>
<body>
<br>
<p>Information about travel to the campus is available <a href="https://www.lancaster.ac.uk/sustainability/action/travel/" style="color:DodgerBlue;">here</a>.
</p>

<h1>Lancaster University</h1>

<div class="slideshow-container">

<div class="mySlides fade">
  <img src="/assets/images/university/20240214_194800601_iOS.jpg" width="100%">  
  <div class="text">Library</div>
</div>

<div class="mySlides fade">
  <img src="/assets/images/alex_square/20200530_194450255_iOS.jpeg" width="100%">  
  <div class="text">Outdoors</div>
</div>

<div class="mySlides fade">
  <img src="/assets/images/infolab/20210917_175340223_iOS.jpg" width="100%"> 
  <div class="text">InfoLab21</div>
</div>

<div class="mySlides fade">
   <img src="/assets/images/university/20170501_135102767_iOS.jpg" width="100%">
  <div class="text">Lake Carter Bridge</div>
</div>

<div class="mySlides fade">
    <img src="/assets/images/alex_square/20210205_170511772_iOS.jpeg" width="100%">
  <div class="text">Alexandra Square</div>
</div>
</div>

<br>

<div style="text-align:center">
  <span class="dot"></span> 
  <span class="dot"></span> 
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
  setTimeout(showSlides, 2500); 
}
</script>
<p style="font-family: 'Akaya Telivigala';">Photo Credit: Mo Haj (@melhaj) (<a href="https://www.instagram.com/melhaj/" target="_blank">https://www.instagram.com/melhaj/</a>)</p>

</body>
</html> 
