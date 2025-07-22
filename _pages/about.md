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
I am an undergraduate student at the University of Washington, double majoring in Computer Science and Applied Mathematics.

# 📖 Educations
-  **University of Washington**, 2022.09 - 2026.06 (expected)<br>
Bachelor of Science in Computer Science<br>
Bachelor of Science in Applied Mathematics: Data Science

# 💼 Work Experience
- <span style="font-size: 18px;"><strong></strong></span>, *Jun - Sep 2025*  
  *Algorithm Engineer Intern*  

- <span style="font-size: 18px;"><strong>Deloitte</strong></span>, *Jun 2025*  
  *Project Assistant*  

- <span style="font-size: 18px;"><strong>Fudan University</strong></span>, *Jun–Sep 2024*  
  *Research Assistant*  
  - Professor Wei Wang's team participation, literature search, pollutant information extraction OCR research, model analysis, program design, project work report under the guidance of the professor

- <span style="font-size: 18px;"><strong>Shanghai Chengdian Fuzhi Technology Co., Ltd.</strong></span>, *Jun–Sep 2023*  
  *Project Assistant*  
  - Database design for intelligent parking system, documentation of intelligent system design, system development specifications and database specifications, project management assisting.

# 🏅 Projects
<style>
  .wordplay-container {
    display: flex;
    align-items: flex-start;
    margin-bottom: 20px;
    flex-wrap: wrap;
  }

  .wordplay-text {
    flex: 1;
    margin-right: 20px;
    min-width: 280px;
  }

  .wordplay-image {
    width: 400px;
    flex-shrink: 0;
  }

  .wordplay-image img {
    width: 100%;
  }

  @media (max-width: 768px) {
    .wordplay-container {
      flex-direction: column;
    }

    .wordplay-text {
      margin-right: 0;
      margin-bottom: 16px;
    }

    .wordplay-image {
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

<div class="wordplay-container">
  <div class="wordplay-text">
    <div style="font-size: 20px; font-weight: bold;">
      • Wordplay: An Interactive Programming Language for Multilingual and Inclusive Expression
    </div>
    <div style="margin: 4px 0; font-style: italic;">
      UW iSchool & Allen School
    </div>
    <div style="margin: 10px 0;">
      Participating in the development and testing of <strong>Wordplay</strong>, an interactive programming language designed for multilingual users and people with disabilities. Working on responsive data flow modules, graphical and interactive programming features, and contributed to an adaptable programming prototype. Regularly reported project progress, discussed human-computer interaction research topics, and summarized experimental findings.
    </div>
    <div style="margin: 6px 0;">
      <strong>Languages & Tools</strong>: JavaScript, TypeScript, HTML, CSS, Svelte/SvelteKit
    </div>
    <div style="margin-top: 10px;">
      <a href="https://wordplay.dev/" style="text-decoration: none; margin-right: 8px;">
        <img src="https://img.shields.io/badge/🌐-Wordplay website-blue?style=flat" alt="Website">
      </a>
      <a href="https://github.com/wordplaydev/wordplay" style="text-decoration: none;">
        <img src="https://img.shields.io/badge/-GitHub-black?logo=github&style=flat" alt="GitHub">
      </a>
    </div>
  </div>
  <div class="wordplay-image">
    <img src="/images/wordplay.png" alt="wordplay">
  </div>
</div>
<hr class="project-divider">
<div class="wordplay-container">
  <div class="wordplay-text">
    <div style="font-size: 20px; font-weight: bold;">
      • Optimization of Neural Style Transfer
    </div>
    <div style="margin: 10px 0;">
      Built a modular Neural Style Transfer system in Python using PyTorch, inspired by 
      <a href="https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf" target="_blank" style="text-decoration: underline;">
        Gatys et al. (2016)
      </a>.
      Leveraged a pre-trained VGG-19 network to extract content and style features, computed via MSE and Gram matrices. Optimized with L-BFGS over 300–500 iterations, supporting both CPU and GPU. Evaluated VGG19 against ResNet18, and proposed improvements for mobile and web deployment.
    </div>
    <div style="margin: 6px 0;">
      <strong>Languages & Tools</strong>: Python, PyTorch, Torchvision, Pillow (PIL), Matplotlib
    </div>
    <div style="margin: 6px 0;">
      <a href="https://github.com/lantinglu/style-transfer" style="text-decoration: none;">
        <img src="https://img.shields.io/badge/-Code-black?logo=github&style=flat" alt="GitHub">
      </a>
    </div>
  </div>
  <div class="wordplay-image">
    <img src="/images/NST.png" alt="NST" style="max-width: 500px; width: 100%; height: auto;">
  </div>
</div>

<hr class="project-divider">

<div class="wordplay-container">
  <div class="wordplay-text">
    <div style="font-size: 20px; font-weight: bold;">
      • Vaccine Reservation System
    </div>
    <div style="margin: 10px 0;">
      Designed and implemented a vaccine appointment scheduling system that allows users to create accounts, log in, check caregiver schedules, and reserve appointments through a terminal interface. Developed secure login with password hashing and salting, modeled patients and caregivers, and managed vaccine stock using SQL. Connected the system to a Microsoft Azure SQL database via JDBC.
    </div>
    <div style="margin: 6px 0;">
      <strong>Languages & Tools</strong>: 
      Java, SQL, JDBC, Microsoft Azure
      <a href="https://github.com/lantinglu/COVID-19-Vaccine-Reservation-System" style="text-decoration: none; margin-left: 8px; vertical-align: middle;">
        <img src="https://img.shields.io/badge/-Code-black?logo=github&style=flat" alt="GitHub">
      </a>
    </div>
  </div>
  <div class="wordplay-image">
    <img src="/images/vaccineReserv.png" alt="Vaccine Reservation System">
  </div>
</div>

<hr class="project-divider">

<div class="wordplay-container">
  <div class="wordplay-text">
    <div style="font-size: 20px; font-weight: bold;">
      • Tinyserv: Exploit Analysis & Patch Development
    </div>
    <div style="margin: 10px 0;">
      Investigated real-world exploits on a vulnerable HTTP server (<code>tinyserv</code>), performed root-cause analysis, and wrote secure patches to prevent unauthorized access to admin-only pages. Ensured functional correctness and long-term security across both normal and malicious inputs.
    </div>
    <div style="margin: 6px 0;">
      <strong>Languages & Tools</strong>: C, gdb, curl, HTTP
      <a href="https://github.com/lantinglu/tinyserv" style="text-decoration: none; margin-right: 8px;">
        <img src="https://img.shields.io/badge/-Code-black?logo=github&style=flat" alt="GitHub">
      </a>
    </div>
  </div>
  <div class="wordplay-image">
    <img src="/images/tinyserv.png" alt="tinyserv">
  </div>
</div>

<hr class="project-divider">

<div class="wordplay-container">
  <div class="wordplay-text">
    <div style="font-size: 20px; font-weight: bold;">
      • Pollutant Information Extraction with OCR
    </div>
    <div style="margin: 4px 0; font-style: italic;">
      Fudan University
    </div>
    <div style="margin: 10px 0;">
      Extracting environmental pollutant information from industrial environmental assessment PDFs using PaddleOCR.
    </div>
    <div style="margin: 6px 0;">
      <strong>Languages & Tools</strong>: Python
      <a href="https://github.com/lantinglu/PaddleOCR-pollution" style="text-decoration: none;">
        <img src="https://img.shields.io/badge/-Code-black?logo=github&style=flat" alt="GitHub">
      </a>
    </div>
  </div>
  <div class="wordplay-image">
    <img src="/images/Paddleocr.png" alt="PaddleOCR">
  </div>
</div>
