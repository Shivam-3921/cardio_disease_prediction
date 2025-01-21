# Cardiovascular Disease Prediction Project

## Project Overview
This project focuses on the analysis and classification of cardiovascular disease data. Using various machine learning techniques, we aim to predict the likelihood of cardiovascular disease based on patient data.

The project consists of two main components:
1. A subfolder containing the cardiovascular disease dataset.
2. A main Jupyter Notebook that performs data analysis and classification.

---

## Project Structure

```
project-directory/
├── data/
│   └── cardio_disease_dataset.csv  # Dataset used for the project
├── main_notebook.ipynb             # Jupyter Notebook with analysis and classification
└── README.md                       # Project documentation (this file)
```

---

## Contents of the Jupyter Notebook

### 1. Feature Selection
#### a. Data Cleaning
- Removed unrealistic data points to ensure data quality.

#### b. Numerical Feature Analysis
- Used boxplots and histogram plots (histplots) to identify trends and outliers.
- Scaled numerical features for better model performance.
- Examined the correlation matrix to identify multicollinearity.

#### c. Categorical Feature Analysis
- Visualized data distribution with countplots.
- Analyzed the relationships between categories using the Chi-Square (\( \chi^2 \)) test.

### 2. Classification
#### a. Machine Learning Models
- Implemented and compared the following classification algorithms:
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
  - LinearSVC
  - Support Vector Machine (SVM) with different kernels
  - Decision Tree
  - Bagging
  - Random Forest
  - Gradient Boosting
  - Adaptive Boosting
  - Stacking Classifier

#### b. Cross-Validation and Hyperparameter Tuning
- Used GridSearchCV for cross-validation and hyperparameter optimization to identify the best parameters for each model.

#### c. Evaluation Metrics
- Generated classification reports including accuracy and F1 scores.
- Plotted the following for each model:
  - ROC-AUC curves
  - Precision-Recall curves

---

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone <repository-link>
   ```

2. Navigate to the project directory:
   ```bash
   cd project-directory
   ```

3. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook main_notebook.ipynb
   ```

---

## Requirements
- Python 3.7+
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn

---

## Results
The notebook provides a detailed comparison of various machine learning models based on:
- Accuracy
- F1 Score
- ROC-AUC curves
- Precision-Recall curves

The results highlight the most effective model for predicting cardiovascular disease and the corresponding hyperparameters.

---

## Acknowledgments
- Dataset: [Provide source/link to the dataset if applicable]
- Libraries: scikit-learn, matplotlib, seaborn, pandas, numpy

---

## License
[Include licensing information here, if applicable.]
