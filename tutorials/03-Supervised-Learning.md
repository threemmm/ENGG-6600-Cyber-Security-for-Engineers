# Supervised Learning

## Table of Contents

1. [Introduction](#introduction)
2. [Types of Supervised Learning](#types-of-supervised-learning)
    - [Regression](#regression)
    - [Classification](#classification)
3. [Common Algorithms](#common-algorithms)
    - [Regression Algorithms](#regression-algorithms)
    - [Classification Algorithms](#classification-algorithms)
4. [Evaluation Metrics](#evaluation-metrics)
5. [Conclusion](#conclusion)

## Introduction

Supervised Learning is one of the most common types of machine learning. In supervised learning, a model is trained on a labeled dataset. The model makes predictions based on the input features and is corrected using the provided labels. The goal is to learn a mapping function from the input variables to the output variable.

## Types of Supervised Learning

Supervised learning can be categorized into two main types: Regression and Classification.

### Regression

In regression tasks, the output variable is a real or continuous value, such as weight or price. The goal is to predict a numerical value based on the input features.

#### Example:

Predicting house prices based on features like the number of bedrooms, location, and square footage.

### Classification

In classification tasks, the output variable is a category, such as 'yes' or 'no', or 'spam' and 'not spam'. The goal is to categorize input data into predefined classes.

#### Example:

Email spam filtering, where the model categorizes emails as either 'spam' or 'not spam'.

## Common Algorithms

### Regression Algorithms

Here are some commonly used algorithms for regression tasks:

1. **Linear Regression**: Assumes a linear relationship between input features and output.
2. **Ridge Regression**: Linear regression with L2 regularization.
3. **Lasso Regression**: Linear regression with L1 regularization.
4. **Decision Trees**: Non-linear model that works well for both regression and classification.
5. **Random Forest**: Ensemble method based on decision trees.

### Classification Algorithms

Here are some commonly used algorithms for classification tasks:

1. **Logistic Regression**: Despite its name, used for binary classification problems.
2. **K-Nearest Neighbors (K-NN)**: Classifies a data point based on how its neighbors are classified.
3. **Support Vector Machines (SVM)**: Seeks to find the hyperplane that best divides a dataset into classes.
4. **Decision Trees**: A flowchart-like tree structure where each internal node represents a feature.
5. **Random Forest**: Ensemble method based on decision trees.

## Evaluation Metrics

Performance in supervised learning is often evaluated using specific metrics:

- **Regression**: Mean Absolute Error (MAE), Mean Squared Error (MSE), R-squared
- **Classification**: Accuracy, Precision, Recall, F1-Score, Area under the ROC curve (AUC-ROC)

## Conclusion

Supervised learning is an essential category of machine learning. It includes two main types: regression and classification, each with its own set of algorithms and evaluation metrics. Understanding these basics is crucial for anyone looking to delve deeper into machine learning or data science.

