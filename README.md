# Early-Chronic-Illness-Detection

## Overview
This project focuses on detecting depression using a machine learning-based approach by analyzing socioeconomic, health, and lifestyle data. The dataset, sourced from Kaggle, includes key features such as education, income, sleep patterns, and family history of depression.


## Methodology

We implemented multiple classification models, including:
- Logistic Regression (Batch & Stochastic Gradient Descent)
- Random Forest & Decision Tree (Tuned)
- Naïve Bayes (Gaussian & Bernoulli)
- MLP Classifier (Neural Network)

Feature selection techniques like Recursive Feature Elimination (RFE) and Principal Component Analysis (PCA) were applied for dimensionality reduction. SMOTE balancing was used to handle class imbalance.

## Key Findings
- Naïve Bayes (67%) performed best due to the dataset’s characteristics.
- Decision Tree (63%) effectively captured non-linear patterns.
- MLP (66-67%) leveraged complex patterns using activation functions.
