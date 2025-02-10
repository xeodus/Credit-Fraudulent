# Credit-Fraudulent
Credit-Fraudulent is a machine learning-based project designed to analyze and predict fraudulent credit card transactions. By leveraging an anonymized dataset from Kaggle, this project implements various classification techniques to detect fraudulent transactions efficiently.

# Dataset
Dataset used for this project is available on https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud.

# Key features of the dataset

- Highly Imbalanced: Only 0.172% of the transactions are fraudulent.
- Principal Component Analysis (PCA) Applied: Most features are transformed components.
- 284,807 Transactions: Includes both fraudulent and legitimate transactions.
- Time and Amount Features: Alongside anonymized principal components.

# Project Workflow

## Data Processing 

- Handling imbalanced data using resampling techniques.
- Feature engineering and selection.
- Data normalization and scaling.

## Exploratory Data Analysis (EDA)
- Visualizing fraud vs. non-fraud transactions.
- Analyzing distribution patterns and correlations.

## Model Selection & Training
- Implementing a Random Forest Classifier for fraud detection.
- Comparing performance with other models like Logistic Regression, SVM, and Neural Networks.
- Hyperparameter tuning for optimal performance.

## Evaluation Metrics
- Accuracy, Precision, Recall, F1-Score.
- Confusion Matrix for better fraud detection insights.
- ROC-AUC Curve analysis.

## Technology Stack

![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-0096C7?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Imbalanced-Learn](https://img.shields.io/badge/Imbalanced--Learn-FF6F00?style=for-the-badge&logo=scikit-learn&logoColor=white)
