# Explainable Machine Learning for Psychological Stress and Mental Health Assessment in Students

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Jupyter Notebook](https://img.shields.io/badge/Notebook-Jupyter-orange.svg)
![Google Colab](https://img.shields.io/badge/Platform-Google%20Colab-F9AB00.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

## 📖 Overview

This repository contains the official implementation of our research on **Explainable Machine Learning for Student Psychological Stress and Mental Health Assessment**.

The proposed framework integrates physiological, psychological, lifestyle, and academic indicators to predict student health risk levels using machine learning while providing interpretable predictions through Explainable AI (XAI).

The framework employs:

- XGBoost classifier
- SHAP (SHapley Additive exPlanations)
- SMOTE for class balancing
- Feature Engineering
- Explainable AI (XAI)

The entire implementation is provided as a single **Google Colab/Jupyter Notebook**.

---

## 📄 Research Paper

**Title**

> Explainable Machine Learning for Psychological Stress and Mental Health Assessment in Students

**Conference**

FICTA 2026 (International Conference on Frontiers in Intelligent Computing: Theory and Applications)

**Publication Status**

Accepted / Presented at **FICTA 2026**

Publication in the conference proceedings is **coming soon**.

---

## 📂 Repository Structure

```
.
├── Student_Stress.ipynb          # Complete implementation
├── student_health_data.csv       # Dataset
├── README.md
```

---

## 📊 Dataset

The dataset used in this work is publicly available on Kaggle.

**Dataset Name**

Student Health Data

**Source**

https://www.kaggle.com/datasets/ziya07/student-health-data

A copy of the dataset (`student_health_data.csv`) has also been included in this repository for convenience.

---

## ⚙️ Features

- Data preprocessing
- Feature engineering
- Class imbalance handling using SMOTE
- Model training
- Hyperparameter tuning
- Performance evaluation
- Confusion matrix
- Classification report
- SHAP explainability
- Feature importance visualization

---

## 🧠 Machine Learning Models

The notebook compares the performance of:

- Logistic Regression
- Random Forest
- XGBoost (Best Performing Model)

---

## 📈 Explainable AI

Model interpretability is achieved using:

- SHAP Summary Plot
- SHAP Feature Importance
- Local Prediction Explanations

This allows transparent understanding of how different physiological and psychological factors influence health risk predictions.

---

## 🚀 Running the Notebook

### Google Colab

1. Open **Student_Stress.ipynb** in Google Colab.
2. Upload or mount the repository.
3. Ensure `student_health_data.csv` is located in the same directory.
4. Run all notebook cells sequentially.

---

### Local Jupyter Notebook

Clone the repository

```bash
git clone https://github.com/MustaqueemAlam/explainable-stress-classification.git
```

Install the required packages

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost imbalanced-learn shap
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
Student_Stress.ipynb
```

and run all cells.

---

## 📦 Required Libraries

- Python 3.9+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost
- imbalanced-learn
- shap

---

## 📊 Results

The proposed XGBoost model achieved excellent predictive performance for student health risk assessment.

| Model | Accuracy |
|---------|----------|
| Logistic Regression | 78.57% |
| Random Forest | 97.81% |
| **XGBoost** | **99.41%** |

The SHAP-based explainability analysis identified stress-related indicators and sleep quality as the most influential factors affecting prediction outcomes.

---

## 🎯 Key Contributions

- Explainable student health risk prediction framework
- Integration of physiological and psychological indicators
- Feature engineering for improved predictive performance
- SHAP-based model interpretation
- High-performance XGBoost classifier
- Reproducible implementation using Google Colab


---

## 📜 License

This project is released under the **MIT License**.

---

## ⭐ Support

If you find this repository useful for your research, please consider giving it a ⭐ on GitHub.
