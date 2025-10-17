<h1 align="center">💳 Credit Card Fraud Detection using Machine Learning</h1>

<p align="center">
  <img src="banner.png" alt="Credit Card Fraud Detection Banner1" width="800">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python Badge">
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-learn Badge">
  <img src="https://img.shields.io/badge/XGBoost-FF6600?style=for-the-badge&logo=xgboost&logoColor=white" alt="XGBoost Badge">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas Badge">
  <img src="https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy Badge">
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=plotly&logoColor=white" alt="Matplotlib Badge">
  <img src="https://img.shields.io/badge/Seaborn-9E3FFD?style=for-the-badge" alt="Seaborn Badge">
</p>

---

## 📘 Project Overview

This project focuses on detecting fraudulent credit card transactions using advanced machine learning algorithms. The dataset contains transactions made by European cardholders in September 2013, with features transformed using PCA for confidentiality.

The goal is to develop a robust classification model that accurately identifies fraud while minimizing false positives.

---

## 🧠 Key Objectives

- Understand and analyze the **imbalanced nature** of fraud detection datasets.  
- Perform **EDA (Exploratory Data Analysis)** to uncover key patterns.  
- Train and compare **Logistic Regression, Random Forest, and XGBoost** models.  
- Apply **SMOTE** to balance classes and improve model performance.  
- Evaluate models using **Precision, Recall, F1-Score, and ROC-AUC** metrics.

---

## 📊 Dataset Information

- **Source:** [Credit Card Fraud Detection Dataset (Kaggle)](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)  
- **Records:** 284,807 transactions  
- **Fraudulent Transactions:** 492 (0.172%)  
- **Features:** 30 anonymized numerical variables (V1–V28), `Amount`, and `Time`

---

## 🔍 Exploratory Data Analysis

- Explored transaction amount and time distributions.  
- Identified **extreme class imbalance** between fraud and non-fraud cases.  
- Detected **time-based fraud clusters** and correlations between PCA features and fraud.  
- Visualized patterns using Seaborn heatmaps and histograms.

---

## ⚙️ Model Building & Evaluation

### 🧩 Algorithms Used
- Logistic Regression  
- Random Forest Classifier  
- XGBoost  

### 📈 Model Performance

| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|:------|:----------|:-----------|:--------|:-----------|:---------|
| Logistic Regression | 99.92% | 0.87 | 0.79 | 0.83 | 0.98 |
| Random Forest | 99.95% | 0.93 | 0.85 | 0.89 | 0.99 |
| XGBoost | **99.96%** | **0.95** | **0.87** | **0.91** | **0.992** |

> ✅ **XGBoost** performed best, effectively balancing precision and recall — crucial for fraud detection.

---

## 🗝️ Key Takeaways

- Fraud data is **highly imbalanced**, demanding resampling or cost-sensitive models.  
- **Recall > Accuracy** in importance for fraud detection.  
- PCA-transformed features preserve privacy but limit interpretability.  
- Ensemble models like **XGBoost** consistently outperform linear baselines.  
- Continuous **model monitoring** is vital since fraud patterns evolve dynamically.

---

## 💾 Project Files

- 📓 [View Jupyter Notebook](./Credit%20Card%20Fraud%20Detection.ipynb)  
- 📂 [Download Dataset from Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

---

## 🧰 Tech Stack

| Category | Tools Used |
|:----------|:------------|
| Programming | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn, XGBoost |
| Environment | Jupyter Notebook |
| Platform | Kaggle, GitHub |

---

## 👨‍💻 Author

**Basavaraj Chakalabbi**  
🔗 [GitHub Profile](https://github.com/Basavaraj0127)

---

## ⭐ Show Your Support

If you found this project insightful, consider giving it a ⭐ on [GitHub](https://github.com/Basavaraj0127)!  
Your support motivates me to build and share more data-driven projects 🚀

---

