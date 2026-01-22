---
title: "FEM for PDE-Constrained Optimization in Heat Conduction"
date: 2024-06-18T00:00:00Z

summary: "Applying finite element methods and convex optimization to sequential PDE-constrained problems in heat conduction (SAND-style formulation)."
tags: ["Finite Element Method", "PDE-Constrained Optimization","Convex Optimization"]
featured: true
share: false
links:
  - name: Code
    url: "https://github.com/caiyf03/APPLICATION-OF-FEM-IN-SOLVING-PDE-CONSTRAINED-OPTIMIZATION-FOR-HEAT-CONDUCTION-PROBLEM"
  - name: Report (PDF)
    url: "https://github.com/caiyf03/APPLICATION-OF-FEM-IN-SOLVING-PDE-CONSTRAINED-OPTIMIZATION-FOR-HEAT-CONDUCTION-PROBLEM/blob/main/computerscience%20(Finalversion).pdf"

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
This project applies finite element methods (FEM) to solve partial differential equation (PDE)–constrained optimization problems arising in heat conduction scenarios. Motivated by theoretical foundations from Computational Science and Engineering and Numerical Optimization, the study explores how numerical optimization and PDE discretization interact in practice. Through a series of thermodynamic case studies, the work demonstrates how FEM can be combined with control and optimization techniques to analyze temperature distributions and infer internal heat sources under PDE constraints. All computational implementations are developed from first principles and tailored to the specific thermal problems considered.

## Methods
The approach begins with formulating the heat conduction problems as PDE-constrained optimization problems, where the objective typically involves minimizing discrepancies in temperature fields or control costs subject to the governing heat equation. The PDEs are discretized using the finite element method, enabling numerical solution of both the state and adjoint equations. Optimization is then performed over control parameters using standard numerical solvers embedded within the FEM framework. Through iterative solution of PDE states and optimization updates, the project integrates FEM discretization with convex optimization strategies to handle constraints effectively across each case study.





