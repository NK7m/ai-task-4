# Logistic Regression Classifier

This repository contains the solution for Task 4 of the AI & ML Internship program - Classification with Logistic Regression.

## Project Overview
- Built a binary classifier using logistic regression on the Breast Cancer Wisconsin Dataset
- Evaluated model performance using various metrics
- Explored threshold tuning and the sigmoid function

## Key Steps
1. Loaded and explored the dataset
2. Split data into training and test sets
3. Standardized features using StandardScaler
4. Trained a logistic regression model
5. Evaluated using:
   - Confusion matrix
   - Precision, recall, ROC-AUC
   - ROC curve and Precision-Recall curve
6. Explored threshold tuning
7. Visualized the sigmoid function

## Results
The model achieved strong performance on the breast cancer classification task, with ROC-AUC score of 0.99.

## How to Run
1. Install requirements: `pip install -r requirements.txt`
2. Open and run the Jupyter notebook: `logistic_regression_classifier.ipynb`

## Dependencies
- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- jupyter
