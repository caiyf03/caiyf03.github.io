---
title: "Object Detection in Counter-Strike 2"
date: 2024-12-01T00:00:00Z

summary: "Applying and comparing object detection algorithms in Counter-Strike 2 for reliable player/weapon detection under complex in-game scenarios."
tags: ["Computer Vision", "Object Detection", "Deep Learning", "CS2"]
featured: true

links:
  - name: Code
    url: "https://github.com/caiyf03/The-Application-and-Comparison-of-Object-Detection-Algorithm-in-Counter-Strike-2"
  - name: Report (PDF)
    url: "https://github.com/caiyf03/The-Application-and-Comparison-of-Object-Detection-Algorithm-in-Counter-Strike-2/blob/main/IML_project%20(1).pdf"
  - name: Demo Video
    url: "https://www.bilibili.com/video/BV1oT4y147je/?vd_source=543fdb1fad79958233adddab9901d6f3"  # 若有 demo 可填，否则删掉

image:
  caption: "Object detection results on Counter-Strike 2 frames"
  focal_point: ""
  preview_only: false
---
## Team
- YiFan Cai (leader)
- XiHe Yu
- Yu Shi

## Overview
This project explores the **application and comparison of modern object detection algorithms** in the context of **Counter-Strike 2 (CS2)** gameplay imagery. It includes:

- Dataset preparation from CS2 gameplay
- Training and evaluation of multiple object detection models
- Quantitative and qualitative comparisons

## Methods
We evaluated several detection architectures including:

- **YOLOv5 / YOLOv8**
- **Faster R-CNN**
- **SSD**
- Other variants (as implemented in the repository)

The evaluation reports both detection accuracy and run-time performance in diverse CS2 scenes.

## Results
- Precision / recall results on annotated CS2 frames
- Visual comparisons of detection output overlays
- Per-class metrics for players, weapons, and other targets

---

