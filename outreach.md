---
layout: page
title: Outreach 
subtitle: Science is for everyone
---

<div id="slideshow" style="max-width:600px; margin:auto;">
  <img src="/assets/img/outreach1.jpg" style="width:100%; display:none;">
  <img src="/assets/img/outreach2.jpg" style="width:100%; display:none;">
  <img src="/assets/img/outreach3.jpg" style="width:100%; display:none;">
  <img src="/assets/img/outreach4.jpg" style="width:100%; display:none;">
  <img src="/assets/img/outreach5.jpg" style="width:100%; display:none;">
  <img src="/assets/img/outreach6.jpg" style="width:100%; display:none;">
  <img src="/assets/img/outreach7.jpg" style="width:100%; display:none;">
  <img src="/assets/img/outreach8.jpg" style="width:100%; display:none;">
  <img src="/assets/img/outreach9.jpg" style="width:100%; display:none;">
  <img src="/assets/img/outreach10.jpg" style="width:100%; display:none;">
  <img src="/assets/img/outreach11.jpg" style="width:100%; display:none;">
</div>

<script>
  let slideIndex = 0;
  const slides = document.querySelectorAll("#slideshow img");

  function showSlides() {
    for (let i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";
    }
    slideIndex++;
    if (slideIndex > slides.length) { slideIndex = 1; }
    slides[slideIndex - 1].style.display = "block";
    setTimeout(showSlides, 3000);
  }

  document.addEventListener("DOMContentLoaded", showSlides);
</script>
