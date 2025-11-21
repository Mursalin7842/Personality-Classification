# Personality Classification Using Machine Learning

This project focuses on predicting whether an individual is an **Introvert** or an **Extrovert** using machine learning techniques.  
It uses a behavioral dataset and demonstrates a complete workflow including preprocessing, feature engineering, model training, and evaluation.

---

## 📘 Introduction

Personality plays a key role in shaping human behavior, communication style, social interaction, career choices, and decision-making patterns.  
The Introversion–Extroversion dimension is one of the most widely studied traits in psychology, and predicting it using data has become an important task in fields such as:

- Human–computer interaction  
- Recommendation systems  
- Behavioral analysis  
- HR screening and productivity studies  
- Mental well-being assessments  

With the growth of data-driven analytics, machine learning provides powerful tools for identifying personality traits based on measurable behavioral patterns.  
This project uses simple social and activity-related features—such as **time spent alone**, **friend circle size**, and **social activity level**—to classify individuals into two categories:

- **0 → Introvert**  
- **1 → Extrovert**

The goal is to demonstrate an effective ML pipeline that can be used for academic research, small-scale personality analytics, or psychological behavior studies.

---

## 📚 Literature Review

A number of research studies support the idea that personality traits can be predicted using computational models:

### 1. Personality Prediction from Behavioral Features  
Early research by psychologists such as **Hans Eysenck** and **Carl Jung** established that measurable social behaviors strongly correlate with introversion and extroversion.  
Modern machine learning approaches now automate this process by learning patterns from structured datasets.

### 2. Machine Learning Models for Personality Classification  
Multiple studies have explored the use of classifiers such as:
- **Support Vector Machines (SVM)**  
- **Random Forest**  
- **Gradient Boosting Models**  
- **Neural Networks**  

These models often achieve strong performance when trained on well-engineered behavioral features.

### 3. Ensemble Learning for Higher Accuracy  
Recent literature suggests that **ensemble methods** (e.g., stacking, boosting) improve prediction accuracy by combining the strengths of multiple models.  
This project uses a stacking ensemble, which has been shown to reduce overfitting and provide more stable results.

### 4. Importance of Feature Engineering  
Research consistently shows that features related to:
- social interaction levels  
- time spent alone  
- communication frequency  
- group participation  
are strong indicators of introversion/extroversion tendencies.

This aligns with the dataset used in this project.

---

## 📂 Dataset

The dataset contains behavioral features such as:
- Time Spent Alone  
- Friends Circle Size  
- Social Activity Score  
- Communication Frequency  
- Stress Levels  
- Hobbies  
- Personality (Target variable)

---

## ⚙️ Methodology Overview

1. **Data Cleaning & Preprocessing**  
2. **Feature Engineering**  
3. **Model Training (RF, GBM, XGBoost, SVM)**  
4. **Stacking Ensemble Construction**  
5. **Model Evaluation (Accuracy, F1 Score)**  
6. **Interpretability using Feature Importance**

---

## 📝 Conclusion

This project demonstrates that personality traits—specifically introversion and extroversion—can be predicted using structured behavioral data and machine learning models.  
Through preprocessing, feature engineering, and stacked ensemble learning, the model achieves reliable performance suitable for academic demonstration and research discussion.

---

## 📦 Files Included
- `Personality Classification.ipynb` — Main notebook  
- `personality_datasert.csv` — Dataset  
- `README.md` — Project Documentation

---
