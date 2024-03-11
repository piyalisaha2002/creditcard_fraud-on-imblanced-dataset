# Credit Card Fraud Detection on Imbalanced Dataset

This repository contains code and resources for implementing a credit card fraud detection model on an imbalanced dataset. The goal is to accurately detect fraudulent credit card transactions despite the inherent class imbalance in the dataset.

## Overview

Credit card fraud is a significant concern for financial institutions and individuals. Traditional fraud detection methods often struggle to cope with the increasing sophistication of fraudulent activities. Machine learning models offer a more effective solution by automatically learning patterns indicative of fraud. However, credit card fraud datasets are highly imbalanced, with a small number of fraud cases compared to legitimate transactions. This poses a challenge for developing accurate models, as they can become biased towards the majority class. This repository addresses this issue by presenting methodologies like undersampling and oversampling to train a fraud detection model on imbalanced data.

## Methodologies

1. **Data Preprocessing**:
   - Explore and understand the dataset, identifying class imbalance.
   - Handle missing values and perform feature scaling if necessary.
   - Split the data into training and testing sets.

2. **Model Training**:
   - Experiment with different machine learning algorithms such as Logistic Regression, Random Forest, and Gradient Boosting.
   - Implement techniques to handle class imbalance, including:
     - Undersampling the majority class to balance the dataset.
     - Oversampling the minority class using techniques like SMOTE (Synthetic Minority Over-sampling Technique).
     - Adjusting class weights to penalize misclassifications of the minority class.

3. **Model Evaluation**:
   - Evaluate the performance of each model using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.
   - Compare the results obtained from different methodologies to identify the most effective approach for fraud detection.

## Usage

1. **Data Preparation**:
   - Ensure the dataset is loaded and preprocessed, handling any missing values and scaling features if necessary.

2. **Model Training**:
   - Experiment with different algorithms and methodologies to handle class imbalance.
   - Train multiple models using techniques like undersampling, oversampling, and adjusting class weights.

3. **Model Evaluation**:
   - Evaluate the performance of each model on the testing set using appropriate metrics.
   - Compare the results and select the model with the best performance for fraud detection.

## Requirements

- Python 3
- Scikit-learn
- Pandas
- NumPy

## Running the Project

1. Ensure the dataset is preprocessed.
2. Train multiple models using different methodologies for handling class imbalance.
3. Evaluate the performance of each model and select the best-performing one for fraud detection.
