# Birthweight
Building a predictive model on a continuous response variable (Y-variable) to predict Birthweight of Babies in Jupyter Notebook.

[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)

## Data
Data Dictionary [data dictionary](https://github.com/emaeda1/Birthweight/blob/main/birthweight_low.xlsx)

## Feature Engineering 
A common approach to feature engineering that we learned in class is to identify correlated variables and then divide the first variable by 2 before adding it to the second variable.

## Models 
-OLS Regression (Standard Linear Regression)
-Lasso Regression
-Bayesian Automatic Relevance Determination (ARD)

## Results

OLS Regression
----------------------------------

Training Set: 0.7135
Testing Set:0.663
Gap:0.0505

Lasso Regression ***FINAL MODEL***
----------------------------------

Training Set:0.713
Testing Set:0.6685
Gap:0.0445

ARD Regression
----------------------------------
Training Set: 0.7134
Testing Set:0.6658
Gap:0.0476
