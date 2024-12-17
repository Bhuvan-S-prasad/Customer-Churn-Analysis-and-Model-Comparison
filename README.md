# Customer Churn Analysis and Model Comparison

This repository is dedicated to analyzing customer churn using various machine learning models and visualizing key insights through exploratory data analysis (EDA). The goal is to compare the performance of different algorithms and identify the best-performing model for predicting customer churn.

---

## Table of Contents
1. [Overview](#overview)
2. [Project Structure](#project-structure)
3. [Dataset](#dataset)
4. [EDA](#eda)
5. [Implemented Models](#implemented-models)
6. [Installation and Usage](#installation-and-usage)



---

## Overview
Customer churn, or customer attrition, refers to customers stopping their relationship with a business. Understanding and predicting churn is crucial for businesses to retain valuable customers.  
This project uses machine learning techniques to predict churn and explores how different models perform on a customer churn dataset. performing EDA and comparing the result of various machine learning algorithm on the dataset

---

## Project Structure
The repository contains the following files:
- **customer_churn.csv**: The dataset used for analysis and modeling.
- **EDA_on_churn.ipynb**: Jupyter notebook for performing exploratory data analysis (EDA) to uncover trends and patterns.
- **logistic_regression.ipynb**: Implementation of Logistic Regression on the dataset.
- **KNN.ipynb**: Implementation of K-Nearest Neighbors (KNN).
- **SVM.ipynb**: Implementation of Support Vector Machines (SVM).
- **random_forest.ipynb**: Implementation of Random Forest classifier.
- **naieve_bayes.ipynb**: Implementation of Naïve Bayes.
- **ensemble.ipynb**: Ensemble techniques combining multiple models.
- **ANN.ipynb**: Implementation of an Artificial Neural Network (ANN).

---

## Dataset
The dataset **customer_churn.csv** includes the following columns:
- **customerID**: Unique identifier for customers.
- **Demographic Data**: Gender, SeniorCitizen, Partner, Dependents.
- **Service Usage**: Tenure, PhoneService, InternetService, etc.
- **Billing Information**: MonthlyCharges, TotalCharges, PaymentMethod.
- **Target**: **Churn** (Yes/No).

**Note**: The dataset is preprocessed to handle missing values and encode categorical variables.

---

## EDA
Exploratory Data Analysis is conducted to uncover patterns and relationships in the data.  
Key analyses include:
- Customer churn distribution.
- Correlation heatmaps for numerical features.
- Analysis of churn rates across categorical variables.
- Visualization of tenure, payment method, and other factors.

Graphs and visualizations are included to enhance interpretability.

---

## Implemented Models
This project implements and evaluates the following models:
1. **Logistic Regression**: Baseline model for binary classification.
2. **K-Nearest Neighbors (KNN)**: Distance-based classification approach.
3. **Support Vector Machines (SVM)**: Classification using hyperplanes.
4. **Random Forest**: An ensemble model based on decision trees.
5. **Naïve Bayes**: Probabilistic classification model.
6. **Ensemble Techniques**: Combining multiple classifiers for better performance.
7. **Artificial Neural Network (ANN)**: A deep learning model for churn prediction.

Each model is evaluated based on metrics like accuracy, precision, recall, F1-score, and ROC-AUC.

---

## Installation and Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/<your_username>/customer-churn-analysis.git
   ```

2. Open any Jupyter notebook to explore or run a specific model:
  ```
  jupyter notebook logistic_regression.ipynb
  ```





