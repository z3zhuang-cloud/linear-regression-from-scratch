# Linear Regression From Scratch

This project builds linear regression from first principles using Python and NumPy.

Instead of relying on `sklearn` for the main model, the notebook:
- generates synthetic data,
- defines mean squared error (MSE),
- derives the gradients,
- implements gradient descent manually,
- visualizes the fitted line and loss curve,
- compares the result with `sklearn.linear_model.LinearRegression`.

## Why this project
Linear regression is simple enough to understand mathematically, but it also contains many of the same ideas used in machine learning more broadly:
- a model with parameters,
- a loss function,
- gradients,
- iterative optimization,
- model evaluation.

## Tools
- Python
- NumPy
- Matplotlib
- scikit-learn (comparison only)

## Core model

We fit

\[
\hat{y} = wx + b
\]

by minimizing mean squared error

\[
MSE = \frac{1}{n}\sum_{i=1}^{n}(y_i - \hat{y}_i)^2
\]

using gradient descent.

## Files
- `linear_regression_from_scratch.ipynb` — full walkthrough
