# 📸 [CVPR 2025] The-Photographers-Eye
**The Photographer's Eye: Teaching Multimodal Large Language Models to See, and Critique Like Photographers**

> Official repository for the CVPR 2025 paper:  
> [The Photographer's Eye: Teaching Multimodal Large Language Models to See, and Critique Like Photographers](https://openaccess.thecvf.com/content/CVPR2025/papers/Qi_The_Photographers_Eye_Teaching_Multimodal_Large_Language_Models_to_See_CVPR_2025_paper.pdf)

---

## 🔍 Overview
We introduce **The Photographer’s Eye (PhotoEye)**, a multimodal large language model trained to *see* and *critique* photographs like professional photographers.

<p align="center">
  <img src="head.pdf" alt="Overview examples of user-model interactions" width="700"/>
</p>

---

## 📊 Dataset: PhotoCritique
We release **PhotoCritique**, a large-scale instruction-tuning dataset with ~2.63M samples.

### From Raw Comments to Structured Critique
<p align="center">
  <img src="app_1.pdf" alt="Example pipeline: from raw comments to critique" width="650"/>
</p>

### Example Data
<p align="center">
  <img src="pc.pdf" alt="PhotoCritique examples" width="650"/>
</p>

### Diversity of Images
<p align="center">
  <img src="imgs.pdf" alt="Diversity of images in PhotoCritique" width="650"/>
</p>

---

## 🧠 Model: PhotoEye
We propose **PhotoEye**, which fuses visual representations from multiple vision encoders under language guidance.

<p align="center">
  <img src="fw.pdf" alt="PhotoEye model architecture" width="700"/>
</p>

---

## 📈 Benchmark: PhotoBench
We evaluate on **PhotoBench**, a benchmark covering hundreds of sub-topics across aesthetics, composition, exposure, post-processing, etc.

### Example Questions
<p align="center">
  <img src="bench.pdf" alt="PhotoBench examples" width="700"/>
</p>

---

## 📂 Resources
- Due to company policy, the **PhotoCritique** dataset cannot be publicly released at this time.  
  However, in our paper we provide a detailed description of how to derive PhotoCritique from the original DPChallenge dataset, **DPC2022** ([paper](https://arxiv.org/pdf/2211.15378)).  
  The DPC2022 dataset can be downloaded here: [Google Drive](https://drive.google.com/drive/folders/1KqZZCwdA3hw09jkavmJYjID_qeibRXwM?usp=drive_link).

- **PhotoBench**: [Google Drive](https://drive.google.com/file/d/1vFQA3Lrj3USukwKhhQm3cTGjpooHzMlu/view?usp=drive_link).  
  This version is a subset filtered using an LLM.  
  A future release may include a version curated by expert human annotators.
