# Logistic Regression: Binary Classification Project 🚀

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![scikit-learn](https://img.shields.io/badge/scikit--learn-LogisticRegression-orange)
![License](https://img.shields.io/badge/License-MIT-green)

This repository contains a **recruiter-ready** implementation of Logistic Regression for binary classification using the **Breast Cancer Wisconsin dataset**.  
The project includes **EDA, preprocessing, model training, evaluation, threshold tuning, and explainability**.

---

## 📂 Repository Structure
```
├── notebooks/
│   └── logistic_regression_project.ipynb   # Full workflow notebook
├── results/
│   ├── confusion_matrix.png
│   ├── roc_curve.png
│   ├── precision_recall_curve.png
│   ├── sigmoid.png
│   ├── threshold_precision_recall.png
│   ├── top_coefficients.png
│   └── results_summary.json
├── requirements.txt
└── README.md
```

---

## 🔍 Workflow Highlights
1. **EDA** – Histograms, correlation heatmap.  
2. **Preprocessing** – Train-test split & scaling.  
3. **Logistic Regression** – With regularization.  
4. **Evaluation** – Confusion matrix, ROC-AUC, PR curves.  
5. **Threshold tuning** – Business trade-off demo.  
6. **Explainability** – Coefficient analysis & SHAP (optional).  

---

## 📊 Sample Outputs
Confusion Matrix             |  ROC Curve
:---------------------------:|:----------------------------:
![](results/confusion_matrix.png) | ![](results/roc_curve.png)

Precision-Recall Curve       |  Sigmoid Function
:---------------------------:|:----------------------------:
![](results/precision_recall_curve.png) | ![](results/sigmoid.png)

---

## 📌 How to Run
```bash
git clone <your-repo-link>
cd logistic_regression_outputs
pip install -r requirements.txt
jupyter notebook notebooks/logistic_regression_project.ipynb
```

---

## 🎯 Interview Prep Included
The notebook includes answers to: logistic vs linear regression, sigmoid function, precision vs recall, ROC-AUC, confusion matrix, handling imbalance, threshold selection, and multi-class extension.

---

✨ **Tip:** This project not only demonstrates Logistic Regression but also shows your ability to communicate insights clearly — a key recruiter expectation.
