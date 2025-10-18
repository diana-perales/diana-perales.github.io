<div id="slideshow" style="max-width:600px; margin:auto;">
  <img src="/assets/img/outreach.jpg" style="width:100%; display:none;">
  <img src="/assets/img/outreach2.jpg" style="width:100%; display:none;">
  <img src="/assets/img/outreach3.jpg" style="width:100%; display:none;">
  <img src="/assets/img/outreach4.jpg" style="width:100%; display:none;">
  <img src="/assets/img/outreach5.jpg" style="width:100%; display:none;">
  <img src="/assets/img/outreach6.jpg" style="width:100%; display:none;">
  <img src="/assets/img/outreach7.jpg" style="width:100%; display:none;">
  <img src="/assets/img/outreach8.jpg" style="width:100%; display:none;">
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
