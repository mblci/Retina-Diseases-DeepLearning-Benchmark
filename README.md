# Retina-Diseases-DeepLearning-Benchmark

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

### Statistical Reliability and Explainability of Modern ConvNeXtV2 and Swin Transformer Architectures in the Classification of Multiple Retinal Diseases based on Fundus Images

[cite_start]This repository contains the official implementation for the benchmarking of modern deep learning architectures (**ConvNeXtV2**, **Swin Transformer**, and **EfficientNetV2**) for the classification of multiple retinal diseases based on fundus images[cite: 11, 25, 39].



## 🌟 Project Highlights & Performance

[cite_start]This study evaluates state-of-the-art architectures not only on raw accuracy but also on **statistical reliability** and **visual explainability (XAI)**[cite: 12, 41].

* [cite_start]**SOTA Performance:** The **ConvNeXtV2-Base** model achieved a **97.14% overall accuracy** and a **0.9692 Macro F1-score**[cite: 13, 28, 42].
* [cite_start]**Pathology-Specific Excellence:** The **Swin Transformer** architecture reached a perfect **100% F1-score** in detecting **Diabetic Retinopathy (DR)**[cite: 14, 29, 43, 276].
* [cite_start]**Operational Efficiency:** Swin-Tiny provides the best balance between speed and performance with an **11.26 ms inference time**, ideal for real-time clinical use[cite: 14, 29, 333, 335].
* [cite_start]**Statistical Rigor:** Validated via **McNemar tests** ($p < 0.05$) and **Bootstrap 95% Confidence Intervals (CI)** to ensure results are systematically superior[cite: 31, 41, 97, 286].
* [cite_start]**Explainable AI (XAI):** Integrated **Grad-CAM** heatmaps to visualize pathological biomarkers like micro-aneurysms, exudates, and optic disc cupping[cite: 12, 101, 220, 343].



## 🛠 Project Overview

* [cite_start]**Dataset:** Evaluated on the **Eye Disease Image Dataset** (Mendeley Data) containing **16,717** images after dynamic augmentation[cite: 23, 24, 38, 158].
* [cite_start]**Classes:** Cataract, Diabetic Retinopathy, Glaucoma, and Healthy[cite: 9, 21, 37, 157].
* [cite_start]**Ablation Study:** Dynamic data augmentation yielded a marginal **5.22% gain** in Macro F1-score[cite: 15, 30, 44, 317].

## 📂 Repository Structure

* `1_Augmented_and_Original_Dataset_3Models.ipynb`: Main training pipeline and benchmark for all three architectures.
* `2_Original_Dataset_Only_ConvNeXt.ipynb`: Ablation study focusing on the impact of data augmentation.
* `3_Evaluation_and_XAI.ipynb`: Advanced statistical analysis (McNemar, CI) and Grad-CAM visualizations.

## 🚀 Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/mblci/Retina-Diseases-DeepLearning-Benchmark.git](https://github.com/mblci/Retina-Diseases-DeepLearning-Benchmark.git)
   cd Retina-Diseases-DeepLearning-Benchmark
