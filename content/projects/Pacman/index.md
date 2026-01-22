---
title: "Building an Intelligent Pac-Man Agent"
date: 2023-10-01T00:00:00Z

summary: "Incrementally upgrading a Pac-Man agent from rule-based planning to probabilistic reasoning and reinforcement learning, forming a complete AI decision-making pipeline."
tags: ["Artificial Intelligence","Reinforcement Learning"]
featured: true
share: false
links:
  - name: Code
    url: "https://github.com/caiyf03/pacman/tree/main"

image:
  caption: "Evolution of Pac-Man intelligence across planning, inference, and learning"
  focal_point: ""
  preview_only: false
---
## Overview
This project series incrementally develops a **fully autonomous Pac-Man agent**, transforming it from a weak, rule-driven system into an intelligent decision-making agent capable of planning, reasoning under uncertainty, and learning from interaction.

The projects are organized as a coherent progression, each introducing a more advanced AI paradigm.

## Logic & Classical Planning
In the initial stage, Pac-Man operates under **logic-based representations and classical planning**:

- Explicit modeling of world states, actions, constraints, and goals  
- Automatic generation of feasible action sequences  
- Deterministic planning in fully observable environments  

This stage establishes the foundation for symbolic reasoning and goal-directed behavior.

## Bayesian Networks
To handle uncertainty, **Bayesian networks** are introduced:

- Probabilistic modeling of hidden variables  
- Inference under noisy or incomplete observations  
- Decision-making based on belief states rather than exact knowledge  

This enables Pac-Man to reason probabilistically instead of relying on fixed rules.

## Ghostbusters: Tracking Under Uncertainty
In the **Ghostbusters** setting, Pac-Man faces invisible ghosts and noisy sensors:

- Bayesian filtering for belief state updates  
- Particle filtering for continuous ghost localization  
- Sequential decision-making in partially observable, dynamic environments  

This stage bridges probabilistic inference and adversarial game dynamics.

## Reinforcement Learning
Finally, the agent transitions to **reinforcement learning**, removing the need for handcrafted models:

- Learning policies directly from environment interaction  
- Optimizing long-term rewards instead of immediate objectives  
- Adapting behavior through trial and error  

At this stage, Pac-Man becomes a self-improving agent capable of autonomous strategy learning.

