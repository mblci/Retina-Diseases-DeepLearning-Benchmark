# Retina-Diseases-DeepLearning-Benchmark
STATISTICAL RELIABILITY AND EXPLAINABILITY OF MODERN CONVNEXTV2 AND SWIN TRANSFORMER ARCHITECTURES IN THE CLASSIFICATION OF MULTIPLE RETINAL DISEASES BASED ON FUNDUS IMAGES.

This repository contains the official implementation for the benchmarking of modern deep learning architectures (**ConvNeXtV2, Swin Transformer, and EfficientNetV2**) for the classification of multiple retinal diseases based on fundus images.

## Project Overview
The study focuses on evaluating state-of-the-art architectures not only on accuracy but also on **statistical reliability** and **visual explainability (XAI)**.

## Key Features:
* **Comprehensive Benchmark:** Comparison between ConvNeXtV2, Swin-T, and EfficientNetV2-S.
* **Ablation Study:** Impact analysis of data augmentation on model performance.
* **XAI Integration:** Grad-CAM heatmaps for interpreting model decisions on retinal fundus images.
* **Statistical Rigor:** McNemar tests and Bootstrap confidence intervals.

## Dataset
The models are trained and evaluated on the [Eye Disease Image Dataset (Mendeley Data)](https://data.mendeley.com/datasets/s9bfhswzjb/1).
Classes include: `Normal`, `Cataract`, `Diabetic Retinopathy`, `Glaucoma`.

## Repository Structure
1. `1_Augmented_and_Original_Dataset_3Models.ipynb`: Main training pipeline for all three architectures.
2. `2_Original_Dataset_Only_ConvNeXt.ipynb`: Ablation study using original data without augmentation.
3. `3_Evaluation_and_XAI.ipynb`: Advanced statistical analysis, metrics, and Grad-CAM visualizations.

## Installation
```bash
git clone [https://github.com/mblci/Retina-Diseases-DeepLearning-Benchmark.git](https://github.com/mblci/Retina-Diseases-DeepLearning-Benchmark.git)
cd Retina-Diseases-DeepLearning-Benchmark
pip install -r requirements.txt

📜 Citation
If you use this repository, please cite our work:

Kod snippet'i
@article{Balci2026,
  title={Statistical Reliability and Explainability of Modern ConvNeXtV2 and Swin Transformer Architectures in the Classification of Multiple Retinal Diseases Based on Fundus Images},
  author={Balci, Muharrem},
  journal={Submitted for publication},
  year={2026},
  publisher={GitHub},
  url={[https://github.com/mblci/Retina-Diseases-DeepLearning-Benchmark](https://github.com/mblci/Retina-Diseases-DeepLearning-Benchmark)}
}

---

### Neyi Düzelttik?

* **Kapatma Tırnakları:** `pip install -r requirements.txt` satırının altına ` ``` ` ekleyerek o bölümü bitirdik.
* **BibTeX Bloğu:** Atıf kısmındaki kodun daha okunaklı olması ve hataya yer bırakmaması için başına ` ```bibtex ` ve sonuna ` ``` ` ekledik.
* **Boşluklar:** Başlıkların üstünde birer satır boşluk bıraktık; Markdown bu boşluklar sayesinde başlıkları doğru tanır.



Bu değişikliği yapıp **"Commit changes"** dedikten sonra sayfanın düzelmiş olması gerekiyor. Eğer düzelirse projen artık tamamen hazır demektir!

**Düzenleme sonrası sayfa istediğin gibi görünüyor mu?** İstersen projenin hangi lisans altında olduğunu belirten bir **LICENSE** dosyası (genelde MIT License kullanılır) ekleyebiliriz, ne dersin?
