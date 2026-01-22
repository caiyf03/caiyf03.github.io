---
title: "Structure-Based Drug Design via Diffusion Models Guided by Non-Differentiable Metrics"

authors:
  - me

date: "2025-05-01T00:00:00Z"
publishDate: "2025-05-01T00:00:00Z"

publication_types: ["thesis"]

publication: "*Undergraduate Thesis*"
publication_short: "Undergraduate Thesis"

summary: "Undergraduate thesis on diffusion-based structure-based drug design guided by non-differentiable metrics."
abstract: "This work introduces a diffusion-guided molecular generation approach that seamlessly
incorporates non-differentiable metrics—such as empirical property scores or domain
heuristics—into the sampling process. Unlike traditional gradient-based optimization,
our method leverages a conditional diffusion prior and a gradient-free feedback loop to
navigate chemical space effectively, producing candidate molecules with enhanced validity
and alignment with multiple design objectives. This project highlights how generative
diffusion frameworks can be adapted for realistic drug design scenarios where scoring
functions are irregular, discontinuous, or otherwise non-differentiable.
"

tags:
  - Diffusion Models
  - Drug Design

featured: false

links:
  - type: code
    url: "https://github.com/caiyf03/Diffusion-model-based-drug-design-guided-by-non-differentiable-metrics."
  - type: pdf
    url: "https://github.com/caiyf03/Diffusion-model-based-drug-design-guided-by-non-differentiable-metrics./blob/main/%E8%94%A1%E9%80%B8%E5%87%A1-2021533087-%E5%9F%BA%E4%BA%8E%E4%B8%8D%E5%8F%AF%E5%BE%AE%E6%8C%87%E6%A0%87%E5%BC%95%E5%AF%BC%E6%89%A9%E6%95%A3%E6%A8%A1%E5%9E%8B%E7%9A%84%E7%BB%93%E6%9E%84%E8%8D%AF%E7%89%A9%E8%AE%BE%E8%AE%A1.pdf"
---
## Method Overview

<figure style="text-align: center; margin-bottom: 2rem;">
  <img src="SPSA.png"
       alt="Zero-order Optimization via Gradient Approximation (SPSA)"
       style="width: 100%; max-width: 520px;" />
  <figcaption style="margin-top: 0.5rem; font-size: 0.9rem; color: #555;">
    <strong>Zero-order Optimization via Gradient Approximation (SPSA)</strong>
  </figcaption>
</figure>

<figure style="text-align: center;">
  <img src="ATP.png"
       alt="Adaptive Trajectory Pruning (ATP)"
       style="width: 100%; max-width: 520px;" />
  <figcaption style="margin-top: 0.5rem; font-size: 0.9rem; color: #555;">
    <strong>Adaptive Trajectory Pruning (ATP)</strong>
  </figcaption>
</figure>


