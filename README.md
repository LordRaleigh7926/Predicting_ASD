# Machine Learning Model Analysis


## Dataset

Data source: [Kaggle Autism Screening Dataset](https://www.kaggle.com/datasets/faizunnabi/autism-screening).


## Overview

This project involves preprocessing data and evaluating several machine learning models on an autism screening dataset. 

## Steps

1. **Imports**:
   - `pandas` for data handling.
   - `sklearn` for preprocessing and model building.

2. **Load Dataset**:
   - Dataset loaded with `id` column as index.

3. **Data Exploration**:
   - Display first five rows.
   - Check for and drop missing values.

4. **Data Preprocessing**:
   - Encode categorical data using `OrdinalEncoder`.
   - Drop irrelevant columns.

5. **Split Data**:
   - Divide data into training (80%) and testing (20%) sets.

6. **Train Models**:
   - **K-Nearest Neighbors (KNN)**: Classifies based on nearest neighbors.
   - **Support Vector Machine (SVM)**: Finds the best boundary between classes.
   - **Naive Bayes**: Uses probability for classification.
   - **Logistic Regression**: Predicts binary outcomes.

7. **Evaluate Models**:
   - Use `classification_report` for performance metrics (precision, recall, F1-score, accuracy).

---
