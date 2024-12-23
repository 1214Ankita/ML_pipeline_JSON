# ML_pipeline_JSON

This repository contains a Python implementation of a machine learning pipeline that dynamically adapts based on a JSON configuration file. The pipeline includes preprocessing, feature engineering, model training, and evaluation.

### Features

Dynamic Configuration: The pipeline is driven by a JSON file, allowing flexibility in dataset handling, feature processing, and model selection.

Support for Multiple Models: Supports algorithms like Random Forest, Linear Regression, Support Vector Regression (SVR), Gradient Boosting, and Decision Trees.

Preprocessing:
Handles both numerical and categorical features.
Imputation strategies for missing values.
Standard scaling and one-hot encoding.
Feature Engineering.

Model Optimization:
Grid search for hyperparameter tuning.
Cross-validation for robust evaluation.

Performance Metrics:
Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R2).

Model Persistence: Saves the best-performing model as a .pkl file.

### Usage
Prerequisites:
Python 3.7+
Required libraries: pandas, scikit-learn, numpy, joblib
