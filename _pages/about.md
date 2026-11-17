---
layout: about
title: about
permalink: /
subtitle: >
  ML / Computer Vision Engineer &middot; M.S. Data Science, Stony Brook University (May 2027) &middot;
  <a href="https://www3.cs.stonybrook.edu/~zyin/">CV Lab</a>, Advisor: Prof. Zhaozheng Yin

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false
  more_info: >
    <p>Stony Brook, NY</p>
    <p><a href="mailto:gdakate1215@gmail.com">gdakate1215@gmail.com</a></p>
    <p><a href="/assets/pdf/Yongeun_Cho_Resume.pdf">Resume (PDF)</a></p>

selected_papers: false
social: true

announcements:
  enabled: false

latest_posts:
  enabled: false
---

**Open to full-time ML Engineer, Computer Vision, and Research roles starting May 2027.**
[Resume (PDF)](/assets/pdf/Yongeun_Cho_Resume.pdf) &middot; [gdakate1215@gmail.com](mailto:gdakate1215@gmail.com)

I build computer vision systems on top of pretrained foundation models and check whether their outputs can be trusted.
Most of my recent work is on clinical video: I take frozen video models like V-JEPA, attach lightweight predictors,
and measure which regions and time windows actually drive each prediction.
I have shipped work across PyTorch research pipelines, real-time multi-agent LLM systems, and cloud-deployed CV apps.

### Highlights

- **Clinical video interpretability.** Built a SAM3 + frozen V-JEPA 2.1 pipeline over 3,689 ICU clips (37 patients), reaching **0.94 AUROC**. My gradient-free attribution method beat native attention by **+0.23 logit** at a 10% budget. [→ project](/projects/1_vjepa_interpretability/)
- **Human–AI deception arena.** Real-time multiplayer game where humans and LLM agents (Claude, GPT-4o, Gemini, Llama) play anonymously. In a pilot, humans detected AI players **73%** of the time vs. **40%** for AI raters. [→ project](/projects/2_sandbox/) &middot; [code](https://github.com/gdakate/The-Sandbox)
- **Foundation-model segmentation.** Reproduced few-shot SAM-based segmentation on Kvasir-SEG (**34.85% Dice** vs. 24.45% reported) and showed that support-image choice alone swings mean Dice from 36.8% to 73.5%. [→ project](/projects/3_medical_segmentation/)
- **Diffusion face anonymization.** Cut inference time by **53%** (18.6 s → 8.7 s); **2nd Prize**, Google ML Bootcamp 2025. [→ project](/projects/4_fawn/)

[See all projects →](/projects/)

### Experience

- **Graduate Student Researcher (M.S. Thesis)**, Computer Vision Lab, Stony Brook University &middot; _Feb 2026 – Present_<br>
  Extending the ICU work as my M.S. thesis: which spatial and temporal evidence drives predictions from frozen V-JEPA 2.1 representations.
- **Research Project Assistant**, Stony Brook Medicine (Neurosurgery) &middot; _May 2026 – Aug 2026_<br>
  Interpretability and counterfactual auditing for a frozen ICU agitation predictor built on V-JEPA representations.
- **Backend Developer**, Snowrose Reorganization Task Force Team, Seoul &middot; _Feb 2024 – Aug 2024_<br>
  Cut query latency by 30% for Spring Boot APIs serving 1,700+ daily requests through database indexing.
- **Software Engineering Intern**, Mand.ro, Incheon &middot; _Aug 2024 – Sep 2024_<br>
  Cut real-time EMG visualization latency for prosthetic control to under 1 s (Matplotlib → OpenCV).
- **Teaching Assistant**, IAE 101 (Intro to Digital Intelligence) and **Pre-College STEM Robotics Instructor**, Stony Brook University &middot; _Sep 2026 – Present_

### Education

- **M.S. in Data Science, Stony Brook University** &middot; _2025 – May 2027 (expected)_<br>
  Computer Vision Lab, Advisor: Prof. Zhaozheng Yin &middot; GPA 3.56 / 4.0
- **B.S. in IT Engineering, Sookmyung Women's University**, Seoul &middot; _Mar 2020 – Aug 2024_

### Skills

**ML & Vision:** PyTorch, TensorFlow, SAM3, V-JEPA, Diffusion Models, YOLOv8, OpenCV, MediaPipe, scikit-learn<br>
**Interpretability & Evaluation:** Feature attribution, Sparse Autoencoders, Representation Learning, Hugging Face, LangChain<br>
**Backend & Deployment:** FastAPI, Flask, Spring Boot, Docker, AWS, GCP &middot; **Languages:** Python, Java, C++, SQL
