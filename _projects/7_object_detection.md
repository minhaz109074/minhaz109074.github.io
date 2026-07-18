---
layout: page
title: Custom Face Mask Detectors (YOLO & SSD)
description: YOLO and SSD object detection architectures implemented from scratch for real-time face mask detection.
# img: assets/img/12.jpg
importance: 7
category: Research & ML
---

**Technologies:** Python, PyTorch, OpenCV, YOLO, SSD, RoboFlow

[GitHub](https://github.com/minhaz109074/Object-detection){: .btn .btn-sm .btn--primary target="_blank"}

---

### Overview

Implemented **YOLO (You Only Look Once)** and **SSD (Single Shot Detector)** object detection architectures from scratch as part of the undergraduate thesis on lightweight, real-time face mask detection systems.

### Key Contributions

- **Architecture Implementation:** Built both YOLO and SSD detection networks from scratch using PyTorch, including custom backbone networks, anchor box configurations, and loss functions (localization + classification).

- **Real-Time Detection:** Optimized both architectures to run at real-time frame rates on CPU/GPU, making them suitable for deployment in edge environments.

- **Comparative Evaluation:** Rigorously benchmarked both architectures on the same face mask dataset, comparing mAP, inference speed, and computational requirements to determine deployment suitability.

- **Dataset Preparation:** Used **RoboFlow** for dataset annotation, augmentation, and preprocessing, ensuring high-quality training data.

### Related Publication

> *A Comparative Study of Lightweight Face Mask Detectors for Real-Time Applications* — Undergraduate Thesis, NSTU 2022. [View Thesis PDF](https://drive.google.com/file/d/1KjnnSRnfcvAE_ze2R0nYLBdGWFxXOhIE/view?usp=sharing)
