# Heart Disease Prediction using Bayesian Networks

A probabilistic model using **Bayesian Networks** to predict heart disease risk based on features like age, cholesterol, fasting blood sugar, and heart rate. Built using `pgmpy`.

## Overview

- Loads and preprocesses heart disease data
- Discretizes key numeric variables
- Defines a Bayesian Network: `age → fbs → target → chol_cat, thalach_cat`
- Trains using Maximum Likelihood Estimation
- Performs inference with Variable Elimination
- Visualizes network structure and prediction results

## Dataset

- Source: UCI Heart Disease dataset or synthetic fallback
- Key features: age, fbs (fasting blood sugar), chol (cholesterol), thalach (max heart rate), target (disease)
