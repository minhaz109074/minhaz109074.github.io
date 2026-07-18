---
layout: page
permalink: /experience/
title: Experience
nav: true
nav_order: 3
---

<style>
  .experience .exp-card {
    background-color: var(--global-card-bg);
    border-color: var(--global-divider-color);
    box-shadow: 0 0.125rem 0.3125rem 0 rgba(0,0,0,0.16), 0 0.125rem 0.625rem 0 rgba(0,0,0,0.12);
    transition: transform 0.22s ease, box-shadow 0.22s ease;
    border-radius: 0.375rem;
  }

  .experience .exp-card:hover {
    transform: translateY(-0.25rem);
    box-shadow: 0 0.625rem 1.375rem rgba(0,0,0,0.12), 0 0.25rem 0.625rem rgba(0,0,0,0.1);
  }

  html[data-theme="dark"] .experience .exp-card {
    box-shadow: 0 0.125rem 0.3125rem 0 rgba(0,0,0,0.45), 0 0.625rem 1.25rem 0 rgba(0,0,0,0.4);
  }

  html[data-theme="dark"] .experience .exp-card:hover {
    box-shadow: 0 0.625rem 1.375rem rgba(0,0,0,0.45), 0 0.25rem 0.625rem rgba(0,0,0,0.4);
  }

  .experience .exp-title {
    color: var(--global-theme-color);
  }

  .experience .exp-badge {
    background-color: var(--global-theme-color);
    color: #fff;
    padding: 0.25rem 0.75rem;
    font-weight: 700;
    white-space: nowrap;
    border-radius: 0.25rem;
  }

  .experience .exp-company {
    color: var(--global-text-color);
    text-decoration: underline;
  }

  .experience .exp-company:hover {
    color: var(--global-theme-color);
  }

  .experience .exp-list {
    color: var(--global-text-color);
    text-align: justify;
    padding-left: 1rem;
  }

  .experience .exp-skill {
    background-color: transparent;
    border: 0.0625rem solid var(--global-divider-color);
    padding: 0.5rem;
    margin-right: 0.25rem;
    margin-bottom: 0.25rem;
    border-radius: 0.25rem;
    display: inline-block;
  }

  @media (max-width: 48rem) {
    .experience .exp-card {
      padding: 1.25rem;
    }
    .experience .exp-badge {
      padding: 0.2rem 0.6rem;
      font-size: 0.75rem;
    }
  }
</style>

