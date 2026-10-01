# 🏦 Loan Approval Prediction

## 📌 Project Overview

This project predicts loan approval status using Machine Learning.

The goal is to analyze applicant information and build a classification model that predicts whether a loan will be approved.

## 📊 Dataset

- Total Records: 45,000
- Total Columns: 14
- Target Variable: Loan Status

### Features

- Age
- Gender
- Education
- Person Income
- Employee Experience
- Home Ownership
- Loan Amount
- Loan Intent
- Loan Interest Rate
- Loan Percentage
- Credit History
- Credit Score
- Previous Loan

## 🔍 Exploratory Data Analysis

The dataset was explored using:

- `head()`
- `info()`
- `isnull()`
- `describe()`
- `value_counts()`
- `groupby()`

No missing values were found in the dataset.

## 🤖 Machine Learning

A **Logistic Regression** model was used for binary classification.

### Model Performance

- Accuracy: **89.44%**
- Precision (Class 1): **78%**
- Recall (Class 1): **74%**
- F1-Score (Class 1): **76%**

## 📈 Confusion Matrix

The model was evaluated using a confusion matrix and classification report.

## 🛠️ Tools & Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Git & GitHub

## 📌 Conclusion

The Logistic Regression model achieved an accuracy of **89.44%** on the test dataset.

This project demonstrates the basic workflow of a Machine Learning classification project, including data exploration, preprocessing, feature encoding, scaling, model training, prediction, and evaluation.