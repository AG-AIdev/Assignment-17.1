# Assignment 17.1 — Comparing Classifiers

This assignment analyzes the performance of multiple machine learning classifiers on the Bank Marketing dataset. The purpose of the project is to predict if a client will subscribe to a term deposit based on demographic, financial, and campaign-related features.

# Contents
- Exploratory Data Analysis (EDA) with visualizations
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier
- Support Vector Machine (SVM)
- Model comparison table (train time, train accuracy, test accuracy)
- Discussion of model performance and next steps

# Summary of Findings
- Logistic Regression and SVM performed similarly and close to the baseline.
- Decision Tree overfit the training data.
- KNN performed slightly worse than linear models.
- The dataset is imbalanced, so accuracy is not the best metric.
- Future improvements include hyperparameter tuning and using recall/F1 as evaluation metrics.

# Next Steps
- Perform GridSearchCV for all models
- Add cross-validation
- Explore additional features and feature engineering
- Improve management of class imbalance
