# Breast Cancer Classification using Random Forest and XGBoost

## Project Overview

This project compares Random Forest and XGBoost models for breast cancer classification using the Breast Cancer Wisconsin Dataset.

## Objectives

- Learn the basic machine learning workflow
- Compare Random Forest and XGBoost models
- Evaluate model performance using Accuracy and AUC
- Identify important features contributing to prediction

## Dataset

Breast Cancer Wisconsin Dataset

- Number of samples: 569
- Number of features: 30
- Target classes: 2 (Benign / Malignant)

## Machine Learning Workflow

1. Load dataset
2. Data exploration
3. Feature and label separation
4. Train-test split
5. Train Random Forest model
6. Train XGBoost model
7. Compare model performance
8. Analyze feature importance

## Results

| Model | Accuracy | AUC |
|---------|---------|---------|
| Random Forest | 0.965 | 0.995 |
| XGBoost | 0.956 | 0.991 |

## Top Important Features

- worst area
- worst concave points
- mean concave points
- worst radius
- mean concavity

## Conclusion

Both models achieved excellent performance on the breast cancer dataset.

Random Forest slightly outperformed XGBoost in both Accuracy and AUC.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost

