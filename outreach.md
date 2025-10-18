<div id="slideshow" style="max-width:600px; margin:auto;">
  <img src="/assets/images/outreach.jpg" style="width:100%; display:none;">
  <img src="/assets/images/outreach2.jpg" style="width:100%; display:none;">
  <img src="/assets/images/outreach3.jpg" style="width:100%; display:none;">
  <img src="/assets/images/outreach4.jpg" style="width:100%; display:none;">
  <img src="/assets/images/outreach5.jpg" style="width:100%; display:none;">
  <img src="/assets/images/outreach6.jpg" style="width:100%; display:none;">
  <img src="/assets/images/outreach9.jpg" style="width:100%; display:none;">
  <img src="/assets/images/outreach8.jpg" style="width:100%; display:none;">
</div>

<script>
  let slideIndex = 0;
  const slides = document.querySelectorAll("#slideshow img");

  function showSlides() {
    // Hide all slides
    for (let i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";
    }

    // Show the next slide
    slideIndex++;
    if (slideIndex > slides.length) { slideIndex = 1; }
    slides[slideIndex - 1].style.display = "block";

    // Set timer for next slide
    setTimeout(showSlides, 3000); // 3000 ms = 3 seconds
  }

  // Start the slideshow when the page has loaded
  document.addEventListener("DOMContentLoaded", showSlides);
</script>
