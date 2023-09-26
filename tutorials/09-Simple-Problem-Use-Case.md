# Simple Problem Use-Case

## Table of Contents

1. [Introduction](#introduction)
2. [Problem Statement](#problem-statement)
3. [Data Import](#data-import)
4. [Exploratory Data Analysis](#exploratory-data-analysis)
5. [Data Preprocessing](#data-preprocessing)
6. [Model Training](#model-training)
7. [Model Evaluation](#model-evaluation)
8. [Conclusion](#conclusion)

## Introduction

In this tutorial, we'll walk through a simple problem use-case to demonstrate the steps involved in solving a machine learning problem. The focus is on applying the concepts we've learned in the previous tutorials.

## Problem Statement

Let's consider a simple problem: predicting whether an email is spam or not based on its content.

## Data Import

First, we import the data. For this example, let's assume we have a CSV file named `spam_data.csv` with two columns: `Email_Content` and `Is_Spam`.

```python
import pandas as pd

# Import the data
df = pd.read_csv('spam_data.csv')
```

## Exploratory Data Analysis

Before building the model, it's important to understand the data.

```python
# View the first few rows of the DataFrame
print(df.head())

# Check for missing values
print(df.isnull().sum())
```

## Data Preprocessing

Next, we preprocess the data. This involves vectorizing the email content and splitting the data into training and test sets.

```python
from sklearn.model_selection import train_test_split
from sklearn.feature_extraction.text import CountVectorizer

# Vectorize the email content
vectorizer = CountVectorizer()
X = vectorizer.fit_transform(df['Email_Content'])

# Split the data
X_train, X_test, y_train, y_test = train_test_split(X, df['Is_Spam'], test_size=0.2)
```

## Model Training

We will use a simple logistic regression model for this problem.

```python
from sklearn.linear_model import LogisticRegression

# Initialize the model
model = LogisticRegression()

# Train the model
model.fit(X_train, y_train)
```

## Model Evaluation

Finally, we evaluate the model using accuracy as the metric.

```python
from sklearn.metrics import accuracy_score

# Make predictions
y_pred = model.predict(X_test)

# Calculate accuracy
accuracy = accuracy_score(y_test, y_pred)
print(f'Accuracy: {accuracy}')
```

## Conclusion

This tutorial provided a simple end-to-end example to demonstrate the process of solving a machine learning problem. We covered data import, exploratory data analysis, preprocessing, model training, and evaluation. While this is a simplified example, the steps remain largely the same for more complex problems.
