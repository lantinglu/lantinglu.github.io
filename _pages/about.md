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
I am pursuing a master’s degree in Computer Science at the University of Illinois Urbana-Champaign, after earning my bachelor’s degree in Computer Science and Applied Mathematics from the University of Washington.

I am currently open to internship opportunities across software engineering, machine learning, and related fields.

# 📖 Education
- **University of Illinois Urbana-Champaign**, 2026.09 - 2028.06 (expected)<br>
Master of Science in Computer Science<br>

-  **University of Washington**, 2022.09 - 2026.03<br>
Bachelor of Science in Computer Science<br>
Bachelor of Science in Applied Mathematics: Data Science

# 💼 Work Experience
- <span style="font-size: 18px;"><strong>United Automotive Electronic Systems (UAES)</strong></span>, *Jun - Aug 2026*<br>
  *Algorithm Engineer Intern*<br>
  - Developed an automated evaluation pipeline with OmniDocBench to benchmark enterprise document parsing systems built with PaddleOCR-VL and MinerU in Dockerized environments. Built a semantic data-selection pipeline for internal enterprise documents by extracting chunk-level embeddings, measuring pairwise cosine distances, and aggregating them into document-level average-distance scores.

  - Applied HDBSCAN to group documents into semantic clusters and selected representative samples using a minimum-subset strategy that maximized semantic feature coverage, while filtering out unsuitable and redundant documents. Integrated selected samples with Label Studio for annotation and model iteration, improving the document parsing evaluation score from **86.86 to 91.72**.

- <span style="font-size: 18px;"><strong>iFLYTEK Co., Ltd	</strong></span>, *Jun - Sep 2025*  
  *Algorithm Engineer Intern*  
  - Development and optimization of reusable pipeline scripts integrating x-vector extraction, vq-code generation, prosody analysis, PyDur-based duration modeling, and MFA-based phoneme alignment, enabling large-scale speech synthesis. Proposed and implemented a variance-based speech quality detection method, improving anomaly detection accuracy at waveform boundaries. Collaborated with team members and reported weekly progress in project meetings.

