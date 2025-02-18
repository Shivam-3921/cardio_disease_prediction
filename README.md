## Introduction

Cardiovascular disease  refers to a class of diseases that affect the heart and blood vessels. It is the leading cause of death worldwide, contributing to millions of fatalities annually. It includes conditions such as coronary artery disease, stroke, heart failure, and hypertension. Early detection and prevention play a crucial role in reducing the risk of severe outcomes.

## Project Description

The primary objective of this project is to develop a machine-learning pipeline for classifying individuals based on their likelihood of having cardiovascular disease. By employing various machine learning models, we aim to identify key risk factors and improve early detection methods.

### Dataset

The dataset used in this project contains a variety of features related to cardiovascular health, such as blood pressure, cholesterol levels, smoking status, and other medical indicators.

- Dataset Location: Stored in a subfolder within the repository.

- Features: Includes numerical and categorical variables indicative of cardiovascular health.

- Target Variable: Binary classification indicating the presence or absence of cardiovascular disease.

### Repository Structure

- cardio_data/cardio.csv: Contains the cardiovascular disease dataset.

- cardio_disease.ipynb: Jupyter Notebook detailing the full data exploration, preprocessing, and model development process.

## Methodology

### 1. Feature Selection

- Cleaned data by removing unrealistic or erroneous data points.

- Conducted exploratory data analysis (EDA) using:

    - Boxplots and histograms to visualize distributions.

    - Correlation matrix and heatmaps to analyze relationships between numerical features.

    - Countplots to examine categorical feature distributions.

    - Assessed categorical feature relationships using the Chi-squared test.

### 2. Classification

- Implemented multiple classification models such as Logistic Regression, K-Nearest Neighbors, LinearSVC, Support Vector Machines, Decision Tree, Bagging Classifier, Random Forest, Gradient Boosting, and Adaptive Boosting.

- Utilized GridSearchCV for cross-validation and hyperparameter tuning to optimize model performance.

- Evaluated models using accuracy, recall, F1-score, ROC curve and Precision-Recall curve.

## Conclusion

This project demonstrates the effectiveness of machine learning techniques in predicting cardiovascular disease risk. By leveraging data-driven insights, we can contribute to early diagnosis and prevention strategies, ultimately improving public health outcomes.

