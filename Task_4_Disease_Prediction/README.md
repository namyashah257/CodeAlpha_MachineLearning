# Task 4: Disease Prediction from Medical Data

## CodeAlpha Machine Learning Internship

## Objective

Predict the presence of heart disease in a patient based on clinical and diagnostic data.

## Dataset

[Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset) (UCI) — clinical features including age, blood pressure, cholesterol, chest pain type, and cardiac test results, with a binary target (disease present / not present).

## Approach

1. Explored the dataset — found it fully numeric with no missing values.
2. **Detected and fixed a data leakage issue**: the raw dataset (1025 rows) contained 723 duplicate rows, inflating an initial Random Forest test to a suspicious 100% accuracy. Removed duplicates (302 unique patients remained) and re-split before retraining.
3. Trained and compared three classifiers: Logistic Regression, SVM, and Random Forest.

## Results

| Model | Accuracy | F1 (weighted) |
| --- | --- | --- |
| **Logistic Regression** | **80%** | **0.80** |
| SVM | — | — |
| Random Forest | — | — |
