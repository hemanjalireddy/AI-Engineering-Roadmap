---
layout: topic
title: Machine Learning Fundamentals
description: Core concepts of ML including supervised/unsupervised learning, model evaluation, and basic algorithms
difficulty: beginner
status: in-progress
date_started: 2025-01-15
order: 1

resources:
  - title: "Andrew Ng's Machine Learning Course"
    type: Course
    link: https://www.coursera.org/learn/machine-learning
    description: Foundational ML course covering supervised learning, unsupervised learning, and best practices
    notes: |
      - **Gradient Descent**: Iterative optimization algorithm that adjusts parameters to minimize cost function
      - **Overfitting vs Underfitting**: Balance between model complexity and generalization
      - **Regularization**: Technique to prevent overfitting by adding penalty terms (L1, L2)
      - Key insight: Always split data into train/validation/test sets
  
  - title: "Hands-On Machine Learning (Géron)"
    type: Book
    link: https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/
    description: Practical guide using Scikit-Learn, Keras, and TensorFlow
    notes: |
      - Start with end-to-end projects to understand the full ML pipeline
      - Feature engineering is often more important than algorithm choice
      - Ensemble methods combine multiple models for better performance

notebooks:
  - title: "Linear Regression from Scratch"
    description: Implementing linear regression with gradient descent in NumPy
    github_link: https://github.com/yourusername/ai-roadmap/blob/main/notebooks/01_linear_regression.ipynb
    colab_link: https://colab.research.google.com/github/yourusername/ai-roadmap/blob/main/notebooks/01_linear_regression.ipynb
  
  - title: "Classification with Logistic Regression"
    description: Binary classification on the Titanic dataset
    github_link: https://github.com/yourusername/ai-roadmap/blob/main/notebooks/02_logistic_regression.ipynb
    kaggle_link: https://www.kaggle.com/yourusername/classification-logistic-regression
---

## Overview

Machine Learning is the foundation of modern AI. This topic covers the essential concepts and algorithms you need to know before diving into more advanced topics like deep learning.

## Key Concepts Learned

### Supervised Learning
- **Regression**: Predicting continuous values (house prices, temperature)
- **Classification**: Predicting discrete labels (spam/not spam, cat/dog)

### Unsupervised Learning
- **Clustering**: Grouping similar data points (K-means, hierarchical clustering)
- **Dimensionality Reduction**: Reducing features while preserving information (PCA, t-SNE)

### Model Evaluation
- Cross-validation for robust performance estimates
- Metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC
- Confusion matrices for classification analysis

## Projects Completed

1. **Housing Price Prediction**: Built a regression model to predict California housing prices
2. **Customer Segmentation**: Used K-means clustering on customer purchase data
3. **Spam Detection**: Created a text classification model with TF-IDF and Naive Bayes

## Next Steps

- Dive deeper into ensemble methods (Random Forests, XGBoost)
- Explore feature engineering techniques
- Move on to Neural Networks and Deep Learning
