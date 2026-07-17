---
layout: about
title: about
permalink: /
subtitle: Software Engineer II at AIT Inc | B.Sc. in CSTE, Noakhali Science & Technology University

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false
  more_info: >
    <p>Dhaka, Bangladesh</p>
    <p>minhazul.abedin.se@gmail.com</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # disabled news list

latest_posts:
  enabled: false # disabled blog posts list
---

### Biography

I am a Software Engineer II at [AIT Inc](https://www.ait.inc) with over 3.5 years of experience designing, developing, and maintaining enterprise-grade backend systems. I specialize in the .NET ecosystem (C#, ASP.NET Core, microservices) and integrating AI-driven automation workflows (LLMs, similarity search, database integrations).

I hold a Bachelor of Science in Computer Science and Telecommunication Engineering from [Noakhali Science and Technology University](https://nstu.edu.bd) (NSTU), graduating as 6th in my class (Top 11% of the cohort). Alongside engineering, I am passionate about research in machine learning and data mining. My academic works include publications on data mining blood donor registries, Sufi music attitudes, and real-time face mask detection systems.

My professional work bridges robust software engineering and practical AI solutions, ranging from adaptive streaming services and microservice payment solutions to GPT-powered budget forecasting tools that save hours of human labor daily.

### Key Achievements

<div class="slideshow-container" style="position: relative; width: 100%; height: 340px; overflow: hidden; border-radius: 8px; box-shadow: 0 4px 6px -1px rgba(0,0,0,0.1); border: 1px solid var(--global-divider-color); margin-top: 1.5rem; margin-bottom: 2rem;">
  
  <!-- Slide 1 -->
  <div class="mySlides" style="display: block; width: 100%; height: 100%; position: relative;">
    <img src="{{ '/assets/img/1.jpg' | relative_url }}" style="width:100%; height:100%; object-fit: cover; opacity: 0.35; filter: brightness(0.65);">
    <div class="text-block" style="position: absolute; bottom: 20px; left: 20px; right: 20px; background: rgba(0, 0, 0, 0.65); color: white; padding: 15px; border-radius: 6px;">
      <h4 style="margin: 0 0 5px 0; font-weight: bold; color: white;">Best Project Award</h4>
      <p style="margin: 0; font-size: 0.9rem;">Awarded at AIT Inc in Audit Week (Feb 2025) for high-impact system module design and AI optimization.</p>
    </div>
  </div>

  <!-- Slide 2 -->
  <div class="mySlides" style="display: none; width: 100%; height: 100%; position: relative;">
    <img src="{{ '/assets/img/2.jpg' | relative_url }}" style="width:100%; height:100%; object-fit: cover; opacity: 0.35; filter: brightness(0.65);">
    <div class="text-block" style="position: absolute; bottom: 20px; left: 20px; right: 20px; background: rgba(0, 0, 0, 0.65); color: white; padding: 15px; border-radius: 6px;">
      <h4 style="margin: 0 0 5px 0; font-weight: bold; color: white;">NSTU Academic Scholar</h4>
      <p style="margin: 0; font-size: 0.9rem;">Awarded the Department Scholarship for Outstanding Academic Performance four times (2017 - 2022).</p>
    </div>
  </div>

  <!-- Slide 3 -->
  <div class="mySlides" style="display: none; width: 100%; height: 100%; position: relative;">
    <img src="{{ '/assets/img/3.jpg' | relative_url }}" style="width:100%; height:100%; object-fit: cover; opacity: 0.35; filter: brightness(0.65);">
    <div class="text-block" style="position: absolute; bottom: 20px; left: 20px; right: 20px; background: rgba(0, 0, 0, 0.65); color: white; padding: 15px; border-radius: 6px;">
      <h4 style="margin: 0 0 5px 0; font-weight: bold; color: white;">3rd Place, Programming Contest</h4>
      <p style="margin: 0; font-size: 0.9rem;">Placed 3rd in the Intra-departmental Programming Contest (2018) for algorithmic speed and accuracy.</p>
    </div>
  </div>

  <!-- Slide 4 -->
  <div class="mySlides" style="display: none; width: 100%; height: 100%; position: relative;">
    <img src="{{ '/assets/img/4.jpg' | relative_url }}" style="width:100%; height:100%; object-fit: cover; opacity: 0.35; filter: brightness(0.65);">
    <div class="text-block" style="position: absolute; bottom: 20px; left: 20px; right: 20px; background: rgba(0, 0, 0, 0.65); color: white; padding: 15px; border-radius: 6px;">
      <h4 style="margin: 0 0 5px 0; font-weight: bold; color: white;">AI & Deep Learning Certifications</h4>
      <p style="margin: 0; font-size: 0.9rem;">AI Engineer Core Track, Deep Learning Specialization, and Applied ML in Python certifications.</p>
    </div>
  </div>

  <!-- Slide 5 -->
  <div class="mySlides" style="display: none; width: 100%; height: 100%; position: relative;">
    <img src="{{ '/assets/img/5.jpg' | relative_url }}" style="width:100%; height:100%; object-fit: cover; opacity: 0.35; filter: brightness(0.65);">
    <div class="text-block" style="position: absolute; bottom: 20px; left: 20px; right: 20px; background: rgba(0, 0, 0, 0.65); color: white; padding: 15px; border-radius: 6px;">
      <h4 style="margin: 0 0 5px 0; font-weight: bold; color: white;">Board Merit Scholarship</h4>
      <p style="margin: 0; font-size: 0.9rem;">Awarded Board Merit Scholarship in 2011 for outstanding secondary school results.</p>
    </div>
  </div>

  <!-- Next and previous buttons -->
  <a class="prev" onclick="plusSlides(-1)" style="cursor: pointer; position: absolute; top: 50%; width: auto; margin-top: -22px; padding: 16px; color: white; font-weight: bold; font-size: 18px; transition: 0.6s ease; border-radius: 0 3px 3px 0; user-select: none; left: 0;">&#10094;</a>
  <a class="next" onclick="plusSlides(1)" style="cursor: pointer; position: absolute; top: 50%; width: auto; margin-top: -22px; padding: 16px; color: white; font-weight: bold; font-size: 18px; transition: 0.6s ease; border-radius: 3px 0 0 3px; user-select: none; right: 0;">&#10095;</a>
</div>

<script>
  let slideIndex = 0;
  let slideTimer;
  showSlides();

  // Next/previous controls
  function plusSlides(n) {
    clearTimeout(slideTimer);
    showSlidesManual(slideIndex += n);
  }

  function showSlides() {
    let i;
    let slides = document.getElementsByClassName("mySlides");
    for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";
    }
    slideIndex++;
    if (slideIndex > slides.length) {slideIndex = 1}
    slides[slideIndex-1].style.display = "block";
    slideTimer = setTimeout(showSlides, 4000); // Change image every 4 seconds
  }

  function showSlidesManual(n) {
    let i;
    let slides = document.getElementsByClassName("mySlides");
    if (n > slides.length) {slideIndex = 1}
    if (n < 1) {slideIndex = slides.length}
    for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";
    }
    slides[slideIndex-1].style.display = "block";
    // Restart automatic timer
    slideTimer = setTimeout(showSlides, 4000);
  }
</script>
