# **Fraudulent Transaction Detection Using Random Forest**

This project involves detecting fraudulent transactions using a simple machine learning model, Random Forest. The task focuses on handling imbalanced data through undersampling and classifying transactions as fraudulent or not fraudulent. The dataset used contains transaction records, where the goal is to predict whether a transaction is fraudulent based on various features.

## Project Overview

In this project, we perform the following steps:

1. **Data Preprocessing:**
We handle the imbalanced data problem using undersampling, reducing the number of majority class samples to balance the dataset.


2. **Model Training:**
We use a Random Forest Classifier to train the model on the balanced data.


3. **Model Evaluation:**
The model is evaluated using various metrics such as accuracy, precision, recall, F1-score, and a confusion matrix.
Dataset

## Dataset: 
The dataset contains transaction records, with each transaction labeled as fraudulent (1) or non-fraudulent (0).

## Code Explanation

1. **Data Preprocessing:**

The dataset is loaded and explored to check for class imbalance.

We handle the imbalance using the RandomUnderSampler to balance the dataset.



2. **Model Training:**

The Random Forest Classifier is trained on the balanced dataset.



3. **Model Evaluation:**

We evaluate the model's performance using accuracy, precision, recall, F1-score, and the confusion matrix.




# Results

The model's performance will be printed as:

**Accuracy:** The proportion of correct predictions.

**Precision:** How many of the predicted fraudulent transactions were actually fraudulent.

**Recall:** How many of the actual fraudulent transactions were correctly identified.

**F1-Score:** The harmonic mean of precision and recall.

**Confusion Matrix:** A visualization of true vs. predicted values.
