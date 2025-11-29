
=======
# 🏥 Healthcare Provider Fraud Detection

Identifying high-risk healthcare providers using machine learning, feature engineering, and advanced evaluation methods.

---

## 📌 Project Overview

This project analyzes Medicare claims data to detect healthcare providers who may be engaged in fraudulent billing activities. It provides a complete machine learning workflow, from initial data exploration to final project presentation.

**Workflow Includes:**
- Multi-source data exploration
- Provider-level feature engineering
- Class imbalance handling (SMOTE + class weights)
- Model development & comparison (Random Forest vs Logistic Regression)
- Comprehensive evaluation with ROC & PR curves
- Interpretability through false positive & false negative analysis
- Professional technical report
- Dedicated space for the final project presentation

---

## 📁 Repository Structure

```bash
fraud_detection_project/
│
├── notebooks/
│   ├── 01_data_exploration_and_feature_engineering.ipynb
│   ├── 02_modeling.ipynb
│   └── 03_evaluation.ipynb
│
├── data/
│   ├── provider_features.csv
│   └── model_predictions.csv
│
├── reports/
│   ├── technical_report.pdf
│   └── presentation.pptx 
│
└── README.md
```

---

## 🗂️ Folder Descriptions

- **notebooks/**  
  Jupyter notebooks covering:
  - Exploratory data analysis
  - Feature engineering
  - Class imbalance strategy
  - Modeling & evaluation

- **data/**  
  Contains exported datasets:
  - `provider_features.csv` → Engineered provider-level dataset
  - `model_predictions.csv` → Model predictions for final evaluation

- **reports/**  
  Project reports:
  - `technical_report.pdf` → Full written report
  - `presentation.pptx` → Placeholder for final presentation slides

- **README.md**  
  Project documentation and overview

---

## ✨ Key Features

### 🔍 Data Engineering
- Integration of Inpatient, Outpatient, Beneficiary, and Label datasets
- Aggregation of claim-level data into provider-level features
- Creation of derived metrics:
  - Total reimbursements
  - Unique beneficiary counts
  - Claims-per-beneficiary ratios

### ⚖️ Class Imbalance Handling
- SMOTE oversampling
- Class-weight adjustments
- Stratified train-test splits
- Metrics focused on fraud recall and F1-score

### 🤖 Modeling
- Random Forest (primary model)
- Logistic Regression (baseline model)
- Feature importance and decision patterns

### 📈 Evaluation
- ROC Curve
- Precision-Recall Curve
- Confusion Matrix
- Error analysis (False Positives & False Negatives)
- Summary comparison table

---

## 🚀 Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Imbalanced-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 💡 Future Improvements

- SHAP interpretability
- Advanced models (XGBoost / LightGBM)
- Deployment using FastAPI
- Interactive fraud detection dashboard

---

>>>>>>> 8b89b075eb840ed6d2e3b3be6220533a11beaf94
