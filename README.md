# Machine Learning with MATLAB

Algorithms for supervised and unsupervised machine learning, neural networks, and anomaly detection using MATLAB R2016a 

## Gradient Descent
Use when dealing with large sample sizes (i.e., n > 10000)

### Linear Model
Linear Gradient Descent uses Linear Cost Function to compute the cost per iteration as it estimates beta.  Use when dealing with single variable (i.e., vectors).

### Feature Normalization
Prior to running Multivariable Gradient Descent, it is often necessary to normalize the features to bring the sample values within a comparable scale and thus, reduce noise and inaccurate estimates.  The normalization technique used is standardization.

### Multivariable Model
Multivariable Gradient Descent uses Multivariable Cost Function to compute the cost per iteration as it estimates beta.  Use when dealing with multiple features (i.e, matrices).

## Normal Equations
Use when dealing with fewer samples (i.e., n =< 10000)

Normal equations provide closed-form solutions to beta, but are inefficient when dealing with large sample sizes.
