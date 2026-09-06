---
layout: archive
title: "CV"
permalink: /en/cv/
lang: en-US
author_profile: true
redirect_from:
  - /en/resume
---

{% include base_path %}

## Education
<div class="cv-education">
  <div class="cv-education__item">
    <img class="cv-education__logo" src="{{ base_path }}/images/school-logos/nankai-logo.jpg" alt="Nankai University logo">
    <div class="cv-education__body">
      <div class="cv-education__title">Ph.D. in Computer Science and Technology, Nankai University, 2026.09 - present</div>
      <div class="cv-education__meta">School of Cyberspace Security · Supervisors: Prof. Ding Dan and Associate Prof. Dai Yimian</div>
    </div>
  </div>

  <div class="cv-education__item">
    <img class="cv-education__logo" src="{{ base_path }}/images/school-logos/cumt-logo.png" alt="China University of Mining and Technology logo">
    <div class="cv-education__body">
      <div class="cv-education__title">M.S. in Software Engineering, China University of Mining and Technology, 2023.09 - 2026.06</div>
      <div class="cv-education__meta">School of Computer Science and Technology · GPA: 88.92/100, rank 1/12 · Supervisors: Prof. Liu Bing and Associate Prof. Liu Peng</div>
    </div>
  </div>

  <div class="cv-education__item">
    <img class="cv-education__logo" src="{{ base_path }}/images/school-logos/hhu-logo.png" alt="Hohai University logo">
    <div class="cv-education__body">
      <div class="cv-education__title">B.S. in Computer Science and Technology, Hohai University, 2017.09 - 2021.06</div>
      <div class="cv-education__meta">School of Computer and Information · GPA: 4.36/5, rank 50/209 · Supervisor: Prof. Liu Fan</div>
    </div>
  </div>
</div>

## Research Interests
- Remote sensing object detection
- Out-of-distribution generalization
- 3D scene understanding

## Project Experience
- Mine Safety Risk Visualization and Control System, 2025.10 - 2025.12
  - Tech stack: Ruoyi front-end/back-end separation framework, visualization dashboard tools, MySQL
  - Responsibilities: real-time data display, dashboard development, DeepSeek-based question answering
  - Highlights: built a data dashboard with Shanhaijing and connected real-time data sources; designed prompts for hazard source analysis

## Honors and Awards
- Outstanding Graduate of China University of Mining and Technology
- Outstanding Master's Thesis of China University of Mining and Technology

## Skills
- Python / C++ / JavaScript
- PyTorch
- Linux and Shell scripting
- CET-6: 536

## Publications
<ul>{% for post in site.publications %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
