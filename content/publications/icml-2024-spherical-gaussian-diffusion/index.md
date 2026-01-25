---
title: "Guidance with Spherical Gaussian Constraint for Conditional Diffusion"

authors:
  # - "J. Yu"
  # - "J. Wang"
  # - "Y. Shi"
  - me

date: "2024-01-01T00:00:00Z"
publishDate: "2024-01-01T00:00:00Z"

publication_types: ["paper-conference"]

publication: 'In *Proceedings of the 41st International Conference on Machine Learning (ICML 2024)*. PMLR, 202.'
publication_short: "ICML 2024"

summary: "ICML 2024 paper on conditional diffusion with a spherical Gaussian constraint."
abstract: "This work analyzes the limitations of loss-guided conditional diffusion models, showing that their performance degradation originates from manifold deviation during sampling. We theoretically establish a lower bound on the estimation error of loss guidance, revealing the inevitability of this deviation. To address this issue, we propose Diffusion with Spherical Gaussian constraint (DSG), which constrains guidance steps within the intermediate data manifold by leveraging high-dimensional Gaussian concentration. DSG admits a closed-form denoising solution, supports larger guidance steps, and can be seamlessly integrated into existing training-free diffusion methods with negligible overhead. Extensive experiments demonstrate that DSG significantly improves both sample quality and sampling efficiency across diverse conditional generation tasks."

tags:
  - Diffusion Models
  - Machine Learning

featured: false

links:
  - type: source
    url: "https://icml.cc/virtual/2024/poster/33898"
  - type: code
    url: "https://github.com/LingxiaoYang2023/DSG2024"
  - type: pdf
    url: "https://openreview.net/pdf?id=VtqyurB4Af"
---

<figure style="text-align: center; margin-bottom: 2rem;">
  <img src="fianl_fff.jpg"
       alt=""
       style="width: 100%; max-width: 650px;" />
  <figcaption style="margin-top: 0.5rem; font-size: 0.9rem; color: #555;">
  </figcaption>
</figure>

<figure style="text-align: center;">
  <img src="three_target.jpg"
       alt=""
       style="width: 100%; max-width: 650px;" />
  <figcaption style="margin-top: 0.5rem; font-size: 0.9rem; color: #555;">
  </figcaption>
</figure>
