# Credit-Fraudulent
Credit-Fraudulent is a machine learning-based project designed to analyze and predict fraudulent credit card transactions. By leveraging an anonymized dataset from Kaggle, this project implements various classification techniques to detect fraudulent transactions efficiently.

## Technology Stack

![Pandas](https://img.shields.io/badge/Pandas-2C8EBB?style=flat&logo=pandas&logoColor=white&labelColor=0277BD)
![NumPy](https://img.shields.io/badge/NumPy-3366CC?style=flat&logo=numpy&logoColor=white&labelColor=0044AA)
![Matplotlib](https://img.shields.io/badge/Matplotlib-DD4B39?style=flat&logo=python&logoColor=white&labelColor=C62828)
![Seaborn](https://img.shields.io/badge/Seaborn-FF9800?style=flat&logo=python&logoColor=white&labelColor=E65100)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-FDD835?style=flat&logo=scikit-learn&logoColor=white&labelColor=F57F17)
![Imbalanced-Learn](https://img.shields.io/badge/Imbalanced--Learn-7CB342?style=flat&logo=scikit-learn&logoColor=white&labelColor=558B2F)

# Dataset
Dataset used for this project is available on https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud.

# Key features of the dataset

- **Highly Imbalanced**: Only 0.172% of the transactions are fraudulent.
- **Principal Component Analysis (PCA) Applied**: Most features are transformed components.
- **284,807 Transactions**: Includes both fraudulent and legitimate transactions.
- **Time and Amount Features**: Alongside anonymized principal components.

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
