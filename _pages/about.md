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
Hi! I am an undergraduate student at the University of Washington, double majoring in Computer Science and Applied Mathematics.

# 📖 Educations
-  **University of Washington**, 2022.09 - 2026.06 (expected)<br>
Bachelor of Science in Computer Science<br>
Bachelor of Science in Applied Mathematics: Data Science

# 💼 Work Experience

- <span style="font-size: 18px;"><strong>Shanghai Fudan University</strong></span>, *Jun–Sep 2024*  
  *Research Assistant*  
  - Professor Wei Wang's team participation, literature search, pollutant information extraction OCR research, model analysis, program design, project work report under the guidance of the professor

- <span style="font-size: 18px;"><strong>Shanghai Chengdian Fuzhi Technology Co., Ltd.</strong></span>, *Jun–Sep 2023*  
  *Project Assistant*  
  - Database design for intelligent parking system, documentation of intelligent system design, system development specifications and database specifications, project management assisting.

# 🏅 Projects
<div style="display: flex; align-items: flex-start; margin-bottom: 20px;">
  <div style="display: flex; flex-direction: column; gap: 10px; width: 1000px; margin-right: 20px;">
    <img src="wordplay1.png" alt="Screenshot 1" style="width: 100%; border-radius: 6px;">
    <img src="wordplay2.png" alt="Screenshot 2" style="width: 100%; border-radius: 6px;">
  </div>

  <div>
    <div style="font-size: 20px; font-weight: bold;">
      Wordplay: An Interactive Programming Language for Multilingual and Inclusive Expression
    </div>
    <div style="margin: 4px 0; font-style: italic;">
      UW iSchool & Allen School
    </div>
    <div style="margin: 10px 0;">
      Participating in the development and testing of <strong>Wordplay</strong>, an interactive programming language designed for multilingual users and people with disabilities. Working on responsive data flow modules, graphical and interactive programming features, and contributed to an adaptable programming prototype. Regularly reported project progress, discussed human-computer interaction research topics, and summarized experimental findings.  
    </div>
    <div style="margin: 6px 0;">
      <strong>Languages & Tools</strong>: JavaScript, TypeScript, HTML, CSS, Svelte/SvelteKit, Git
    </div>
    <div style="margin-top: 10px;">
      <a href="https://wordplay.dev/" style="text-decoration: none; margin-right: 8px;">
        <img src="https://img.shields.io/badge/🌐-Wordplay website-blue?style=flat" alt="Website">
      </a>
      <a href="https://github.com/wordplaydev/wordplay" style="text-decoration: none;">
        <img src="https://img.shields.io/badge/🧠-GitHub-black?style=flat" alt="GitHub">
      </a>
    </div>
  </div>
</div>


- **COVID-19 Vaccine Reservation System** <br>
  Designed and implemented a vaccine appointment scheduling system that allows users to create accounts, log in, check caregiver schedules, and reserve appointments through a terminal interface. Developed secure login with password hashing and salting, modeled patients and caregivers, and managed vaccine stock using SQL. Connected the system to a Microsoft Azure SQL database via JDBC. <br> 
  **Languages & Tools**: Java, SQL, JDBC, Microsoft Azure <br>
  **Link**: [COVID-19 Vaccine Reservation System](https://github.com/lantinglu/COVID-19-Vaccine-Reservation-System)

- **tinyserv: Exploit Analysis & Patch Development**  
  Investigated real-world exploits on a vulnerable HTTP server (`tinyserv`), performed root-cause analysis, and wrote secure patches in C to prevent unauthorized access to admin-only pages. Ensured functional correctness and long-term security across both normal and malicious inputs. <br>
  **Languages & Tools**: C, Git, gdb, curl, HTTP  <br>
  **Link**: [tinyserv](https://github.com/lantinglu/tinyserv)

- **Dynamic Storage Allocator**   
  Developed a dynamic memory allocator in C from scratch, implementing malloc, free, and heap coalescing using an explicit free list. <br>
  **Languages & Tools**: C, gdb <br>
  **Link**: [Dynamic Storage Allocator](https://github.com/lantinglu/CSE351-The-Hardware-Software-Interface/tree/main/lab5)




