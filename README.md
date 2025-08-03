# YZTA-rabiabeyzazengin
Bootcamp project of yzta
# 🧬 Thalassemia Prediction from Blood Test Results using TabNet
🔗 [Canlı Demo](https://yzta-rabiabeyzazengin-erqza4qpvdosugr3mjv9wr.streamlit.app/)

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


Upload TRAIN2.csv and test.csv to your working directory or Google Drive.

Run the script or notebook to train the model and get predictions.

📊 Model Details
Preprocessing:

Label Encoding of categorical features

Standardization with StandardScaler

Stratified K-Fold validation (5-fold)

Model:

TabNetClassifier trained on processed dataset

Balanced class weights

🌐 Web Interface (Planned)
A lightweight web app (in progress) will allow users to:

Enter their blood test values

Get an instant prediction on the likely interpretation

View explanation and disclaimers

📬 Author
Rabia Beyza Zengin
👩‍💻 Software Engineer | AI Enthusiast
