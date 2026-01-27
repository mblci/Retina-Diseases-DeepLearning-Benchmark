# Retina-Diseases-DeepLearning-Benchmark

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

### Statistical Reliability and Explainability of Modern ConvNeXtV2 and Swin Transformer Architectures in the Classification of Multiple Retinal Diseases based on Fundus Images

This repository contains the official implementation for the benchmarking of modern deep learning architectures (**ConvNeXtV2**, **Swin Transformer**, and **EfficientNetV2**) for the classification of multiple retinal diseases based on fundus images.

## 🌟 Project Highlights & Performance

This study evaluates state-of-the-art architectures not only on raw accuracy but also on **statistical reliability** and **visual explainability (XAI)**.

* [cite_start]**SOTA Performance:** The **ConvNeXtV2-Base** model achieved a **97.14% overall accuracy** and a **0.9692 Macro F1-score**[cite: 13, 28, 42].
* [cite_start]**Pathology-Specific Excellence:** The **Swin Transformer** architecture reached a perfect **100% F1-score** in detecting **Diabetic Retinopathy (DR)**[cite: 14, 29, 310].
* [cite_start]**Operational Efficiency:** Swin-Tiny provides the best balance between speed and performance with an **11.26 ms inference time**, ideal for real-time clinical use[cite: 14, 29, 310].
* [cite_start]**Statistical Rigor:** Validated via **McNemar tests** ($p < 0.05$) and **Bootstrap 95% Confidence Intervals (CI)** to ensure results are systematically superior[cite: 12, 27, 31, 41, 44].
* [cite_start]**Explainable AI (XAI):** Integrated **Grad-CAM** heatmaps to visualize pathological biomarkers like micro-aneurysms, exudates, and optic disc cupping[cite: 12, 27, 33, 41, 46].

## 🛠 Project Overview

* [cite_start]**Dataset:** Evaluated on the **Eye Disease Image Dataset** (Mendeley Data) containing **16,717** images after dynamic augmentation[cite: 10, 23, 24, 38].
* [cite_start]**Classes:** Cataract, Diabetic Retinopathy, Glaucoma, and Healthy[cite: 9, 23, 157].
* [cite_start]**Ablation Study:** Dynamic data augmentation yielded a marginal **5.22% gain** in Macro F1-score[cite: 15, 30, 317, 319].

## 📂 Repository Structure

* [cite_start]`1_Augmented_and_Original_Dataset_3Models.ipynb`: Main training pipeline and benchmark for all three architectures[cite: 151, 237].
* [cite_start]`2_Original_Dataset_Only_ConvNeXt.ipynb`: Ablation study focusing on the impact of data augmentation[cite: 233, 314].
* [cite_start]`3_Evaluation_and_XAI.ipynb`: Advanced statistical analysis (McNemar, CI) and Grad-CAM visualizations[cite: 220, 342, 343].

## 🚀 Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/mblci/Retina-Diseases-DeepLearning-Benchmark.git](https://github.com/mblci/Retina-Diseases-DeepLearning-Benchmark.git)
   cd Retina-Diseases-DeepLearning-Benchmark

## Install dependencies:
* pip install -r requirements.txt

## 📝 Citation
If you find this work or the code useful for your research, please cite:
```bibtex
@article{Balci2026,
  title={Statistical Reliability and Explainability of Modern ConvNeXtV2 and Swin Transformer Architectures in the Classification of Multiple Retinal Diseases Based on Fundus Images},
  author={Balci, Muharrem},
  journal={Submitted to Medical Image Analysis},
  year={2026},
  publisher={GitHub},
  url={https://github.com/mblci/Retina-Diseases-DeepLearning-Benchmark}
}
```

## 📜 License
This project is licensed under the Apache License 2.0.

This means you are free to use, modify, and distribute the code, provided that you give appropriate credit and include the original license file.

See the LICENSE file for the full text of the license.
