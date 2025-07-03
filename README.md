# Task 7: Support Vector Machines (SVM) – Breast Cancer Classification

## Objective
The objective of this task is to implement SVM classifiers with both linear and RBF kernels to classify tumor types in the Breast Cancer dataset. The task includes hyperparameter tuning and performance evaluation.

## Dataset
- Source: [Breast Cancer Dataset – scikit-learn]
- Loaded using `sklearn.datasets.load_breast_cancer()`

## Tools Used
- Python
- Pandas
- Scikit-learn
- NumPy
- Matplotlib

## What Was Done
- Loaded and scaled the breast cancer dataset
- Trained a linear SVM and evaluated accuracy, confusion matrix, and classification report
- Trained an RBF kernel SVM and compared performance
- Performed hyperparameter tuning using different values of `C` and `gamma`
- Used cross-validation to validate model reliability

## Output
- `svm_breast_cancer.ipynb` – contains full code, evaluation metrics, and results
- Identified optimal kernel and parameters through testing
