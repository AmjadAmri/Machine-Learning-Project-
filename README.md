# Predicting Student Academic Success using Machine Learning
A machine learning project that predicts student dropout and academic success through data preprocessing, feature selection, hyperparameter optimization, and comparative evaluation of multiple classification models.

![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python)
![scikit-learn](https://img.shields.io/badge/scikit--learn-Machine_Learning-F7931E?logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical_Computing-013243?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C)
![Machine Learning](https://img.shields.io/badge/Machine_Learning-Classification-success)

## Overview

This project develops a machine learning pipeline to predict student academic outcomes using the "Predict Students' Dropout and Academic Success" dataset.

The project covers the complete machine learning workflow, including exploratory data analysis, data preprocessing, feature engineering, feature selection, model training, hyperparameter tuning, and comparative evaluation of multiple classification algorithms.

## Objectives

- Explore and understand the dataset through EDA.
- Prepare the dataset for machine learning.
- Handle class imbalance.
- Select the most informative features.
- Train multiple classification models.
- Optimize model hyperparameters.
- Compare model performance.
- Identify the best-performing model.

## Dataset

## Dataset

Dataset:
Predict Students' Dropout and Academic Success

Target Classes

- Dropout
- Graduate
- Enrolled

Features include:

- Academic history
- Demographic information
- Socioeconomic factors
- First- and second-semester academic performance

## Project Workflow

<p align="center">
<img src="https://github.com/user-attachments/assets/24bb5c44-23bc-47e3-8d60-115b249223b8" width="900">
</p>

| Stage | Techniques |
|--------|------------|
| Exploratory Data Analysis | Dataset inspection, descriptive statistics, visualization |
| Data Preprocessing | Missing values, duplicates, outlier treatment, class balancing |
| Feature Selection | Mutual Information, Recursive Feature Elimination (RFE) |
| Model Training | KNN, SVM, Decision Tree |
| Hyperparameter Optimization | GridSearchCV |
| Evaluation | Accuracy, Precision, Recall, F1-score, Confusion Matrix |

## Exploratory Data Analysis

The dataset was analyzed to understand feature distributions, class balance, correlations, and potential data quality issues before model development.

Main analyses included:

- Dataset inspection
- Missing value inspection
- Statistical summaries
- Class distribution analysis
- Feature distribution visualization

## Data Preprocessing

The preprocessing pipeline included:

- Missing value handling
- Duplicate removal
- Outlier treatment
- Feature encoding
- Feature scaling
- Class balancing

## Feature Engineering & Feature Selection

## Feature Selection

To reduce dimensionality and retain the most informative predictors, two feature selection techniques were applied:

- Mutual Information
- Recursive Feature Elimination (RFE) using Logistic Regression


## Machine Learning Models

The following classification models were trained and evaluated:

- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Decision Tree

## Results & Model Comparison

The models were optimized using GridSearchCV with 5-fold cross-validation before comparing their predictive performance.

## Technology Stack

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| Machine Learning | Scikit-learn |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib |
| Hyperparameter Optimization | GridSearchCV |
| Development Environment | Jupyter Notebook |

## Future Improvements

- Apply explainable AI (SHAP/LIME) to improve model interpretability.
- Deploy the trained model as an interactive web application.
- Evaluate the pipeline on additional educational datasets.



