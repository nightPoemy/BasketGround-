
# 🏀 BasketGround: A Multi-dimensional Vision-Language Dataset for
Basketball Video Analysis

<p align="center">
  <b>Cross-architecture Knowledge Distillation for Lightweight Video Models</b><br>
  A Large-Scale Benchmark for Fine-Grained Basketball Video Understanding
</p>

---

## 📌 Overview

We present **BASKET**, a large-scale dataset for **visual-evidence-based spatio-temporal grounding** in basketball videos.

Unlike existing datasets, BASKET focuses on **fine-grained semantic understanding** in highly dynamic, multi-player sports scenarios. Each sample requires models to jointly reason about:

- 🧑 Player identity  
- 🏀 Actions and interactions  
- 📍 Spatial-temporal localization  

This benchmark introduces significant challenges due to **occlusions, viewpoint changes, and similar appearances among players**, making it a strong testbed for multimodal reasoning.

---

## 🎯 Key Features

- 🔹 **Multi-entity reasoning**: identity + action + spatial grounding  
- 🔹 **Fine-grained annotations**: player name, team, jersey color, number  
- 🔹 **Challenging scenarios**: occlusion, fast motion, multi-player interaction  
- 🔹 **Evaluation protocols**: VEA, mTIoU, mVIoU  
- 🔹 **Real-world basketball games**

---

## 📊 Dataset Statistics

| Split | Videos | Samples | Annotations |
|------|--------|--------|------------|
| Train | XXX | XXX | XXX |
| Val   | XXX | XXX | XXX |
| Test  | XXX | XXX | XXX |

> 📌 *Detailed statistics will be updated upon release.*

---

## 🧠 Task Definition

### 🔹 Task 1: Attribute Prediction
Predict player-related attributes:
- Player Name
- Team
- Jersey Color
- Jersey Number

### 🔹 Task 2: Spatio-Temporal Grounding
Given a textual query, localize:
- ⏱ Temporal segment  
- 📦 Spatial region  

---

## 📏 Evaluation Metrics

We propose a unified evaluation framework:

- **VEA (Visual Evidence Accuracy)**
- **mTIoU (mean Temporal IoU)**
- **mVIoU (mean Visual IoU)**

We also evaluate **conditional localization performance under different VEA levels**.

---

## 📂 Dataset Structure

BASKET/
│── videos/
│── annotations/
│ ├── train.json
│ ├── val.json
│ └── test.json
│── metadata/
│── splits/


## 📥 Download

🚧 The dataset will be released upon acceptance.

(Anonymous version for review: [LINK])
