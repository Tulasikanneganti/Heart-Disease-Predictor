# Heart-Disease-Predictor
Classification Models on Dataset

This project evaluates multiple machine learning classification algorithms to predict a binary target variable from a dataset. The main goal is to compare model performances and analyze their effectiveness in terms of accuracy and error rates.

Models Evaluated

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

Gaussian Naive Bayes

Dataset Description

The dataset includes various features along with a binary target column.

The target variable is preprocessed to ensure it is in the correct format for classification.

Methodology

The dataset is split into training and testing sets to evaluate model generalization.

Each model is trained on the training data and tested on the unseen test data.

Key evaluation metrics computed include:

Accuracy: The proportion of correctly classified samples.

False Negative Rate (FNR): The proportion of positive cases incorrectly classified as negative.

Confusion Matrix: A detailed breakdown of true positives, true negatives, false positives, and false negatives.

Key Insights

Gaussian Naive Bayes performs well when the data distribution matches its underlying assumptions, often yielding high accuracy.

Decision Tree and Random Forest classifiers can achieve very high accuracy but may risk overfitting, especially on smaller datasets.

Logistic Regression serves as a strong baseline linear model and performs well with balanced, well-prepared data.

False Negative Rate is a critical metric in many domains, such as healthcare and fraud detection, where missing positive cases has serious consequences.

Requirements

Python 3.x environment

Libraries: scikit-learn, pandas, numpy

Usage

Prepare your dataset ensuring the target column is properly formatted.

Split the data into training and test sets.

Train and evaluate the different models.

Use the evaluation metrics to select the best model suited for your specific needs.
