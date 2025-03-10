# Iris Dataset Classification using Logistic Regression

# Overview

This project focuses on classifying iris species using Logistic Regression. It includes data exploration, preprocessing, model training, and evaluation to assess classification performance.

# Dataset

The dataset used is the Iris dataset, which consists of:

150 samples

3 classes (Setosa, Versicolor, Virginica)

4 features (sepal length, sepal width, petal length, petal width)

# Machine Learning Model

The machine learning model used in this project is Logistic Regression, implemented using sklearn.linear_model.LogisticRegression. It is a simple yet effective model for multi-class classification problems.

# Data Preprocessing

The dataset is split into training and testing sets using train_test_split.

Features are standardized using StandardScaler to improve model performance.

# Evaluation Metrics

The model's performance is assessed using the following metrics:

Accuracy Score: Measures the overall correctness of predictions.

Confusion Matrix: Provides insight into the classification results for each category.

Classification Report: Includes precision, recall, and F1-score for each class.

# Results and Insights

The Logistic Regression model achieves high accuracy on the test dataset.

The confusion matrix indicates how well each species is classified.

The classification report provides a breakdown of precision, recall, and F1-score, helping to identify potential misclassifications.

The visualization using seaborn pair plots helps in understanding feature relationships and data separability.
