# CodeAlpha_MachineLearning

Machine Learning Internship Projects — CodeAlpha

This repository contains 3 completed machine learning tasks from the CodeAlpha Machine Learning Internship, covering classical ML, deep learning, and real-world data challenges like class imbalance and data leakage.

## Tasks Completed

### [Task 1: Credit Scoring Model](./Task_1_Credit_Scoring)

Predicts creditworthiness (Poor / Standard / Good) from financial history using Logistic Regression, Decision Tree, and Random Forest.
**Best result:** Random Forest — 78% accuracy, ROC-AUC 0.9074

### [Task 3: Handwritten Character Recognition](./Task_3_Handwritten_Character)

Classifies handwritten digits (0–9) using a Convolutional Neural Network trained on MNIST.
**Result:** 99.19% test accuracy

### [Task 4: Disease Prediction from Medical Data](./Task_4_Disease_Prediction)

Predicts heart disease presence from clinical data using Logistic Regression, SVM, and Random Forest. Includes a real data-leakage investigation (duplicate records inflating accuracy) and fix.
**Best result:** Logistic Regression — 80% accuracy, ROC-AUC 0.8712

## Tech Stack

Python · Pandas · NumPy · Scikit-learn · TensorFlow/Keras · Matplotlib · Seaborn

## Setup

```bash
python -m venv venv
venv\Scripts\activate      # Windows
pip install -r requirements.txt
```

## Author

Namya Shah — CodeAlpha Machine Learning Intern
