---
layout: page
permalink: /cv/
title: CV
nav: true
nav_order: 3
description:
---

<style>
.cv-section { margin-bottom: 2rem; }
.cv-section h2 { font-size: 1.15rem; font-weight: 700; border-bottom: 1.5px solid var(--global-divider-color, #dee2e6); padding-bottom: 0.3rem; margin-bottom: 1rem; text-transform: uppercase; letter-spacing: 0.05em; }
.cv-entry { margin-bottom: 1.1rem; }
.cv-entry-header { display: flex; justify-content: space-between; align-items: baseline; flex-wrap: wrap; gap: 0.25rem; }
.cv-entry-header .cv-org { font-weight: 600; font-size: 0.97rem; }
.cv-entry-header .cv-date { font-size: 0.88rem; color: var(--global-text-color-light, #6c757d); white-space: nowrap; }
.cv-entry-title { font-style: italic; font-size: 0.93rem; color: var(--global-text-color-light, #6c757d); margin-bottom: 0.1rem; }
.cv-entry-loc { font-size: 0.88rem; color: var(--global-text-color-light, #6c757d); margin-bottom: 0.35rem; }
.cv-entry ul { margin: 0.25rem 0 0 0; padding-left: 1.2rem; }
.cv-entry ul li { font-size: 0.93rem; margin-bottom: 0.15rem; }
.cv-skills-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 0.75rem 1.5rem; }
@media (max-width: 640px) { .cv-skills-grid { grid-template-columns: 1fr; } .cv-entry-header { flex-direction: column; } }
.cv-skill-group strong { font-size: 0.88rem; display: block; margin-bottom: 0.15rem; }
.cv-skill-group span { font-size: 0.88rem; color: var(--global-text-color-light, #6c757d); }
.cv-award-item { display: flex; justify-content: space-between; align-items: baseline; flex-wrap: wrap; gap: 0.1rem; font-size: 0.93rem; margin-bottom: 0.4rem; }
.cv-award-item .cv-award-name { font-weight: 500; }
.cv-award-item .cv-award-meta { font-size: 0.87rem; color: var(--global-text-color-light, #6c757d); }
</style>

<div class="cv-section">
<h2>Education</h2>

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-org">Stony Brook University</span>
    <span class="cv-date">2025 – 2027 (expected)</span>
  </div>
  <div class="cv-entry-title">M.S. in Data Science</div>
  <div class="cv-entry-loc">Stony Brook, NY, USA</div>
  <ul>
    <li>Computer Vision Lab &middot; Advisor: Prof. Zhaozheng Yin</li>
    <li>GPA: 3.56 / 4.0</li>
    <li>Focus: Video Foundation Models, Interpretability, Computer Vision</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-org">Sookmyung Women's University</span>
    <span class="cv-date">Mar 2020 – Aug 2024</span>
  </div>
  <div class="cv-entry-title">B.S. in IT Engineering</div>
  <div class="cv-entry-loc">Seoul, Republic of Korea</div>
  <ul>
    <li>Sookmyung Software Talent Scholarship (2022)</li>
  </ul>
</div>
</div>

<div class="cv-section">
<h2>Experience</h2>

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-org">Stony Brook Medicine</span>
    <span class="cv-date">May 2026 – Aug 2026</span>
  </div>
  <div class="cv-entry-title">Research Project Assistant</div>
  <div class="cv-entry-loc">Stony Brook, NY, USA</div>
  <ul>
    <li>Developed a PyTorch pipeline for ICU agitation prediction using SAM3-based region extraction and frozen V-JEPA 2.1 representations, reaching 0.94 AUROC on 3,689 clips from 37 patients.</li>
    <li>Designed a gradient-free counterfactual attribution framework that outperformed native attention by +0.23 logit at a 10% region-time selection budget (paired p &lt; 0.001).</li>
    <li>Audited subject-disjoint cross-validation folds, found class-prevalence imbalance (4.0–18.3%), and redesigned a reproducible split with ~13% prevalence per fold using label counts, not model performance.</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-org">Snowrose Reorganization Task Force Team</span>
    <span class="cv-date">Feb 2024 – Aug 2024</span>
  </div>
  <div class="cv-entry-title">Backend Developer</div>
  <div class="cv-entry-loc">Seoul, Republic of Korea</div>
  <ul>
    <li>Designed backend APIs using Spring Boot and Java.</li>
    <li>Improved database query latency by 30% through indexing optimization.</li>
    <li>Supported 1,700+ daily requests; conducted API testing and resolved 50+ critical issues.</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-org">Mand.ro</span>
    <span class="cv-date">Aug 2024 – Sep 2024</span>
  </div>
  <div class="cv-entry-title">Software Engineering Intern</div>
  <div class="cv-entry-loc">Incheon, Republic of Korea</div>
  <ul>
    <li>Optimized real-time EMG visualization for prosthetic control, reducing latency to under 1 second by migrating from Matplotlib to OpenCV.</li>
    <li>Improved signal-to-visual responsiveness for assistive robotics/HMI applications.</li>
  </ul>
</div>
</div>

<div class="cv-section">
<h2>Research Experience</h2>

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-org">Stony Brook Computer Vision Lab</span>
    <span class="cv-date">Feb 2026 – Present</span>
  </div>
  <div class="cv-entry-title">Graduate Student Researcher (M.S. Thesis) · Advisor: Prof. Zhaozheng Yin</div>
  <div class="cv-entry-loc">Stony Brook, NY, USA</div>
  <ul>
    <li>Extending the ICU agitation work as an M.S. thesis, analyzing which spatial and temporal evidence drives predictions from frozen V-JEPA 2.1 representations.</li>
    <li>Benchmarked vision foundation models for few-shot medical segmentation on Kvasir-SEG, reaching 34.85% Dice vs. 24.45% in prior work, with Dice ranging from 36.8% to 73.5% on support-image choice alone.</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-org">Smart System Lab, Sookmyung Women's University</span>
    <span class="cv-date">Mar 2024 – Dec 2024</span>
  </div>
  <div class="cv-entry-title">Student Researcher</div>
  <div class="cv-entry-loc">Seoul, Republic of Korea</div>
  <ul>
    <li>Analyzed Linux EXT4 file-system behavior and <code>rm</code> execution for deleted-file recovery research.</li>
    <li>Contributed to work improving Scalpel-based erased-file recovery.</li>
    <li>Participated in drug-interaction and adverse-event prevention research.</li>
  </ul>
</div>
</div>

<div class="cv-section">
<h2>Projects</h2>

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-org">Video Foundation Model Interpretability</span>
    <span class="cv-date">May – Aug 2026</span>
  </div>
  <ul>
    <li>Spatiotemporal interpretability over frozen V-JEPA 2.1 representations: 0.94 AUROC predictor and a gradient-free counterfactual auditing framework (+0.23 logit over native attention).</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-org">The Sandbox: Human–AI Deception Arena</span>
    <span class="cv-date">Jan – May 2026</span>
  </div>
  <ul>
    <li>Multiplayer social-deduction research environment; FastAPI + WebSocket backend; 73% human detection of AI players in 5-session pilot.</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-org">Medical Image Segmentation with Vision Foundation Models</span>
    <span class="cv-date">Feb – May 2026</span>
  </div>
  <ul>
    <li>Reproduced SAM-based few-shot segmentation on Kvasir-SEG (34.85% Dice vs. 24.45% reported) and showed that support-image choice alone swings Dice from 36.8% to 73.5%.</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-org">FAWN — Face Anonymization with Neural Networks</span>
    <span class="cv-date">Mar 2025</span>
  </div>
  <ul>
    <li>Diffusion-based face anonymization; 53% inference speedup (18.6 s → 8.7 s); evaluated with Re-ID, FID, and attribute metrics.</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-org">Real-time Grocery Shopping Assistant for the Visually Impaired</span>
    <span class="cv-date">Mar – May 2024</span>
  </div>
  <ul>
    <li>Fine-tuned YOLOv8 with MediaPipe hand tracking to identify the product in the user's hand; Flask inference backend deployed on GCP for a Flutter app. Gold Award; published at KEMS 2024.</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-org">Drug Interaction and Adverse Event Prevention Application</span>
    <span class="cv-date">Sep 2023 – Mar 2024</span>
  </div>
  <ul>
    <li>Spring Boot backend with public healthcare API integration and GCP deployment; Bronze Award at KDCS 2024.</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-org">Lecture Translation Service for the Visually Impaired</span>
    <span class="cv-date">Jan – May 2023</span>
  </div>
  <ul>
    <li>Spring Boot REST API with OAuth2/JWT; Google Solution Challenge Global Top 100.</li>
  </ul>
</div>
</div>

<div class="cv-section">
<h2>Publications</h2>

<div class="cv-entry">
  <ul>
    <li><strong>Y. Cho</strong>, J. Lee. “Real-time Shopping Assistant for the Visually Impaired.” <em>Korean Entertainment Media Society Fall Conference</em>, Vol. 27, No. 2, 2024.</li>
    <li><strong>Y. Cho</strong>, J. Lee. “A Study on Drug Interaction and Side Effect Prevention.” <em>Korea Digital Content Society Summer Conference</em>, 2024. Bronze Award.</li>
  </ul>
</div>
</div>

<div class="cv-section">
<h2>Teaching</h2>

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-org">Teaching Assistant, IAE 101: Introduction to Digital Intelligence</span>
    <span class="cv-date">Sep 2026 – Present</span>
  </div>
  <div class="cv-entry-loc">Stony Brook University, NY</div>
</div>

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-org">Pre-College STEM Robotics Instructor</span>
    <span class="cv-date">Sep 2026 – Present</span>
  </div>
  <div class="cv-entry-loc">Stony Brook University, NY</div>
  <ul>
    <li>Teach the SnappyXO robotics course to pre-college students.</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-org">SWAI Education Camp Instructor</span>
    <span class="cv-date">Jan 2023</span>
  </div>
  <div class="cv-entry-loc">Sookmyung Women's University, Seoul</div>
  <ul>
    <li>Led hands-on drone-building and Scratch coding activities for children.</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-org">Logical Thinking and Software — TA / Tutor</span>
    <span class="cv-date">Sep – Dec 2022</span>
  </div>
  <div class="cv-entry-loc">Sookmyung Women's University, Seoul</div>
  <ul>
    <li>Supported Python instruction for 50+ non-major students.</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-org">Python &amp; Scratch Instructor</span>
    <span class="cv-date">Feb – Sep 2022</span>
  </div>
  <div class="cv-entry-loc">D-Lab Coding Academy, Seoul</div>
  <ul>
    <li>Taught Python and Scratch to 30+ students through project-based lessons.</li>
  </ul>
</div>
</div>

<div class="cv-section">
<h2>Leadership</h2>

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-org">Google Developer Student Club — Sookmyung</span>
    <span class="cv-date">Sep 2022 – May 2023</span>
  </div>
  <ul>
    <li>Led a 3-person development team in the 2023 Google Solution Challenge; earned Global Top 100 recognition.</li>
    <li>Presented a Java Spring Boot technical session to club members.</li>
  </ul>
</div>
</div>

<div class="cv-section">
<h2>Awards</h2>

<div class="cv-award-item">
  <span class="cv-award-name">2nd Prize — 2025 KSTA/NIPA Google ML Bootcamp</span>
  <span class="cv-award-meta">2025</span>
</div>
<div class="cv-award-item">
  <span class="cv-award-name">Gold Award — IT Project Competition, Sookmyung Women's University</span>
  <span class="cv-award-meta">2024</span>
</div>
<div class="cv-award-item">
  <span class="cv-award-name">Bronze Award — 2024 Korea Digital Content Society Summer Conference</span>
  <span class="cv-award-meta">2024</span>
</div>
<div class="cv-award-item">
  <span class="cv-award-name">Global Top 100 — 2023 Google Solution Challenge</span>
  <span class="cv-award-meta">2023</span>
</div>
<div class="cv-award-item">
  <span class="cv-award-name">Sookmyung Software Talent Scholarship</span>
  <span class="cv-award-meta">2022</span>
</div>
</div>

<div class="cv-section">
<h2>Skills</h2>

<div class="cv-skills-grid">
  <div class="cv-skill-group">
    <strong>Machine Learning &amp; Vision</strong>
    <span>PyTorch, TensorFlow, scikit-learn, Sparse Autoencoders, Diffusion Models, SAM, YOLOv5/v8, OpenCV, MediaPipe, Optical Flow</span>
  </div>
  <div class="cv-skill-group">
    <strong>Foundation Models &amp; Model Analysis</strong>
    <span>Video Foundation Models, Representation Learning, Feature Attribution, Model Evaluation, Hugging Face, LangChain</span>
  </div>
  <div class="cv-skill-group">
    <strong>Backend &amp; Deployment</strong>
    <span>FastAPI, Flask, Spring Boot, Docker, AWS, GCP, Git</span>
  </div>
  <div class="cv-skill-group">
    <strong>Programming</strong>
    <span>Python, Java, C++, C, SQL, JavaScript</span>
  </div>
</div>
</div>

<div class="cv-section">
<h2>Languages</h2>

<div class="cv-award-item">
  <span class="cv-award-name">Korean</span>
  <span class="cv-award-meta">Native</span>
</div>
<div class="cv-award-item">
  <span class="cv-award-name">English</span>
  <span class="cv-award-meta">Professional working proficiency</span>
</div>
</div>
