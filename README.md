# Implementation-of-Linear-Regression-Using-Gradient-Descent

## AIM:
To write a program to predict the profit of a city using the linear regression model with gradient descent.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
Data Preparation:

Read the dataset from a CSV file using pandas.
Separate the features (X) and the target variable (y) from the dataset.
Convert these into NumPy arrays and scale them using StandardScaler to ensure all features have a mean of 0 and a standard deviation of 1, which helps in the convergence of gradient descent.
Feature Engineering:

Add an intercept term (a column of ones) to the feature matrix X. This is necessary for the bias (intercept) in the linear regression model.
Initialization:

Initialize the weights (theta) to zeros. The number of weights is equal to the number of features plus one (for the intercept).
Gradient Descent:

Iterate a specified number of times (num_iters).

In each iteration:

Compute the predictions by multiplying the feature matrix X with the weights theta.
Calculate the errors by subtracting the actual target values (y) from the predictions.
Update the weights (theta) using the gradient descent update rule:
θ
=
α
1
m
X
T
(
X
θ
−
y
)

where:

α is the learning rate.
m is the number of training examples.
Prediction:

To predict the target value for new data, scale the new data using the same scaler.
Use the learned weights (theta) to make predictions on the scaled new data.

## Program:
```
/*
Program to implement the linear regression using gradient descent.
Developed by: 
RegisterNumber:  
*/
```

## Output:
![linear regression using gradient descent](sam.png)


## Result:
Thus the program to implement the linear regression using gradient descent is written and verified using python programming.
