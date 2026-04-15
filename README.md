# Health Care Diagnosis Prediction

## Overview
This project aims to predict medical test results (Normal, Abnormal, Inconclusive) based on patient features using machine learning models. The analysis includes data exploration, preprocessing, model training, and evaluation.

## Dataset
The dataset (`Data/healthcare_dataset.csv`) contains healthcare-related information with the following features:
- Age
- Gender
- Blood Type
- Medical Condition
- Admission Type
- Medication
- Test Results (target variable)

## Project Structure
```
Health Care Diagnosis/
├── Data/
│   └── healthcare_dataset.csv
├── Notebook/
│   └── Health.ipynb
└── README.md
```

## Requirements
- Python 3.7+
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, imbalanced-learn, shap

Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn shap
```


## Models Evaluated
- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier
- K-Nearest Neighbors

## Key Features
- Data preprocessing with scaling and one-hot encoding
- Handling imbalanced data with class weights
- Cross-validation for model evaluation
- Prediction output with feature details

