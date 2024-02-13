# Sampling

Using Different Sampling Techniques on Different ML Models

## Overview

In this assignment , we are implementing different sampling techniques for credit card dataset using five distinct models CatBoost,
XGBoost, LightGBM, Support Vector Classifier (SVC), and Random Forest and various sampling methods and evaluating their accuracy

## Dataset

The dataset for this assignment is a CSV file containing credit card transactions. The data includes various features such as transaction amount, timestamp, and others. It is essential to handle imbalanced classes, as fraudulent transactions are typically rare compared to legitimate ones.

### File: credit_card_data.csv

## Sampling Techniques

The assignment involves applying five different sampling techniques to address the imbalanced nature of the data. The selected techniques are:

1. **Random Sampling:** Randomly selecting instances from the dataset without considering class distribution.

2. **Stratified Sampling:** Ensuring that the proportion of classes in the sample is similar to that in the entire dataset.

3. **Under-sampling:** Reducing the number of instances in the majority class to balance class distribution.

4. **Over-sampling:** Increasing the number of instances in the minority class to balance class distribution.

5. **SMOTE (Synthetic Minority Over-sampling Technique):** Creating synthetic instances for the minority class to address class imbalance.

## Models

Five different machine learning models will be trained on each of the sampled datasets. The selected models are:

1. **CatBoost**
2. **XGBoost**
3. **LightGBM**
4. **Support Vector Classifier (SVC)**
5. **Random Forest**

## Instructions

1. **Data Loading:**

   - Load the credit card dataset from `credit_card_data.csv`.
   - Understand the dataset's structure and features.

2. **Data Preprocessing:**

   - Handle missing values, if any.
   - Explore and visualize the class distribution to understand the data imbalance.

3. **Sampling:**

   - Apply the five sampling techniques to create five different datasets.
   - Ensure the balance between fraudulent and legitimate transactions in the sampled datasets.

4. **Model Training:**

   - Train a CatBoost, XGBoost, LightGBM, SVC, and Random Forest model on each sampled dataset.

5. **Model Evaluation:**

   - Evaluate the accuracy of each model on a separate test dataset (not used during training).
   - Compare the performance of models trained on different sampling techniques.

6. **Results and Conclusion:**
   - Summarize the findings, comparing the effectiveness of each sampling technique in improving model accuracy for credit card fraud detection.
