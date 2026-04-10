# 🧠 Bangla Mental Health NLP Framework

An end-to-end large-scale Bangla mental health classification system using NLP, Machine Learning, and Explainable AI.

---

## 📌 Overview

This project presents a scalable and explainable framework for Bangla mental health text classification using synthetic data generation, TF-IDF features, and Calibrated LinearSVC.

The system is designed to address:
- Low-resource Bangla NLP challenges
- Mental health data scarcity
- Need for interpretable AI in healthcare

Based on research work: :contentReference[oaicite:0]{index=0}

---

## 🚀 Key Features

- ✅ Large-scale synthetic Bangla dataset (15+ million samples)
- ✅ 15 mental health disorder classification
- ✅ Severity detection (হালকা / মাঝারি / তীব্র)
- ✅ TF-IDF + LinearSVC model
- ✅ Explainable AI (SHAP + LIME)
- ✅ End-to-end pipeline (Data → EDA → Model → Evaluation)


---

## 📊 Dataset
Full dataset is not included due to size issue as there fifteen million data row. A sample dataset is provided for demonstration purposes.
- Language: Bangla
- Categories: 15 mental disorders
- Includes:
  - comment_bn
  - category_bn
  - stage_bn
  - response_bn

Synthetic + real-anonymized hybrid data

---

## ⚙️ Methodology

1. Synthetic Data Generation (Python-based)
2. Data Preprocessing & Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Extraction (TF-IDF)
5. Model Training (LinearSVC - OvR)
6. Evaluation (F1, Accuracy, Confusion Matrix)
7. Explainability (SHAP, LIME)

---

## 📈 Results

- Accuracy: **99.96%**
- Macro F1-score: **0.9995**
- Strong generalization across all classes

---

## 🧠 Explainability

- SHAP → Global feature importance
- LIME → Instance-level explanations

