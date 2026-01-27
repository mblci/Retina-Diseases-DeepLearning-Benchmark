# Retina-Diseases-DeepLearning-Benchmark

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

### Statistical Reliability and Explainability of Modern ConvNeXtV2 and Swin Transformer Architectures in the Classification of Multiple Retinal Diseases based on Fundus Images

This repository contains the official implementation for the benchmarking of modern deep learning architectures (**ConvNeXtV2**, **Swin Transformer**, and **EfficientNetV2**) for the classification of multiple retinal diseases based on fundus images.

## 🌟 Project Highlights & Performance
This study evaluates state-of-the-art architectures not only on raw accuracy but also on **statistical reliability** and **visual explainability (XAI)**.

* **SOTA Performance:** The **ConvNeXtV2-Base** model achieved a **97.14% overall accuracy** and a **0.9692 Macro F1-score**.
* **Pathology-Specific Excellence:** The **Swin Transformer** architecture reached a perfect **100% F1-score** in detecting **Diabetic Retinopathy (DR)**.
* **Operational Efficiency:** Swin-Tiny provides the best balance between speed and performance with an **11.26 ms inference time**, ideal for real-time clinical use.
* **Statistical Rigor:** Validated via **McNemar tests** ($p < 0.05$) and **Bootstrap 95% Confidence Intervals (CI)** to ensure results are systematically superior.
* **Explainable AI (XAI):** Integrated **Grad-CAM** heatmaps to visualize pathological biomarkers like micro-aneurysms, exudates, and optic disc cupping.

## 🛠 Project Overview
* **Dataset:** Evaluated on the **Eye Disease Image Dataset** (Mendeley Data) containing **16,717** images after dynamic augmentation.
* **Classes:** Cataract, Diabetic Retinopathy, Glaucoma, and Healthy.
* **Ablation Study:** Dynamic data augmentation yielded a marginal **5.22% gain** in Macro F1-score.

## 📂 Repository Structure
* `1_Augmented_and_Original_Dataset_3Models.ipynb`: Main training pipeline and benchmark for all three architectures.
* `2_Original_Dataset_Only_ConvNeXt.ipynb`: Ablation study focusing on the impact of data augmentation.
* `3_Evaluation_and_XAI.ipynb`: Advanced statistical analysis (McNemar, CI) and Grad-CAM visualizations.

## 🚀 Installation & Usage
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/mblci/Retina-Diseases-DeepLearning-Benchmark.git](https://github.com/mblci/Retina-Diseases-DeepLearning-Benchmark.git)
    cd Retina-Diseases-DeepLearning-Benchmark
    ```
2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## 📝 Citation
If you find this work or the code useful for your research, please cite:

```bibtex
@article{Balci2026,
  title={Statistical Reliability and Explainability of Modern ConvNeXtV2 and Swin Transformer Architectures in the Classification of Multiple Retinal Diseases Based on Fundus Images},
  author={Balci, Muharrem and Aykut, Ali},
  journal={Submitted to Medical Image Analysis},
  year={2026},
  publisher={GitHub},
  url={[https://github.com/mblci/Retina-Diseases-DeepLearning-Benchmark](https://github.com/mblci/Retina-Diseases-DeepLearning-Benchmark)}
}


---

## 📜 License

This project is licensed under the **Apache License 2.0**.  
This means you are free to use, modify, and distribute the code, provided that you give appropriate credit and include the original license file. 

See the [LICENSE](LICENSE) file for the full text of the license.
