# Retina-Diseases-DeepLearning-Benchmark

🎉 **[PUBLISHED]** Our paper **"A comparative analysis of modern CNN and transformer architectures for multi-class retinal disease classification with statistical validation and explainability"** has been officially published in **Neurocomputing (Elsevier)**[cite: 1]! 
🔗 **Read the full paper here:** [https://doi.org/10.1016/j.neucom.2026.134387](https://doi.org/10.1016/j.neucom.2026.134387)[cite: 1]

This repository contains the official implementation for the benchmarking of modern deep learning architectures (ConvNeXtV2, Swin Transformer, and EfficientNetV2) for the classification of multiple retinal diseases based on fundus images[cite: 1].

## 🌟 Project Highlights & Performance

This study evaluates state-of-the-art architectures not only on raw accuracy but also on statistical reliability and visual explainability (XAI)[cite: 1].

*   **SOTA Performance:** The ConvNeXtV2-Base model achieved a 97.14% overall accuracy and a 0.9692 Macro F1-score[cite: 1].
*   **Pathology-Specific Excellence:** The Swin Transformer architecture reached a perfect 100% F1-score in detecting Diabetic Retinopathy (DR)[cite: 1].
*   **Operational Efficiency:** Swin-Tiny provides the best balance between speed and performance with an 11.26 ms inference time, ideal for real-time clinical use[cite: 1].
*   **Statistical Rigor:** Validated via McNemar tests (p<0.05) and Bootstrap 95% Confidence Intervals (CI) to ensure results are systematically superior[cite: 1].
*   **Explainable AI (XAI):** Integrated Grad-CAM heatmaps to visualize pathological biomarkers like micro-aneurysms, exudates, and optic disc cupping[cite: 1].

## 🛠 Project Overview

*   **Dataset:** Evaluated on the Eye Disease Image Dataset (Mendeley Data) containing 16,717 images after dynamic augmentation[cite: 1].
*   **Classes:** Cataract, Diabetic Retinopathy, Glaucoma, and Healthy[cite: 1].
*   **Ablation Study:** Dynamic data augmentation yielded a marginal 5.22% gain in Macro F1-score[cite: 1].

## 📂 Repository Structure

*   `1_Augmented_and_Original_Dataset_3Models.ipynb`: Main training pipeline and benchmark for all three architectures.
*   `2_Original_Dataset_Only_ConvNeXt.ipynb`: Ablation study focusing on the impact of data augmentation.
*   `3_Evaluation_and_XAI.ipynb`: Advanced statistical analysis (McNemar, CI) and Grad-CAM visualizations.

## 🚀 Installation & Usage

Clone the repository:
```bash
git clone [https://github.com/mblci/Retina-Diseases-DeepLearning-Benchmark.git](https://github.com/mblci/Retina-Diseases-DeepLearning-Benchmark.git)
cd Retina-Diseases-DeepLearning-Benchmark

## Install dependencies:
* pip install -r requirements.txt

## 📝 Citation
If you find this work or the code useful for your research, please cite:
```bibtex
@article{Balci2026Neurocomputing,
  title={A comparative analysis of modern CNN and transformer architectures for multi-class retinal disease classification with statistical validation and explainability},
  author={Balcı, Muharrem and Alkan, Ahmet},
  journal={Neurocomputing},
  volume={699},
  pages={134387},
  year={2026},
  publisher={Elsevier},
  doi={10.1016/j.neucom.2026.134387},
  url={[https://doi.org/10.1016/j.neucom.2026.134387](https://doi.org/10.1016/j.neucom.2026.134387)}
}
```






## 📜 License
This project is licensed under the Apache License 2.0.

This means you are free to use, modify, and distribute the code, provided that you give appropriate credit and include the original license file.

See the LICENSE file for the full text of the license.
