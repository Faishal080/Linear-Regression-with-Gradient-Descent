# Linear Regression from Scratch

A beginner-friendly implementation of **Linear Regression from scratch using Gradient Descent**, without using a ready-made linear regression model.

This project demonstrates how a linear regression model learns its weights and bias by minimizing the cost function through iterative parameter updates.

##  Project Overview

In this project, Linear Regression is implemented step-by-step using:

- NumPy
- Matplotlib
- Scikit-learn's Diabetes dataset

Instead of directly using a pre-built regression model, the core components are implemented manually to understand how Linear Regression and Gradient Descent work internally.

##  Dataset

The project uses the **Diabetes dataset** available through Scikit-learn.

The dataset contains:

- 442 observations
- 10 input features
- A continuous target variable

The features include:

- Age
- Sex
- BMI
- Blood Pressure
- S1
- S2
- S3
- S4
- S5
- S6

##  What is Implemented?

The notebook covers the following steps:

1. Loading the dataset
2. Exploring the dataset
3. Standardizing the features and target
4. Splitting the data into:
   - Training set
   - Validation set
   - Test set
5. Initializing weights and bias
6. Making predictions
7. Defining the cost function
8. Computing gradients
9. Updating parameters using Gradient Descent
10. Training the model iteratively
11. Monitoring training and validation cost
12. Visualizing the cost history

##  Linear Regression

The model predicts the target using:

ŷ = Xw + b

where:

- `X` = input features
- `w` = weights
- `b` = bias
- `ŷ` = predicted value

##  Gradient Descent

Gradient Descent is used to optimize the model parameters.

The process is:

```text
Initialize weights and bias
        ↓
Make predictions
        ↓
Calculate cost
        ↓
Calculate gradients
        ↓
Update weights and bias
        ↓
Repeat