- <span style="font-size: 18px;"><strong>Fudan University</strong></span>, *Jun–Sep 2024*  
  *Research Assistant*  
  - Professor Wei Wang's team participation, literature search, pollutant information extraction OCR research, model analysis, program design, project work report under the guidance of the professor. See below for [details](#pollutant-ocr).

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

  .project-image.project-image-compact {
    width: 320px;
    max-width: 100%;
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

  .yolo-results {
    display: grid;
    grid-template-columns: minmax(0, 1fr) 20px minmax(0, 1fr);
    align-items: center;
    gap: 8px;
    width: 400px;
    max-width: 100%;
    flex-shrink: 0;
    margin: 0;
  }
  .yolo-results img { display: block; width: 100%; height: auto; }
  .yolo-result { min-width: 0; text-align: center; }
  .yolo-result p { margin: 8px 0 0; font-size: 12px; }
  .yolo-result-arrow { text-align: center; font-size: 28px; color: #637e99; }
  @media (max-width: 768px) {
    .yolo-results { width: 100%; }
  }
  @media (max-width: 540px) {
    .yolo-results { grid-template-columns: minmax(0, 1fr); max-width: 360px; }
    .yolo-result-arrow { transform: rotate(90deg); }
  }

  hr.project-divider {
    border: 0;
    height: 1px;
    background-color: #e5e5e5;
    margin: 2rem 0;
  }
</style>

<div class="project-container"> <!-- Wordplay -->
  <div class="project-text">
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
  <div class="project-image">
    <a href="{{ '/images/wordplay.png' | relative_url }}" target="_blank" rel="noopener" title="Open full-size image">
      <img src="/images/wordplay.png" alt="wordplay">
    </a>
  </div>
</div>
<hr class="project-divider">

<div class="project-container"> <!-- Multilingual Character-Level Language Prediction Model -->
  <div class="project-text">
    <div style="font-size: 20px; font-weight: bold;">
      • Multilingual Character-Level Language Model for Next-Character Prediction
    </div>
    <div style="margin: 4px 0; font-style: italic;">
      Multilingual NLP & Language Modeling Project
    </div>
    <div style="margin: 10px 0;">
      Developed a multilingual character-level language prediction model for next-character prediction under low-resource and noisy text scenarios. Proposed a hybrid framework combining a character-level Transformer with a statistical N-gram language model, using weighted score fusion to improve prediction robustness and stability across multilingual inputs.
    </div>
    <div style="margin: 10px 0;">
      Implemented an end-to-end training and inference pipeline with AdamW optimization and a cosine annealing learning rate schedule with warmup, improving training stability and convergence efficiency. Processed multilingual datasets and evaluated model performance through prediction accuracy and experimental comparison.
    </div>
    <div style="margin: 6px 0;">
      <strong>Languages & Tools</strong>: Python, PyTorch, Transformer
    </div>
    <div style="margin-top: 10px;">
      <a href="https://github.com/lantinglu/Multilingual-Character-Level-Language-Prediction-Model" style="text-decoration: none;">
        <img src="https://img.shields.io/badge/-GitHub-black?logo=github&style=flat" alt="Code">
      </a>
    </div>
  </div>
  <div class="project-image">
    <a href="{{ '/images/multilingual-character.png' | relative_url }}" target="_blank" rel="noopener" title="Open full-size image">
      <img src="/images/multilingual-character.png" alt="multilingual character-level language prediction model">
    </a>
  </div>
</div>
<hr class="project-divider">

<div class="project-container"> <!-- MarketPilot AI -->
  <div class="project-text">
    <div style="font-size: 20px; font-weight: bold;">
      &bull; MarketPilot AI: Market Entry Decision Support
    </div>
    <div style="margin: 4px 0; font-style: italic;">
      Multi-Agent Workflow &amp; Market Intelligence Project
    </div>
    <div style="margin: 10px 0;">
      Developed a modular market-entry analysis system that helps cross-border sellers evaluate overseas product opportunities. Integrated planning, retrieval, and reporting agents with rule-based demand forecasting, risk assessment, and a weighted Market Entry Score to generate explainable business recommendations.
    </div>
    <div style="margin: 10px 0;">
      Built an Excel-to-CSV/JSON/SQLite data pipeline with source metadata and benchmark scenarios covering 8 markets and 5 industries. Supported free-form product queries with clearly labeled industry-benchmark fallback when exact product data is unavailable. Deployed an interactive Streamlit demo with English and Chinese reports, report previews, and Markdown downloads.
    </div>
    <div style="margin: 6px 0;">
      <strong>Languages &amp; Tools</strong>: Python, pandas, openpyxl, SQLite, Streamlit, pytest
    </div>
    <div style="margin-top: 10px;">
      <a href="https://marketpilot-ai-agent.streamlit.app/" style="text-decoration: none; margin-right: 8px;">
        <img src="https://img.shields.io/badge/-Live_Demo-blue?logo=streamlit&amp;style=flat" alt="Live Demo">
      </a>
      <a href="https://github.com/lantinglu/MarketPilot-AI" style="text-decoration: none;">
        <img src="https://img.shields.io/badge/-GitHub-black?logo=github&amp;style=flat" alt="GitHub">
      </a>
    </div>
  </div>
  <div class="project-image">
    <a href="{{ '/images/marketPilot.png' | relative_url }}" target="_blank" rel="noopener" title="Open full-size image">
      <img src="/images/marketPilot.png" alt="MarketPilot AI market-entry analysis dashboard">
    </a>
  </div>
</div>
<hr class="project-divider">

<div class="project-container"> <!-- YOLO-World -->
  <div class="project-text">
    <div style="font-size: 20px; font-weight: bold;">
      &bull; YOLO-World for Open-Vocabulary Object Detection
    </div>
    <div style="margin: 4px 0; font-style: italic;">
      Computer Vision &amp; Vision-Language Modeling Project
    </div>
    <div style="margin: 10px 0;">
      Built an open-vocabulary object detection system covering text encoding, visual feature extraction, and cross-modal fusion. Integrated a YOLOv8-based CNN backbone, a CLIP Text Encoder, and a lightweight RepVL-PAN module to jointly model multi-scale visual features and text embeddings. Used a Text Adapter to modulate C3/C4/C5 features under textual guidance for cross-modal alignment.
    </div>
    <div style="margin: 10px 0;">
      Optimized dataset management and the training pipeline. Trained on 5,000 images and evaluated on 500 test images from a COCO subset, achieving <strong>0.6128 mAP@50</strong>, compared with <strong>0.5453 for the YOLOv8s baseline</strong>.
    </div>
  </div>
  <div class="yolo-results" aria-label="Detection workflow on the left and example output on the right">
    <a href="{{ '/images/yolo-workflow.svg' | relative_url }}" target="_blank" rel="noopener" title="Open full-size workflow">
      <img src="{{ '/images/yolo-workflow.svg' | relative_url }}" alt="Image and text branches merge into vision-language fusion, followed by detection and confidence filtering" width="600" height="548" loading="lazy">
    </a>
    <div class="yolo-result-arrow" aria-hidden="true">&#8594;</div>
    <div class="yolo-result">
      <a href="{{ '/images/yolo-world-overlay.jpg' | relative_url }}" target="_blank" rel="noopener" title="Open full-size output">
        <img src="{{ '/images/yolo-world-overlay.jpg' | relative_url }}" alt="Output: surfer and surfboard detections, with ground truth in green and predictions in red" width="944" height="966" loading="lazy">
      </a>
      <p>Output &mdash; Ground truth (green), predictions (red).</p>
    </div>
  </div>
</div>
<hr class="project-divider">

<div class="project-container"> <!-- Style Transfer -->
  <div class="project-text">
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
  <div class="project-image">
    <a href="{{ '/images/NST.png' | relative_url }}" target="_blank" rel="noopener" title="Open full-size image">
      <img src="/images/NST.png" alt="NST" style="max-width: 500px; width: 100%; height: auto;">
    </a>
  </div>
</div>
<hr class="project-divider">

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
    <div style="margin: 6px 0;">
      <a href="https://github.com/lantinglu/green-nightmode" style="text-decoration: none;">
        <img src="https://img.shields.io/badge/-Code-black?logo=github&style=flat" alt="GitHub">
      </a>
      <a href="https://greasyfork.org/zh-CN/scripts/538046-%E6%8A%A4%E7%9C%BC%E6%A8%A1%E5%BC%8F%E5%8A%A9%E6%89%8B-%E5%8F%AF%E8%B0%83%E8%8A%82%E5%BC%BA%E5%BA%A6-%E5%BC%80%E5%85%B3%E6%8C%89%E9%92%AE-%E8%89%B2%E5%BD%A9%E6%94%AF%E6%8C%81"
      target="_blank" style="text-decoration: none;">
      <img src="https://img.shields.io/badge/GreasyFork-red?logo=greasyfork&style=flat" alt="GreasyFork">
      </a>
    </div>
  </div>
  <div class="project-image">
    <a href="{{ '/images/Green-mode.GIF' | relative_url }}" target="_blank" rel="noopener" title="Open full-size image">
      <img src="/images/Green-mode.GIF" alt="Green-mode" style="max-width: 500px; width: 100%; height: auto;">
    </a>
  </div>
</div>
<hr class="project-divider">

<div class="project-container" id="pollutant-ocr" style="scroll-margin-top: 80px;"> <!-- PaddleOCR -->
  <div class="project-text">
    <div style="font-size: 20px; font-weight: bold;">
      • Pollutant Information Extraction with OCR
    </div>
    <div style="margin: 4px 0; font-style: italic;">
      Fudan University
    </div>
    <div style="margin: 10px 0;">
      Participation in a text-mining research project on intelligent document processing for environmental regulatory compliance; Design and implementation of an integrated table-parsing solution for information extraction from unstructured enterprise reports; Application of differentiable binarization models for text detection and CRNN-based text recognition for OCR.
    </div>
    <div style="margin: 6px 0;">
      <strong>Languages & Tools</strong>: Python
      <a href="https://github.com/lantinglu/PaddleOCR-pollution" style="text-decoration: none;">
        <img src="https://img.shields.io/badge/-Code-black?logo=github&style=flat" alt="GitHub">
      </a>
    </div>
  </div>
  <div class="project-image project-image-compact">
    <a href="{{ '/images/pdf-to-json.svg' | relative_url }}" target="_blank" rel="noopener" title="Open full-size image">
      <img src="/images/pdf-to-json.svg" alt="PDF text extraction workflow: document pages, PaddleOCR text detection and recognition, structured JSON output">
    </a>
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
    <div style="margin: 6px 0;">
      <strong>Languages & Tools</strong>:
      Java, SQL, JDBC, Microsoft Azure
      <a href="https://github.com/lantinglu/COVID-19-Vaccine-Reservation-System" style="text-decoration: none; margin-left: 8px; vertical-align: middle;">
        <img src="https://img.shields.io/badge/-Code-black?logo=github&style=flat" alt="GitHub">
      </a>
    </div>
  </div>
  <div class="project-image">
    <a href="{{ '/images/vaccineReserv.png' | relative_url }}" target="_blank" rel="noopener" title="Open full-size image">
      <img src="/images/vaccineReserv.png" alt="Vaccine Reservation System">
    </a>
  </div>
</div>
<hr class="project-divider">

<div class="project-container"> <!-- Tinyserv -->
  <div class="project-text">
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
  <div class="project-image">
    <a href="{{ '/images/tinyserv.png' | relative_url }}" target="_blank" rel="noopener" title="Open full-size image">
      <img src="/images/tinyserv.png" alt="tinyserv">
    </a>
  </div>
</div>
<hr class="project-divider">
