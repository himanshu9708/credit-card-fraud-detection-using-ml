
# Credit Card Fraud Detection

A machine learning project for detecting fraudulent credit card transactions using multiple classification algorithms and performance evaluation techniques.

---

# Dataset

Dataset used in this project:

https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

## Overview

This project focuses on identifying fraudulent credit card transactions using supervised machine learning models. The notebook includes data preprocessing, feature scaling, model training, evaluation, and comparison of different algorithms.

The main objective is to build a reliable fraud detection system capable of handling imbalanced transaction data.

---

## Features

- Data preprocessing and cleaning
- Fraud transaction percentage analysis
- Feature scaling using StandardScaler
- Duplicate value handling
- Train-test split for model training
- Multiple machine learning algorithms
- Genetic Algorithm based feature selection
- ROC-AUC curve visualization
- Model comparison using F1-score and ROC-AUC

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

---

## Machine Learning Models Used

### 1. Logistic Regression
A baseline classification model used for fraud prediction.

### 2. Random Forest Classifier
An ensemble learning model used to improve prediction performance.

### 3. Genetic Algorithm + Logistic Regression
Feature selection is performed using Genetic Algorithm before applying Logistic Regression.

### 4. XGBoost Classifier
A gradient boosting model used for high-performance fraud detection.

---

## Dataset Information

The dataset contains credit card transaction details where:

- Normal transactions are labeled as `0`
- Fraudulent transactions are labeled as `1`

The project performs:

- Data inspection
- Feature transformation
- Scaling of transaction amount
- Removal of unnecessary columns
- Duplicate removal

---

## Evaluation Metrics

The following metrics are used for performance evaluation:

- F1 Score
- Confusion Matrix
- ROC Curve
- ROC-AUC Score

These metrics help evaluate model performance on highly imbalanced datasets.

---

## Project Workflow

1. Import dependencies  
2. Load and inspect dataset  
3. Data preprocessing  
4. Feature scaling  
5. Remove duplicates  
6. Split training and testing data  
7. Train multiple models  
8. Evaluate model performance  
9. Compare results  
10. Visualize ROC-AUC curves  

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/credit-card-fraud-detection.git
```

Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost genetic-selection
```

Run the notebook:

```bash
jupyter notebook
```

---

## Project Structure

```text
Credit-Card-Fraud-Detection/
│
├── Credit_Card_Fraud_Detection.ipynb
├── README.md
└── dataset.csv
```

---

## Results

The notebook compares multiple machine learning algorithms and identifies which model performs best for fraud detection based on F1-score and ROC-AUC score.

XGBoost and Random Forest generally provide stronger performance compared to basic Logistic Regression for imbalanced classification problems.

---

## Future Improvements

- Hyperparameter tuning
- Deep learning implementation
- Real-time fraud detection system
- Deployment using Flask or FastAPI
- Model optimization for production environments

---

