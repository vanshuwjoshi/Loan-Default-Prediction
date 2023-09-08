# Loan Default Prediction

## Overview

This repository contains the code and documentation for a data challenge project completed as part of STAT 441 (Statistical Learning: Classification) at the University of Waterloo. The project's objective was to develop a classification model that predicts whether a client will default on a loan based on their characteristics in the dataset. This predictive model can assist banks in making informed decisions regarding loan approvals.

## Problem Statement

The central problem statement involved creating a classification model to determine the likelihood of a client defaulting on a loan. The model's output can be used as a crucial factor in the bank's decision-making process for loan approval.

## Data Preparation

- **Feature Engineering**: The dataset underwent feature engineering using the Boruta technique to select relevant features and enhance model performance.

## Supervised Machine Learning Models

Several supervised machine learning models were explored, including:

- **Naive Bayes**
- **Random Forest**
- **Logistic Regression**
- **XGBoost**
- **Ensemble of SVM and Logistic Regression**
- **Ensemble of Logistic Regression and Decision Tree**

## Model Selection

After a thorough evaluation, the models that provided the best accuracy, recall value and precision score were XGBoost and logistic regression. These models were selected as the final candidates for loan default prediction.

## Evaluation

The models were evaluated based on their accuracy, recall, and precision scores to ensure their effectiveness in predicting loan defaults.
