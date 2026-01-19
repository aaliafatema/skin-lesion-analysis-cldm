# Skin Lesion Analysis and Prognostic Modeling (CLDM)

Great, thanks — I understand your situation clearly now 👍
You have **code notebooks + dataset zip + paper + PPTs + Turnitin report**, and you want a **proper GitHub README** that explains everything **cleanly and academically**.

Below is a **ready-to-use `README.md`** written **specifically for the files you uploaded** and suitable for:

* capstone submission
* GitHub public repo
* academic review

You can **copy–paste this directly into `README.md`** in VS Code.

---

# Skin Lesion Analysis and Prognostic Modeling using Deep Learning (CLDM)

## 📌 Overview

This repository contains the implementation artifacts, experiments, and documentation related to the project **“A Comprehensive Review on Skin Lesion Analysis and Prognostic Modeling using Deep Learning”**.
The work focuses on automated skin lesion analysis using deep learning and proposes a **conceptual Conditional Latent Diffusion Prognostic Framework (CLDM)** for forecasting lesion progression.

The repository includes:

* Jupyter notebooks for skin lesion analysis
* Dataset references (HAM10000)
* Research paper (camera-ready)
* Presentation slides
* Turnitin similarity report

⚠️ **Note:** This project is intended for **academic and research purposes only** and is **not a clinical diagnostic tool**.

---

## 📂 Repository Structure

```text
├── Skin_Lesion.ipynb            # Main notebook for skin lesion analysis
├── temp_model.ipynb             # Experimental / prototype model notebook
├── Reseach_Paper.pdf   # Final research paper
├── Presentation.pptx            # Project presentation slides
├── Turnitin_Report.pdf          # Similarity / plagiarism report
├── README.md                    # Project documentation
```

---

## 🧠 Project Objectives

* Study and compare **traditional ML vs deep learning** approaches for skin lesion classification
* Analyze challenges such as:

  * Class imbalance
  * Data scarcity
  * Lack of interpretability
* Propose a **future-ready prognostic framework (CLDM)** using:

  * U-Net segmentation
  * Latent diffusion models
  * Uncertainty quantification

---

## 📊 Dataset

* **HAM10000 (Human Against Machine with 10000 training images)**
* Contains dermoscopic images across **7 skin lesion classes**
* Known challenge: **severe class imbalance**, especially for melanoma

> Due to licensing and size constraints, the dataset may need to be downloaded separately.

---

## ⚙️ Methodology Summary

### 1. Preprocessing

* Image resizing and normalization
* Data augmentation to reduce overfitting
* Handling class imbalance using weighted learning and augmentation

### 2. Segmentation

* Conceptual use of **U-Net** for lesion region extraction
* Removes background artifacts (hair, rulers, illumination)

### 3. Classification

* CNN-based architectures
* Comparison with traditional ML methods (SVM, Random Forest)

### 4. Prognostic Modeling (Conceptual)

* **Conditional Latent Diffusion Model (CLDM)**
* Forecasts lesion evolution at:

  * 6 months
  * 12 months
  * 24 months
* Generates **uncertainty heatmaps** to improve interpretability

---

## 📈 Key Contributions

* Comprehensive literature review (2019–2025)
* Identification of clinical deployment challenges
* Proposal of a **hybrid prognostic framework**
* Focus on **explainable and uncertainty-aware AI**

---

## 🧪 Notebooks Description

### `Skin_Lesion.ipynb`

* Data loading and preprocessing
* Exploratory analysis
* Baseline deep learning pipeline
* Evaluation metrics

### `temp_model.ipynb`

* Experimental / prototype models
* Used for testing alternative ideas and architectures

---

## 📝 Research Paper

The full paper is available as:

📄 **453_Camera_Ready_Paper.pdf**

**Title:**
*A Comprehensive Review on Skin Lesion Analysis and Prognostic Modeling using Deep Learning*

**Authors:**
Aalia Fatema Dandawala, Vedant Jadhav, Raj Shukla, Dr. Prashasti Kanikar

---

## 📽 Presentation

The project presentation (`.pptx`) summarizes:

* Problem motivation
* Literature findings
* Proposed CLDM framework
* Comparative analysis
* Conclusion and future work

---

## 🔍 Turnitin Report

The Turnitin similarity report is included for **academic transparency** and institutional submission requirements.

---

## 🚀 How to Run 

```bash
pip install numpy pandas matplotlib scikit-learn tensorflow torch
jupyter notebook
google colab
```

Then open:

* `Skin_Lesion.ipynb`

---

Dataset:
https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000

## ⚠️ Disclaimer

This repository is created **strictly for academic evaluation and research**.
It is **not approved for medical or clinical use**.

---



