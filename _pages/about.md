---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# About
I am an incoming Master of Computer Science student at the University of Illinois Urbana-Champaign, with an undergraduate background in Applied Mathematics and Computer Science from the University of Washington.

# 📖 Educations
-  **University of Washington**, 2022.09 - 2026.03<br>
Bachelor of Science in Applied Mathematics: Data Science & Computer Science

- **University of Illinois Urbana-Champaign**, 2026.08 - 2028.05 (expected)<br>
Master of Computer Science<br>

# 💼 Work Experience

- <span style="font-size: 18px;"><strong>Shanghai Chengdian Fuzhi Technology Co., Ltd.</strong></span>, *Jun–Sep 2023*  
  *Project Assistant*  
  - Database design for intelligent parking system, documentation of intelligent system design, system development specifications and database specifications, project management assisting.

# 🏅 Projects
<style>
  .project-container {
    display: flex;
    align-items: flex-start;
    margin-bottom: 20px;
    flex-wrap: wrap;
  }

  .project-text {
    flex: 1;
    margin-right: 20px;
    min-width: 280px;
  }

  .project-image {
    width: 400px;
    flex-shrink: 0;
  }

  .project-image img {
    width: 100%;
  }

  @media (max-width: 768px) {
    .project-container {
      flex-direction: column;
    }

    .project-text {
      margin-right: 0;
      margin-bottom: 16px;
    }

    .project-image {
      width: 100%;
    }
  }

  hr.project-divider {
    border: 0;
    height: 1px;
    background-color: #e5e5e5;
    margin: 2rem 0;
  }
</style>

<div class="project-container"> <!-- Green mode -->
  <div class="project-text">
    <div style="font-size: 20px; font-weight: bold;">
      • Eye Protection Mode Assistant
    </div>
    <div style="margin: 10px 0;">
      Developed a lightweight, browser-wide eye protection mode using Tampermonkey. 
      Implemented a dynamic green light-filter overlay with intensity control via mouse wheel, a floating toggle button, and auto-saved preferences for persistent user experience. 
      Designed to work on nearly all websites while preserving page color hierarchy for better readability. 
      Provided bilingual documentation (EN/CN) and maintained the project through iterative updates.
    </div>
    <div style="margin: 6px 0;">
      <strong>Languages & Tools</strong>: JavaScript, DOM APIs, CSS, Tampermonkey
    </div>
  </div>
  <div class="project-image">
    <img src="/images/Green-mode.GIF" alt="Green-mode" style="max-width: 500px; width: 100%; height: auto;">
  </div>
</div>
<hr class="project-divider">

<div class="project-container"> <!-- Vaccine -->
  <div class="project-text">
    <div style="font-size: 20px; font-weight: bold;">
      • Vaccine Reservation System
    </div>
    <div style="margin: 10px 0;">
      Designed and implemented a vaccine appointment scheduling system that allows users to create accounts, log in, check caregiver schedules, and reserve appointments through a terminal interface. Developed secure login with password hashing and salting, modeled patients and caregivers, and managed vaccine stock using SQL. Connected the system to a Microsoft Azure SQL database via JDBC.
    </div>
  </div>
  <div class="project-image">
    <img src="/images/vaccineReserv.png" alt="Vaccine Reservation System">
  </div>
</div>
<hr class="project-divider">

<div class="project-container"> <!-- PaddleOCR -->
  <div class="project-text">
    <div style="font-size: 20px; font-weight: bold;">
      • Pollutant Information Extraction with OCR
    </div>
    <div style="margin: 4px 0; font-style: italic;">
      Fudan University
    </div>
    <div style="margin: 10px 0;">
      Extracting environmental pollutant information from industrial environmental assessment PDFs using PaddleOCR.
    </div>
  </div>
  <div class="project-image">
    <img src="/images/Paddleocr.png" alt="PaddleOCR">
  </div>
</div>
