---
layout: page
title: About me
subtitle: Stories of a parasitologist
---

<style>
  /* Container for flex sections */
  .flex-section {
    display: flex;
    align-items: center;
    justify-content: center;
    max-width: 900px;
    margin: 30px auto;
    gap: 30px;
    flex-wrap: wrap;
  }

  /* Reverse the order (image right, text left) */
  .flex-section.reverse {
    flex-direction: row-reverse;
  }

  /* Text blocks styling */
  .text-block {
    max-width: 480px;
    font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
    font-size: 16px;
    line-height: 1.5;
    padding: 20px;
    border-radius: 8px;
    background-color: #f9f9f9;
  }

  /* Custom background colors for text blocks */
  .text-block.goals {
    background-color: #6FA89F;
    color: white;
  }

  .text-block.longterm {
    background-color: #6DA4B3;
    color: white;
  }

  /* Carousel containers */
  .carousel {
    max-width: 400px;
    flex-shrink: 0;
  }

  .carousel img {
    width: 100%;
    display: none;
    border-radius: 8px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.15);
  }

  /* Italics */
  em {
    font-style: italic;
  }

  /* Header styling */
  h3 {
    margin-top: 0;
  }
</style>

<p style="text-align:center;">Hi! I'm Diana M. B. Perales Macedo.</p>
<p style="text-align:center;">If you explore fecal matter in a microscope (with the guidance of a veterinarian!) you might also stumble into the world of parasites!</p>

<!-- 1st section: Text left, carousel right -->
<div class="flex-section">
  <div id="carousel1" class="carousel">
    <img src="/assets/img/field1.jpg" alt="Field 1">
    <img src="/assets/img/field2.jpg" alt="Field 2">
    <img src="/assets/img/field3.jpg" alt="Field 3">
    <img src="/assets/img/field4.jpg" alt="Field 4">
    <img src="/assets/img/field5.jpg" alt="Field 5">
    <img src="/assets/img/field6.jpg" alt="Field 6">
    <img src="/assets/img/field7.jpg" alt="Field 7">
    <img src="/assets/img/field8.jpg" alt="Field 8">
    <img src="/assets/img/field9.jpg" alt="Field 9">
    <img src="/assets/img/field10.jpg" alt="Field 10">
    <img src="/assets/img/field11.jpg" alt="Field 11">
    <img src="/assets/img/field12.jpg" alt="Field 12">
    <img src="/assets/img/field13.jpg" alt="Field 13">
    <img src="/assets/img/field14.jpg" alt="Field 14">
    <img src="/assets/img/field15.jpg" alt="Field 15">
    <img src="/assets/img/field16.jpg" alt="Field 16">
    <img src="/assets/img/field17.jpg" alt="Field 17">
    <img src="/assets/img/field18.jpg" alt="Field 18">
    <img src="/assets/img/field19.jpg" alt="Field 19">
  </div>

  <div class="text-block">
    <h3>How It Started</h3>
    <p>My interest in parasitology began during my time as a volunteer at the Villa Michelle Animal Shelter in Mayagüez, Puerto Rico, where I assisted the on-site veterinarian. There, I was first exposed to parasites such as nematodes, <em>sparking my curiosity about host-parasite interactions</em>. What truly solidified my passion was reaching out to the parasitologist at my university (UPRM) to pursue a hands-on research opportunity. That decision led me to Dr. Sean Locke, whose mentorship guided me to develop my own <em>undergrad. research on cercariae (baby parasites) from freshwater bodies in Puerto Rico</em>.</p>
  </div>
</div>

<!-- 2nd section: Text left with image left -->
<div class="flex-section reverse">
  <div class="carousel">
    <img src="/assets/img/future1.jpg" alt="future 1" style="display:block;">
  </div>

  <div class="text-block goals">
    <h3>Current goals</h3>
    <p>I am currently a <em>graduate student at the University of Washington</em>, Seattle, specializing in ecological parasitology. Under the mentorship of Dr. Chelsea Wood, my research focuses on tracking trends in trematode and other metazoan parasite populations to understand how they respond to ecological variables such as temperature, predator presence, and time. This work involves both field collections and the analysis of historical data from museum specimens. I use a combination of morphological analysis and genetic sequencing to identify parasites to the lowest taxonomic level.</p>
  </div>
</div>

<!-- 3rd section: Text left, image right -->
<div class="flex-section">
  <div class="carousel">
    <img src="/assets/img/outreach13" alt="outreach 13" style="display:block;">
  </div>

  <div class="text-block longterm">
    <h3>Long term goals</h3>
    <p>I'm especially passionate about gaining <em>hands-on research experience in ecology and freshwater sciences</em>, as part of my path toward a Ph.D. in the School of Aquatic and Fisheries Sciences at UW. Ultimately, my goal is to contribute to a <em>deeper understanding of complex ecological systems while facilitating this information to K-12 students</em>.</p>
  </div>
</div>

<!-- 4th section: Carousel left, text right -->
<div class="flex-section">
  <div id="carousel2" class="carousel">
    <img src="/assets/img/story1.jpg" alt="Story 1">
    <img src="/assets/img/story2.jpg" alt="Story 2">
  </div>

  <div class="text-block">
    <h3>My story</h3>
    <p>My earliest photos capture the international friendships my parents made in Sendai, Japan, where my father was completing his PhD. When I was around three years old, we moved to Peru. Although we stayed there for less than a year, it was a meaningful time in which I connected with my Peruvian roots, learning about the culture, food, family, and the vibrant, bustling life of Lima.</p>
    <p>Later, after my father accepted a professorship at the University of Puerto Rico, our family moved once again, this time to the beautiful island of Puerto Rico, where I lived until I completed my master’s degree at UPRM. While I proudly recognize my Peruvian heritage, I also strongly identify with Puerto Rican culture. Life here is full of beauty and unpredictability; our summers are marked by both sunshine and natural disasters, making each year an unforgettable experience.</p>
  </div>
</div>

<script>
  // Generic carousel function for any carousel container
  function createCarousel(id) {
    let index = 0;
    const slides = document.querySelectorAll(`#${id} img`);

    function showSlide() {
      slides.forEach(img => img.style.display = 'none');
      index++;
      if (index > slides.length) index = 1;
      slides[index - 1].style.display = 'block';
      setTimeout(showSlide, 3000);
    }
    showSlide();
  }

  document.addEventListener("DOMContentLoaded", function() {
    createCarousel("carousel1");
    createCarousel("carousel2");
  });
</script>
