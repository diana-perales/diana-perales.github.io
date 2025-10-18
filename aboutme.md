---
layout: page
title: About me
subtitle: Stories of a parasitologist
---

<p style="text-align:center;">My name is Diana M. B. Perales Macedo.</p>

<p style="text-align:center;">If you explore fecal matter in a microscope (with the guidance of a veterinarian!) you might also stumble into the world of parasites!</p> 


<div id="slideshow" style="max-width:600px; margin:auto;">
  <img src="/assets/img/field1.jpg" style="width:100%; display:none;">
  <img src="/assets/img/field2.jpg" style="width:100%; display:none;">
  <img src="/assets/img/field3.jpg" style="width:100%; display:none;">
  <img src="/assets/img/field4.jpg" style="width:100%; display:none;">
  <img src="/assets/img/field5.jpg" style="width:100%; display:none;">
  <img src="/assets/img/field6.jpg" style="width:100%; display:none;">
  <img src="/assets/img/field7.jpg" style="width:100%; display:none;">
  <img src="/assets/img/field8.jpg" style="width:100%; display:none;">
  <img src="/assets/img/fieldh9.jpg" style="width:100%; display:none;">
  <img src="/assets/img/field10.jpg" style="width:100%; display:none;">
  <img src="/assets/img/field11.jpg" style="width:100%; display:none;">
  <img src="/assets/img/field12.jpg" style="width:100%; display:none;">
  <img src="/assets/img/fieldh13.jpg" style="width:100%; display:none;">
  <img src="/assets/img/field14.jpg" style="width:100%; display:none;">
  <img src="/assets/img/field15.jpg" style="width:100%; display:none;">
  <img src="/assets/img/field16.jpg" style="width:100%; display:none;">
  <img src="/assets/img/fieldh17.jpg" style="width:100%; display:none;">
  <img src="/assets/img/field18.jpg" style="width:100%; display:none;">
  <img src="/assets/img/field19.jpg" style="width:100%; display:none;">
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

<div style="background-color:#f9f9f9; padding:20px; border-radius:8px; margin-bottom:20px;">
  <h3>How It Started</h3>
     My interest in parasitology began during my time as a volunteer at the Villa Michelle Animal Shelter in Mayagüez, Puerto Rico, where I assisted the on-site veterinarian. There, I was first exposed to parasites such as nematodes, sparking my curiosity about host-parasite interactions. What truly solidified my passion was reaching out to the parasitologist at my university (UPRM) to pursue a hands-on research opportunity. That decision led me to Dr. Sean Locke, whose mentorship introduced me to the world of parasitology. 

</div>

<div style="background-color:#6FA89F; padding:20px; border-radius:8px; margin-bottom:20px;">
  <h3>Current goals</h3>
     I am currently a graduate student at the University of Washington, Seattle, specializing in ecological parasitology. Under the mentorship of Dr. Chelsea Wood, my research focuses on tracking trends in trematode and other metazoan parasite populations to understand how they respond to ecological variables such as temperature, predator presence, and time. This work involves both field collections and the analysis of historical data from museum specimens. I use a combination of morphological analysis and genetic sequencing to identify parasites to the lowest taxonomic level. 

</div>

<div style="background-color:#6DA4B3; padding:20px; border-radius:8px; margin-bottom:20px;">
  <h3>Long term goals</h3>
   I'm especially passionate about gaining hands-on research experience in ecology and freshwater sciences, as part of my path toward a Ph.D. in the School of Aquatic and Fisheries Sciences at UW. Ultimately, my goal is to contribute to a deeper understanding of complex ecological systems and the often-overlooked role parasites play within them. 

</div>

<!-- Second carousel -->
<div id="slide" style="max-width:600px; margin:auto;">
  <img src="/assets/img/story1.jpg" style="width:100%; display:none;">
  <img src="/assets/img/story2.jpg" style="width:100%; display:none;">
</div>

<script>
  let storyIndex = 0;
  const storySlides = document.querySelectorAll("#slide img");

  function showStory() {
    for (let i = 0; i < storySlides.length; i++) {
      storySlides[i].style.display = "none";
    }
    storyIndex++;
    if (storyIndex > storySlides.length) { storyIndex = 1; }
    storySlides[storyIndex - 1].style.display = "block";
    setTimeout(showStory, 3000);
  }

  // Start both carousels
  document.addEventListener("DOMContentLoaded", function () {
    showSlideshow();
    showStory();
  });
</script>

<div style="background-color:#f9f9f9; padding:20px; border-radius:8px; margin-bottom:20px;">
  <h3>My story</h3>
  My earliest photos capture the international friendships my parents made in Sendai, Japan, where my father was completing his PhD. When I was around three years old, we moved to Peru. Although we stayed there for less than a year, it was a meaningful time in which I connected with my Peruvian roots, learning about the culture, food, family, and the vibrant, bustling life of Lima. 

   Later, after my father accepted a professorship at the University of Puerto Rico, our family moved once again, this time to the beautiful island of Puerto Rico, where I lived until I completed my master’s degree at UPRM. While I proudly recognize my Peruvian heritage, I also strongly identify with Puerto Rican culture. Life here is full of beauty and unpredictability; our summers are marked by both sunshine and natural disasters, making each year an unforgettable experience.  <p>
