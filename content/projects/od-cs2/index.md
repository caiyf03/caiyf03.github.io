---
title: "Object Detection in Counter-Strike 2"
date: 2024-01-22T00:00:00Z

summary: "Applying and comparing object detection algorithms in Counter-Strike 2 for reliable player/weapon detection under complex in-game scenarios."
tags: ["Computer Vision", "Object Detection", "Deep Learning", "CS2"]
featured: true
share: false
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
This project investigates the application of real-time object detection in Counter-Strike 2 (CS2). We build a custom in-game dataset and systematically compare multiple detection frameworks to evaluate their accuracy, speed, and practicality in dynamic gaming scenarios. Beyond benchmarking, we demonstrate how detection results can be integrated into gameplay-related applications such as distance estimation and automated aiming.

## Methods
We implement and compare YOLOv7, Faster R-CNN, and SSD.
Key components include:

-Construction of a custom VOC-style CS2 dataset from gameplay footage

-Model training and evaluation under identical settings

-Preprocessing and data augmentation for difficult scenes

-Ensemble-style bounding box fusion using confidence weighting and clustering


## Key Features
-Custom-built CS2 object detection dataset

-Comparative study of one-stage vs. two-stage detectors

-Model ensemble via weighted bounding box averaging

-Real-time in-game deployment with screen capture

-Applications including auto-aiming and target distance estimation

---
<figure style="text-align: center; margin-bottom: 2rem;">
  <img src="1.png"
       alt=""
       style="width: 100%; max-width: 650px;" />
  <figcaption style="margin-top: 0.5rem; font-size: 0.9rem; color: #555;">
  </figcaption>
</figure>
<figure style="text-align: center; margin-bottom: 2rem;">
  <img src="2.png"
       alt=""
       style="width: 100%; max-width: 650px;" />
  <figcaption style="margin-top: 0.5rem; font-size: 0.9rem; color: #555;">
  </figcaption>
</figure>

