---
layout: page
permalink: /education/
title: Education
nav: true
nav_order: 4
---

<style>
  .education .edu-card {
    background-color: var(--global-card-bg);
    border-color: var(--global-divider-color);
    box-shadow: 0 0.125rem 0.3125rem 0 rgba(0,0,0,0.16), 0 0.125rem 0.625rem 0 rgba(0,0,0,0.12);
    transition: transform 0.22s ease, box-shadow 0.22s ease;
    border-radius: 0.375rem;
  }

  .education .edu-card:hover {
    transform: translateY(-0.25rem);
    box-shadow: 0 0.625rem 1.375rem rgba(0,0,0,0.12), 0 0.25rem 0.625rem rgba(0,0,0,0.1);
  }

  html[data-theme="dark"] .education .edu-card {
    box-shadow: 0 0.125rem 0.3125rem 0 rgba(0,0,0,0.45), 0 0.625rem 1.25rem 0 rgba(0,0,0,0.4);
  }

  html[data-theme="dark"] .education .edu-card:hover {
    box-shadow: 0 0.625rem 1.375rem rgba(0,0,0,0.45), 0 0.25rem 0.625rem rgba(0,0,0,0.4);
  }

  .education .edu-title {
    color: var(--global-theme-color);
  }

  .education .edu-badge {
    background-color: var(--global-theme-color);
    color: #fff;
    padding: 0.25rem 0.75rem;
    font-weight: 700;
    white-space: nowrap;
    border-radius: 0.25rem;
  }

  .education .edu-link {
    color: var(--global-theme-color);
    text-decoration: none;
  }

  .badge {
    color: var(--global-card-bg-color) !important;
    background-color: var(--global-theme-color) !important
  }

  .education .edu-link:hover {
    text-decoration: underline;
  }

  .education .edu-list {
    color: var(--global-text-color);
    text-align: justify;
    padding-left: 1rem;
  }

  .education .edu-skill {
    background-color: transparent;
    border: 0.0625rem solid var(--global-divider-color);
    padding: 0.5rem;
    margin-right: 0.25rem;
    margin-bottom: 0.25rem;
    border-radius: 0.25rem;
    display: inline-block;
  }

  .education .edu-thesis-btn {
    font-size: 0.8rem;
    padding: 0.25rem 0.5rem;
    color: var(--global-theme-color);
    border-color: var(--global-theme-color);
  }

  @media (max-width: 48rem) {
    .education .edu-card {
      padding: 1.25rem;
    }
    .education .edu-badge {
      padding: 0.2rem 0.6rem;
      font-size: 0.75rem;
    }
  }
</style>

<div class="education">

  <div class="card my-3 p-4 edu-card">
    <div class="card-body p-0">
      <div class="d-flex flex-column flex-md-row justify-content-between align-items-start align-items-md-center mb-2">
        <h4 class="card-title font-weight-bold mb-1 edu-title">Bachelor of Science in Computer Science & Telecommunication Engineering</h4>
        <span class="badge font-weight-bold text-uppercase align-middle">Jan 2017 - March 2022</span>
      </div>
      <h5 class="card-subtitle text-muted mb-3 font-weight-bold">
        <a href="https://nstu.edu.bd" target="_blank" class="edu-link">Noakhali Science and Technology University</a> | Noakhali, Bangladesh
      </h5>
      <ul class="card-text edu-list">
        <li class="mb-2"><strong>Academic Standing:</strong> CGPA of 3.58 / 4.00 (<strong>3.98</strong> in the last 2 semesters), ranking 6th of 54 students (Top 11% of cohort).</li>
        <li class="mb-2"><strong>Undergraduate Thesis:</strong> <em>A Comparative Study of Lightweight Face Mask Detectors for Real-Time Applications</em>
          <br>
          <span class="text-muted">Supervisor: Abul Kalam Azad (Assistant Professor, Dept. of CSTE, NSTU; Ph.D. Candidate in Computer Science, The University of Alabama)</span>
          <br>
          <a href="https://drive.google.com/file/d/1KjnnSRnfcvAE_ze2R0nYLBdGWFxXOhIE/view?usp=sharing" target="_blank" class="btn btn-sm btn-outline-primary mt-2 edu-thesis-btn">View Thesis PDF</a>
        </li>
        <li class="mb-2"><strong>Key Coursework:</strong> Algorithms & Data Structures, Object-Oriented Programming, Database Management Systems, System Analysis & Design, Artificial Intelligence, Digital Signal Processing, Computer Networks, Wireless Communications.</li>
        <li class="mb-2"><strong>Honors:</strong> Received the Department Scholarship for Outstanding Academic Performance four times.</li>
      </ul>
      <div class="mt-3">
        <span class="edu-skill">Computer Science</span>
        <span class="edu-skill">Telecommunication Engineering</span>
        <span class="edu-skill">Computer Vision</span>
        <span class="edu-skill">Machine Learning</span>
        <span class="edu-skill">Object Detection</span>
      </div>
    </div>
  </div>

</div>
