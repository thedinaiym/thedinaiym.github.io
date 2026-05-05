---
layout: page
title: Aesthetics-Aware Makeup Transfer
description: Conditional GAN + rule-based expert system — 14× faster than BeautyGAN, SSIM 0.906
img: assets/img/3.jpg
importance: 2
category: work
---

Research system that overcomes the "blind style transfer" limitation of BeautyGAN by coupling professional makeup domain expertise with a learned generative model.

**Stack:** Python · PyTorch · Mask-Conditioned U-Net · AdaIN · Poisson Image Editing · Stable Diffusion

**Key results:**

- SSIM = 0.906, LPIPS = 0.034 on held-out test set
- Inference latency 0.88 ms on RTX 4080 SUPER (14× faster than BeautyGAN)
- Programmatic paired data generation via Poisson Image Editing — no scarce annotated pairs needed
- Four-experiment comparative study across synthetic, AI-generated, and real-makeup data regimes
- Finding: deterministic synthetic labels outperform AI-generated pairs for pixel-level makeup training

**Paper:** [Preprint (Overleaf)](https://www.overleaf.com/read/jfdcgnhphzfd#1b0730) — _Under Review_
