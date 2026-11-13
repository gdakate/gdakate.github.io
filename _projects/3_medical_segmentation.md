---
layout: page
title: Medical Image Segmentation with Vision Foundation Models
description: Reproduced EviPrompt and ProtoSAM on Kvasir-SEG (DSC 34.85 vs. 24.45 reported); support-image choice alone swings Dice 0.37–0.74
importance: 3
category: research
---

**Student Researcher · Computer Vision Lab, Stony Brook University · Feb 2026 – May 2026**

`SAM` · `Few-shot Segmentation` · `Medical Imaging` · `PyTorch` · `Model Evaluation`

### Problem

Few-shot, SAM-based segmentation methods promise usable medical masks with almost no annotation.
In practice they depend on a small set of labeled support images, and papers rarely report how much the choice of those images matters.

### Approach

- Reproduced **EviPrompt** and **ProtoSAM** on the Kvasir-SEG polyp segmentation benchmark.
- Ran controlled experiments that held everything fixed except which support images were used.
- Tested whether simple visual-similarity statistics between support and query images could predict which supports would work well.

### Results

- My reproduction reached **DSC 34.85**, compared with **24.45** reported in prior work.
- Support-image selection alone moved mean Dice from **0.368 to 0.735**, nearly a 2× swing with the same model.
- Visual-similarity heuristics did not reliably predict good supports; feature-level compatibility mattered more.

### Takeaways

- Headline numbers for few-shot methods can hide most of their variance. Reporting results across support sets should be standard.
- Support selection should be treated as part of the method, chosen by feature compatibility rather than visual similarity.
