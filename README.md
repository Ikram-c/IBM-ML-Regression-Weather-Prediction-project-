# IBM ML Regression (Weather Prediction project)

## Overview of project
The aim of the project was to find an optimized model for weather prediction using the szeged-weather dataset from Kaggle. 
Data was imported from a CSV into a Pandas dataframe and EDA was conducted to find nulls, the distribution (using a histogram) and plotting a Seaborn correlation Matrix.
Categorical data was encoded using Sklearn's LabelEncoder
A test train split was used and the following Regression models were used:
-Simple Linear regression
-Polynomial Regression (optimised using Kfolds with 10 splits)
-LASSO Regression
-Polynomial Ridge Regression
The models were assessed using RMSE and r^2 accuracy measurements.

