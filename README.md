# 🧬 The Impact on Body Signals: Analysis of Smoking and Drinking

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

## 📊 Overview

This project explores the relationship between physiological signals and smoking/drinking behaviors. Utilizing a dataset of over 70,000 records, we developed machine learning models to classify individuals based on their smoking and drinking status, achieving an accuracy of approximately 81%.

---

## 🧠 Methodology

### 🔄 Data Preprocessing

- **Feature Engineering**: Created new features such as BMI, age groups, blood pressure categories, and cholesterol levels.
- **Data Cleaning**: Handled missing values and outliers to ensure data quality.

### 🧪 Model Development

- **Algorithms Used**:
  - Support Vector Machine (SVM)
  - XGBoost Classifier
- **Dimensionality Reduction**:
  - Principal Component Analysis (PCA)
- **Evaluation Metrics**:
  - Accuracy: ~81%
  - Confusion Matrix
  - ROC Curve

### 📈 Visualization

- Generated comprehensive visualizations to illustrate the distribution of physiological signals among different groups.
- Visual tools used include histograms, box plots, and scatter plots.

---

## 📁 Project Structure

```
the_impact_on_body-signals-analysis-of-smoking-and-drinking/
├── CSC240_final_project.ipynb   # Main analysis notebook
├── CS240_final_presentation.pdf # Project presentation slides
├── report.pdf                   # Detailed project report
├── journal.md                   # Project journal and notes
├── LICENSE                      # MIT License
└── README.md                    # Project documentation
```

---

## 🛠️ Requirements

- Python 3.x
- Libraries:
  - pandas
  - numpy
  - scikit-learn
  - xgboost
  - matplotlib
  - seaborn

Install the required libraries using pip:

```bash
pip install pandas numpy scikit-learn xgboost matplotlib seaborn
```

---

## ▶️ Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/AnakinHuang/the_impact_on_body-signals-analysis-of-smoking-and-drinking.git
   ```

2. Navigate to the project directory:

   ```bash
   cd the_impact_on_body-signals-analysis-of-smoking-and-drinking
   ```

3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook CSC240_final_project.ipynb
   ```

4. Run the notebook cells sequentially to reproduce the analysis.

---

## 👤 Author

- **Yuesong Huang** (yhu116@u.rochester.edu)
- **Junhua Huang** (jhuang77@u.rochester.edu)
- **Yuyang Wang** (ywang383@u.rochester.edu)
- **Boyang Wang** (bwang55@u.rochester.edu)

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
