# Diabetes Prediction Model using Logistic Regression

## Overview

This project aims to develop a predictive model to determine whether a patient has diabetes based on certain diagnostic measurements. The dataset used for this analysis is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective is to diagnostically predict whether a patient has diabetes using various medical predictor variables. 

## Dataset Description

The dataset consists of the following columns:

- Pregnancies: Number of times pregnant
- Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
- Blood Pressure: Diastolic blood pressure (mm Hg)
- Skin Thickness: Triceps skin fold thickness (mm)
- Insulin: 2-Hour serum insulin (mu U/ml)
- BMI: Body mass index (weight in kg/(height in m)^2)
- Diabetes: Diabetes pedigree function
- Age: Age in years
- Outcome: Class variable (0 or 1) indicating whether the patient has diabetes or not

All patients in the dataset are females at least 21 years old of Pima Indian heritage.

## Analysis Steps

1. Importing necessary libraries including pandas, numpy, matplotlib, seaborn, and scikit-learn.
2. Loading the dataset from a CSV file.
3. Checking for missing values using a heatmap visualization.
4. Computing the correlation matrix to understand the relationships between variables.
5. Visualizing the correlation matrix using a heatmap.
6. Preparing the data for training by splitting it into features (independent variables) and target (dependent variable).
7. Splitting the data into training and testing sets.
8. Training a logistic regression model on the training data.
9. Making predictions on the test data.
10. Evaluating the model's accuracy.

## Files

- `diabetes.csv`: CSV file containing the dataset.
- `Diabetes_Prediction_Model.ipynb`: Jupyter Notebook containing the code for logistic regression model.
- `README.md`: This file providing an overview of the logistic regression model.