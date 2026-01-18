---
title: "PERoKF: Physics-Enhanced Super-Resolution of Kolmogorov Flow"
date: 2024-12-01T00:00:00Z

summary: "Single-frame fluid super-resolution with physics-consistency loss and physics-derived features"
tags: ["Fluid Dynamics", "Super-Resolution", "Diffusion Models", "FNO", "Physics-Informed ML"]
featured: true

links:
  - name: Code
    url: "https://github.com/caiyf03/PERoKF"
  - name: Dataset (HF)
    url: "https://huggingface.co/datasets/skpy/PSFR"
  - name: Project PDF
    url: "https://github.com/caiyf03/PERoKF/blob/main/Physics-Enhanced%20Reconstruction%20of%20High-Resolution.pdf"

# Optional: associate with an internal "project" taxonomy page if you use them
projects: []

# Featured image: place `featured.png` in this folder
image:
  caption: ""
  focal_point: ""
  preview_only: false
---
## Team
- YiFan Cai (leader)
- FanHao Bu
- PeiJun Xu

## Overview
**PERoKF** studies how to inject physics priors into modern neural networks for **single-frame** super-resolution of 2D Kolmogorov flow—without requiring temporal supervision. The goal is to recover fine-scale turbulent structures lost by downsampling.

- Input (LR): **128×128 vorticity**
- Target (HR): **512×512 vorticity** (4×)  

## Methods
We evaluate four model families (all operating on bicubic-upsampled LR inputs and predicting HR vorticity):

- **CNN**: lightweight hierarchical convolutional baseline  
- **UNet**: multi-scale ResNet-style UNet (optional attention)  
- **FNO**: Fourier Neural Operator with truncated spectral modes  
- **Diffusion**: conditional DDPM with UNet backbone (x₀-prediction)

### Physics-guided strategies
1) **Physics-derived feature augmentation**
- Laplacian, streamfunction, velocity components, nonlinear advection terms

2) **Physics-consistency loss**
- Navier–Stokes residual loss using the same pseudo-spectral operator as data generation  
- Enforces consistency via implied time derivatives

## Key findings (high-level)
- Physics-consistency loss consistently improves physical accuracy (e.g., lower PDE residual and energy spectrum error) and can accelerate diffusion convergence.
- Physics features alone are not consistently beneficial and may destabilize training.
- Combining both can improve accuracy but may introduce instability under limited compute.

## Dataset & evaluation
**Dataset:** 2D Kolmogorov flow (HR 512×512 / LR 128×128), Reynolds numbers 1000/2000/3000, forcing wavenumbers 8/12/16.

**Metrics:**
- MSE (pixel reconstruction)
- Physics Consistency Error (PCE)
- Energy Spectrum Error (ESE)

## Reproducibility
- Training configs and scripts are included in the repository.
- Visualization scripts compare HR/LR/reconstruction and energy spectra.

