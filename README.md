# YZTA-rabiabeyzazengin
Bootcamp project of yzta
# 🧬 Thalassemia Prediction from Blood Test Results using TabNet

This project aims to predict types of thalassemia based on hematological parameters using a deep learning model trained with PyTorch TabNet.

---

## 📌 Problem Statement

Thalassemia is a group of inherited blood disorders characterized by abnormal hemoglobin production. Early detection is critical for treatment planning.

This project provides a classification model that predicts:
- Alpha thalassemia trait
- Beta thalassemia trait
- Beta thalassemia major
- Normal
- Others

based on common blood test indicators.

---

## 🧠 Features Used

| Feature Name          | Description                     |
|-----------------------|---------------------------------|
| `HB`                 | Hemoglobin                      |
| `MCV`                | Mean Corpuscular Volume         |
| `Hb A0`              | Hemoglobin A0                   |
| `Hb A2`              | Hemoglobin A2                   |
| `Hb A1C/Hb F`        | Hemoglobin A1C / F              |
| `Hb E`               | Hemoglobin E                   |
| `Hb Bart's`          | Hemoglobin Bart's               |
| `Hb D/S/Constant/C`  | Hemoglobin variants (D/S etc.)  |

Target label: **`Interpretation`**

---

## 📁 Dataset

- `TRAIN2.csv` - Labeled training dataset  
- `test.csv` - Unseen test samples (same structure)

Each row represents a patient's test results and a label representing the thalassemia type or normal condition.

---

## ⚙️ Technologies Used

- Python 3.x
- PyTorch TabNet
- scikit-learn (for preprocessing and cross-validation)
- Google Colab
- Pandas, NumPy

---

## 🚀 How to Use

1. Clone this repository or open in Google Colab.
2. Install TabNet:

```bash
pip install pytorch-tabnet

