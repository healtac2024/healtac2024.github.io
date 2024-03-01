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

<br>
<div class="slideshow-container">

<div class="mySlides fade">
    <div class="numbertext">1 / 3</div>
    <img src="/assets/images/venue_1.jpg" style="width:100%">
    <div class="text">George Fox</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">2 / 3</div>
  <img src="/assets/images/venue_3.jpg" style="width:100%">
  <div class="text">George Fox</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 3</div>
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
<h3>George Fox building</h3>
</body>
</html>
