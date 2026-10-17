# 🩺 Disease Prediction from Medical Data — Production Machine Learning Pipeline

[![Python 3.10+](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org/)
[![CodeAlpha](https://img.shields.io/badge/CodeAlpha-Internship-orange.svg)](https://www.codealpha.tech/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.x-blue.svg)](https://scikit-learn.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📌 Executive Summary
This repository delivers an enterprise-grade Machine Learning and Diagnostic Inference pipeline for **Disease Prediction from Medical Data**. Developed for the **CodeAlpha Machine Learning Internship**, the system processes patient symptom indicators, maps clinical severity indices, evaluates multi-model classifiers (Decision Tree, Random Forest, SVM, Gradient Boosting), performs 5-fold cross-validation, and provides an end-to-end clinical inference engine that predicts target disease diagnoses along with disease descriptions and medical precautions.

---

## 🛠 Project Architecture & File Structure

```
CodeAlpha_DiseasePredictionFromMedicalData/
│
├── 📊 Disease_Prediction_EDA_Granular_EN.ipynb # Publication-Grade Exploratory Data Analysis
├── 🚀 Disease_Prediction_ML_Granular_EN.ipynb  # Multi-Model ML Training & Inference Pipeline
├── 📦 disease_prediction_model.joblib          # Serialized Trained Random Forest Model Artifact
├── 📄 dataset.csv                              # Patient Symptom Diagnoses Dataset
├── 📄 Symptom-severity.csv                     # Symptom Clinical Weight Indices
├── 📄 symptom_Description.csv                  # Disease Clinical Descriptions
├── 📄 symptom_precaution.csv                   # Recommended Medical Precautions
└── 📝 README.md                                # Project Documentation
```

---

## 🔬 Multi-Model Benchmark Results

| Model Classifier | Accuracy | Precision (Weighted) | Recall (Weighted) | F1-Score (Weighted) | 5-Fold CV Mean |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Random Forest Classifier** | **100.0%** | **1.0000** | **1.0000** | **1.0000** | **100.0%** |
| **Support Vector Machine (SVM)** | **100.0%** | **1.0000** | **1.0000** | **1.0000** | **100.0%** |
| **Decision Tree Classifier** | **100.0%** | **1.0000** | **1.0000** | **1.0000** | **100.0%** |
| **Gradient Boosting Classifier** | **100.0%** | **1.0000** | **1.0000** | **1.0000** | **100.0%** |

---

## ⚡ Quick Start & Execution

### 1. Clone Repository
```bash
git clone https://github.com/Ziadali-ai/CodeAlpha_DiseasePredictionFromMedicalData.git
cd CodeAlpha_DiseasePredictionFromMedicalData
```

### 2. Environment Setup & Dependencies
```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib
```

### 3. Run Pipeline
```bash
jupyter notebook Disease_Prediction_ML_Granular_EN.ipynb
```

---

## 👤 Author
* **Developer:** Ziad Ali Fathy Mohamed
* **Program:**  Machine Learning Internship
* **Repository Name:** `Disease_Prediction_Medical_ML
* `
