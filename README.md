# Iris Flower Classification

Introductory machine learning project that classifies iris flowers by species using the classic Iris dataset.

## Overview
This notebook loads the Iris dataset from `IRIS.csv`, performs basic inspection and null checks, splits the dataset into training and test sets, and trains a decision tree classifier to predict flower species from sepal and petal measurements.

## Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn

## Workflow
1. Load and inspect the dataset
2. Check for missing values
3. Separate features and target labels
4. Split the data into training and test sets
5. Train a `DecisionTreeClassifier`
6. Evaluate the model with confusion matrix and accuracy score

## Model Notes
- Problem type: multi-class classification
- Algorithm: decision tree classifier
- Evaluation: confusion matrix and accuracy score

## Files
```text
Project_Iris_Flower-/
├── IRIS.csv
├── project_iris.ipynb
├── requirements.txt
└── README.md
```

## Run Locally
```bash
pip install -r requirements.txt
jupyter notebook project_iris.ipynb
```

## Learning Focus
- End-to-end supervised classification workflow
- Train-test split fundamentals
- Decision tree modeling on small tabular datasets
- Basic metric-based model evaluation
