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
    <li>Built a clinical video interpretability pipeline using frozen V-JEPA representations from 3,600+ ICU clips across multiscale eye-, face-, and patient-level streams.</li>
    <li>Implemented Top-K Sparse Autoencoders in PyTorch; evaluated latent features through multi-seed stability testing, activation-based retrieval, optical-flow grounding, and artifact controls.</li>
    <li>Developed a region–time counterfactual auditing framework for frozen MLP and self-attention predictors, outperforming native attention by +0.23 logit while matching Integrated Gradients.</li>
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
    <span class="cv-date">2026</span>
  </div>
  <div class="cv-entry-title">Student Researcher</div>
  <div class="cv-entry-loc">Stony Brook, NY, USA</div>
  <ul>
    <li>Medical image segmentation with SAM-based vision foundation models under low-annotation settings.</li>
    <li>Benchmarked zero-shot/few-shot segmentation; investigated sensitivity to support/reference image selection.</li>
    <li>Evaluated on Kvasir-SEG and related medical-image datasets.</li>
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
    <li>Built spatiotemporal interpretability pipeline over frozen V-JEPA representations; implemented Top-K Sparse Autoencoders and counterfactual auditing framework.</li>
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
    <li>Reproduced SAM-based zero-shot segmentation experiments on Kvasir-SEG; DSC 34.85 vs. 24.45 baseline.</li>
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
    <li>YOLOv8 object detection (83% accuracy), MediaPipe gesture recognition, Flask/AWS EC2 cloud inference; published at KEMS 2024.</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-org">Drug Interaction and Adverse Event Prevention Application</span>
    <span class="cv-date">Sep 2023 – Mar 2024</span>
  </div>
  <ul>
    <li>Spring Boot backend with public healthcare API integration and GCP deployment (99.9% uptime); published at DCS 2024.</li>
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
<h2>Teaching</h2>

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
