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

![Correlation](/images/Corr.PNG)

### Principal Component Analysis

PCA was implemented because of multicollinearity between groups of input variables.

### Results

![Results](/images/Results.PNG)

**Notebooks**

1_EDA_Prep_Dimension
This notebook includes the EDA, data preparation and dimension reduction.  

2_Feature_Selection_and_Test_Subsets
This notebook includes feature selection models and tests for best subsets of features with a logistic regression model.

3_Regression_Models
This notebook includes the Logistic Regression Model and LASSO Regression Models’ model evaluation and selection and metric evaluation.
