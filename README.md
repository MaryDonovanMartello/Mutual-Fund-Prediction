# Mutual-Fund-Prediction

## EDA and Continuous Value Prediction

### Summary

The goal of this project was to use Python to design models to predict mutual fund return values and to identify the features that best predict those return values. Linear Regression and LASSO Linear Regression models were tested. The paper walks through the dimensionality reduction, feature selection, model evaluation and selection, and assessment of the models.

### Tools

* Scikit-learn
* Seaborn
* Matplotlib
* Numpy
* Pandas


**Data:** [funds](https://www.kaggle.com/stefanoleone992/mutual-funds-and-etfs?select=Mutual+Funds.csv)

### Methodology

Compared multiple versions of models that varied techniques for data-splitting and feature selection.

### Models / Methods / Metrics

* Linear Regresiion
* LASSO Linear Regression
* Dimensionality Reduction: Principal Component Analysis
* Feature Selection:
  * Principal Component Analysis
  * Exploratory Data Analysis
  + LASSO Linear Regression
  + Log-Transformation and Scaling
* GridSearch
* R-Squared and Root Mean Squared Error

## Project Preview

### Exploratory Data Analysis

A few features have a strong correlation with the target variable: ytd_return

![Correlation](/images/Results.PNG)

### Principal Component Analysis

PCA was implemented because of multicollinearity between groups of input variables.

![PCA](/images/Results.PNG)

### Results

![Results](/images/Results.PNG)