<div class="experience">

  <div class="card my-3 p-4 exp-card">
    <div class="card-body p-0">
      <div class="d-flex flex-column flex-md-row justify-content-between align-items-start align-items-md-center mb-2">
        <h4 class="card-title font-weight-bold mb-1 exp-title">Software Engineer II</h4>
        <span class="exp-badge">Dec 2022 - Present</span>
      </div>
      <h5 class="card-subtitle text-muted mb-3 font-weight-bold">
        <a href="https://www.ait.inc" target="_blank" class="exp-company">AIT Inc</a> | Dhaka, Bangladesh
      </h5>
      <ul class="card-text exp-list">
        <li class="mb-2">Designed, developed, and maintained enterprise-grade backend systems using ASP.NET Core, delivering scalable, reliable, and high-performance solutions across healthcare, e-commerce, AI, government, and social media platforms.</li>
        <li class="mb-2">Led the integration of LLM-based automation into a budget forecasting platform, cutting manual data preparation time by over 90%.</li>
        <li class="mb-2">Designed and developed modular monolithic and microservice-based applications, APIs, database schemas, and backend services with a strong focus on scalability, maintainability, and clean software design.</li>
        <li class="mb-2">Integrated AI-assisted tooling (code review, ticketing, database design) into the development workflow, reducing engineering overhead by 2-4 hours daily.</li>
        <li class="mb-2">Collaborated directly with U.S. and Australian clients to gather requirements, analyze business challenges, and propose technical solutions.</li>
        <li class="mb-2">Mentored junior developers and interns, conducted code reviews and technical interviews, and supported the engineering hiring process.</li>
      </ul>
      <div class="mt-3">
        <span class="exp-skill">C#</span>
        <span class="exp-skill">ASP.NET Core WebAPI</span>
        <span class="exp-skill">PostgreSQL + pgvector</span>
        <span class="exp-skill">MongoDB</span>
        <span class="exp-skill">Cassandra</span>
        <span class="exp-skill">Redis</span>
        <span class="exp-skill">Apache Kafka</span>
        <span class="exp-skill">AWS</span>
        <span class="exp-skill">Docker</span>
      </div>
    </div>
  </div>

  <div class="card my-3 p-4 exp-card">
    <div class="card-body p-0">
      <div class="d-flex flex-column flex-md-row justify-content-between align-items-start align-items-md-center mb-2">
        <h4 class="card-title font-weight-bold mb-1 exp-title">Software Engineer Intern</h4>
        <span class="exp-badge">Aug 2022 - Nov 2022</span>
      </div>
      <h5 class="card-subtitle text-muted mb-3 font-weight-bold">
        <a href="https://www.ait.inc" target="_blank" class="exp-company">AIT Inc</a> | Dhaka, Bangladesh
      </h5>
      <ul class="card-text exp-list">
        <li class="mb-2">Participated in the AIT Inc Dev Bootcamp for Coding Champs, gaining practical experience with ReactJS, NextJS, Flutter, .NET Core, and Design Patterns.</li>
        <li class="mb-2">Developed small-scale projects, including an e-commerce site, web API, mobile app, and console application, to learn and apply new technologies.</li>
      </ul>
      <div class="mt-3">
        <span class="exp-skill">ReactJS</span>
        <span class="exp-skill">Next.js</span>
        <span class="exp-skill">Flutter</span>
        <span class="exp-skill">.NET Core</span>
        <span class="exp-skill">Design Patterns</span>
      </div>
    </div>
  </div>

  <div class="card my-3 p-4 exp-card">
    <div class="card-body p-0">
      <div class="d-flex flex-column flex-md-row justify-content-between align-items-start align-items-md-center mb-2">
        <h4 class="card-title font-weight-bold mb-1 exp-title">Associate Member</h4>
        <span class="exp-badge">Dec 2020 - Sep 2021</span>
      </div>
      <h5 class="card-subtitle text-muted mb-3 font-weight-bold">
        Darul Irfan Research Institute | Chattogram, Bangladesh
      </h5>
      <ul class="card-text exp-list">
        <li class="mb-2">Collaborated on academic research analyzing data patterns in Sufi music and local community cultural involvements.</li>
        <li class="mb-2">Participated in study design, data collection, and preparation of research papers published in peer-reviewed journals.</li>
      </ul>
      <div class="mt-3">
        <span class="exp-skill">Research Methodology</span>
        <span class="exp-skill">Data Mining</span>
        <span class="exp-skill">Academic Writing</span>
      </div>
    </div>
  </div>

  <div class="card my-3 p-4 exp-card">
    <div class="card-body p-0">
      <div class="d-flex flex-column flex-md-row justify-content-between align-items-start align-items-md-center mb-2">
        <h4 class="card-title font-weight-bold mb-1 exp-title">Mentorship & Teaching Experience</h4>
        <span class="exp-badge">Jan 2017 - Present</span>
      </div>
      <h5 class="card-subtitle text-muted mb-3 font-weight-bold">
        Professional Mentorship & Academic Instruction
      </h5>
      <ul class="card-text exp-list">
        <li class="mb-2"><strong>Intern Mentor at AIT Inc (2023 - Present):</strong> Guided software engineering interns through an industry-oriented curriculum. Mentored them in API design, database modeling, production-grade system architecture, and conducted code reviews.</li>
        <li class="mb-2"><strong>Academic Instructor (2017 - 2022):</strong> Taught Physics, Chemistry, and Mathematics to secondary and higher secondary students, helping them develop strong analytical and problem-solving skills.</li>
      </ul>
      <div class="mt-3">
        <span class="exp-skill">API Design</span>
        <span class="exp-skill">System Architecture</span>
        <span class="exp-skill">Database Modeling</span>
        <span class="exp-skill">Academic Instruction</span>
        <span class="exp-skill">Technical Mentorship</span>
      </div>
    </div>
  </div>

</div>
