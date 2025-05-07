# Body Signals Analysis of Smoking and Drinking

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## 🚀 Overview

This project investigates the relationship between body signal data and smoking/drinking behaviors. Using a dataset of 70,000+ physiological records, we developed machine learning models to classify individuals based on their smoking and drinking status, achieving strong performance and clear visual insights.

**Key achievements:**
- Comprehensive preprocessing and feature engineering (BMI, age groups, blood pressure categories, cholesterol ratio, etc.).
- Correlation analysis and hypothesis testing (t-tests, chi-squared tests) to explore statistical relationships.
- Built two classification models (SVM & XGBoost) with ~81% accuracy.
- Data visualization to support interpretability.

---

## 🗂️ Dataset

The dataset contains physiological measurements such as:
- Blood pressure (systolic/diastolic)
- Heart rate
- Cholesterol levels
- Vision metrics
- BMI (calculated)

**Note:** The dataset is not included due to privacy and licensing reasons.

---

## 🔧 Methods & Techniques

### Preprocessing
- Missing data handling (imputation using median/mode)
- Feature engineering:
    - BMI calculation
    - Age group categorization
    - Blood pressure classification
    - Cholesterol ratio computation
    - Vision impairment flag

### Statistical Analysis
- **Correlation analysis:** Pearson correlation & heatmaps
- **Hypothesis testing:**
    - T-tests between smokers/non-smokers
    - Chi-squared tests for categorical variables

### Models
- **SVM (Support Vector Machine):**
    - Kernel-based classification
    - Accuracy: ~81%

- **XGBoost:**
    - Gradient-boosted trees
    - Accuracy: ~81%
    - Feature importance analysis

### Dimensionality Reduction
- **PCA (Principal Component Analysis):**
    - Used to reduce feature space for visualization.

---

## 📊 Visualizations

- Correlation heatmaps
- PCA plots
- Boxplots & countplots for hypothesis testing
- Pie charts for distribution insights

Example:
```python
plt.pie(counts, labels=cholesterol_categories, autopct='%1.1f%%')
