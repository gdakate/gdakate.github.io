---
layout: page
title: Video Foundation Model Interpretability
description: Gradient-free counterfactual auditing of a frozen V-JEPA predictor on 3,689 ICU video clips (+0.23 logit over native attention)
importance: 1
category: research
---

**Research Project Assistant · Stony Brook Medicine (Neurosurgery) · May 2026 – Aug 2026**

`V-JEPA 2.1` · `SAM3` · `PyTorch` · `Counterfactual Attribution` · `Sparse Autoencoders` · `Optical Flow`

### Problem

ICU teams want early warning of patient agitation from bedside video, but a prediction is only useful if clinicians can see _why_ it fired.
Patients are heavily occluded by tubes, masks, and bedding, so landmark-based features (MediaPipe face/pose) were unreliable.
The question: which body regions and time windows does a frozen video-foundation-model predictor actually depend on, and can that evidence be measured reliably?

### Approach

- **Region-level representations.** Used SAM3 to crop eye-, face-, and patient-level regions, then extracted frozen V-JEPA 2.1 embeddings for each region from 3,689 twenty-second clips across 37 patients.
- **Predictors.** Trained lightweight MLP and self-attention classifiers on top of the frozen embeddings, keeping the backbone fixed.
- **Gradient-free attribution.** Scored region–time cells with a learned agitation direction in embedding space, then tested each method by replacing its top-ranked cells with counterfactual (calm) features and measuring the logit drop.
- **Rigor.** Compared against native attention, Integrated Gradients, and matched-random baselines under the same selection budget, with subject-disjoint splits and subject-level bootstrap confidence intervals.
- **Sparse autoencoders.** Implemented Top-K SAEs and evaluated latent stability across seeds with activation retrieval, optical-flow grounding, and artifact controls.

### Results

- At a 10% evidence budget, counterfactual direction-based evidence reduced the predictor's logit **0.23 more than native attention**, with a 95% CI that excluded zero.
- It **matched Integrated Gradients** without needing gradients, so it can be reused across predictors.
- Raw attention gave good predictions but pointed to different locations across seeds and heads, which is why it made a weak explanation.

### Takeaways

- SAE features were not stable enough across seeds to support semantic claims, so I pivoted to a simpler, testable attribution method instead of forcing the story.
- In clinical ML, the evaluation protocol (patient-disjoint folds, matched baselines, confidence intervals) matters as much as the model.
