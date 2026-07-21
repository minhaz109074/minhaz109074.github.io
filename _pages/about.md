---
layout: about
title: About
permalink: /
subtitle: Software Engineer | AI/ML Researcher

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

I am a Software Engineer with over 3.5 years of experience, currently working at [AIT Inc](https://www.ait.inc), one of Bangladesh's leading software companies, headquartered in the USA, serving clients across the USA and Australia. I have experience building scalable backend systems following industry-standard architecture and best practices.

I have hands-on experience integrating AI into production systems — for instance, I led the integration of an LLM-based automation pipeline into a budget forecasting platform, where manual data preparation was a major bottleneck for users. By automating this process, I reduced preparation time by over 90%, directly solving a recurring pain point for the users. In addition, I have experience building reel-like short-video features for a social media platform, using adaptive streaming technology, video transcoding, and a video recommendation engine. For this, I used vector similarity search, LLM integration, and a video-tagging pipeline that selects representative frames from long videos and feeds them into an LLM for semantic tagging, along with embedding generation using local LLMs.

My current research interest focuses on agentic automation to improve reliability and efficiency in real-world software systems. In addition, I am interested in computer vision and multimodal AI, particularly video-language understanding — how models can reason jointly over visual and textual signals for tasks like retrieval, tagging, and summarization. As a software engineer at heart, I care less about AI as an isolated research artifact and more about how it performs once it's under real engineering constraints — latency, scale, reliability.

I am open to collaborating and discussing any exciting research that can help solve real human pain points. Feel free to reach out!

### Key Achievements

<style>
  .slideshow-container {
    position: relative;
    width: 100%;
    height: clamp(14rem, 45vw, 21.25rem);
    overflow: hidden;
    border-radius: 0.5rem;
    box-shadow: 0 0.25rem 0.375rem -0.0625rem rgba(0,0,0,0.1);
    border: 0.0625rem solid var(--global-divider-color);
    margin-top: 1.5rem;
    margin-bottom: 2rem;
  }

  .slideshow-container .mySlides {
    display: none;
    width: 100%;
    height: 100%;
  }

  .slideshow-container .mySlides img {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }

  .slideshow-prev,
  .slideshow-next {
    cursor: pointer;
    position: absolute;
    top: 50%;
    margin-top: -1.125rem;
    padding: 0.75rem 1rem;
    color: #fff;
    font-weight: bold;
    font-size: 1.125rem;
    transition: 0.6s ease;
    user-select: none;
    border-radius: 0 0.1875rem 0.1875rem 0;
    text-decoration: none;
  }

  .slideshow-next {
    right: 0;
    border-radius: 0.1875rem 0 0 0.1875rem;
  }

  .slideshow-prev {
    left: 0;
  }

  .slideshow-prev:hover,
  .slideshow-next:hover {
    background: rgba(0,0,0,0.8);
  }

  @media (max-width: 48rem) {
    .slideshow-container {
      height: clamp(10rem, 40vw, 16rem);
    }

    .slideshow-prev,
    .slideshow-next {
      padding: 0.5rem 0.75rem;
      font-size: 0.875rem;
      margin-top: -0.875rem;
    }
  }

  @media (max-width: 30rem) {
    .slideshow-container {
      height: clamp(8rem, 50vw, 12rem);
    }
  }

  .post-title {
    font-weight: 700;
    font-size: 2.75rem;
  }

  @media (max-width: 48rem) {
    .post-title {
      font-size: 2.25rem;
    }
  }
</style>

<div class="slideshow-container">
  
  <div class="mySlides" style="display: block;">
    <img src="{{ '/assets/img/achievements/01.jpg' | relative_url }}" alt="AIT Agile Transformation Workshop">
  </div>

  <div class="mySlides">
    <img src="{{ '/assets/img/achievements/02.jpg' | relative_url }}" alt="Best Project Award">
  </div>

  <div class="mySlides">
    <img src="{{ '/assets/img/achievements/03.jpg' | relative_url }}" alt="3rd Work Anniversary">
  </div>

  <div class="mySlides">
    <img src="{{ '/assets/img/achievements/04.jpg' | relative_url }}" alt="ICMTBI 2021 Certificate">
  </div>

  <div class="mySlides">
    <img src="{{ '/assets/img/achievements/05.jpg' | relative_url }}" alt="BDML Workshop">
  </div>

  <a class="slideshow-prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="slideshow-next" onclick="plusSlides(1)">&#10095;</a>
</div>

<script>
  let slideIndex = 0;
  let slideTimer;
  showSlides();

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
    slideTimer = setTimeout(showSlides, 4000);
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
    slideTimer = setTimeout(showSlides, 4000);
  }
</script>
