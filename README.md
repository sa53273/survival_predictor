## Titanic Survival Predictor

This repository contains the code and resources for the "Titanic Survival Predictor" project, developed for the Kaggle Titanic competition. The goal of the project is to predict the survival of passengers aboard the Titanic using various machine learning techniques.

# Project Overview

The Titanic Survival Predictor project involves several key steps:

# Data Pipeline:
Data Cleaning: Handling missing values and irrelevant features.
Feature Engineering: Creating new features and transforming existing ones.
Encoding: One-hot encoding categorical variables.
Machine Learning Model:
Model Selection: Using a RandomForestClassifier to predict survival.
Cross-Validation: Applying GridSearchCV to find the best hyperparameters.
Results:
The final model achieved an accuracy score of 0.82 on the training data and 0.77 on the test set.
This score placed the project at 11173rd position in the Kaggle Titanic competition.
Data Pipeline

The data pipeline includes the following steps:

Imputation: Missing age values are imputed using the mean age.
Encoding: Categorical variables such as 'Sex' are one-hot encoded.
Dropping Irrelevant Features: Features like 'Embarked', 'Name', 'Ticket', and 'Cabin' are dropped as they do not contribute significantly to the model.
Machine Learning Model

A RandomForestClassifier was chosen for the prediction task. The model's hyperparameters were fine-tuned using GridSearchCV, which optimizes for the best parameters through cross-validation. The parameters considered include:

Number of estimators: 10, 100, 200, 500
Maximum depth: None, 5, 10
Minimum samples split: 2, 3, 4

# Results

Training Accuracy: 0.82
Test Accuracy: 0.77
Competition Placement: 11173rd
