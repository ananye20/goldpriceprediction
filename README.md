# goldpriceprediction
## Overview
This project focuses on predicting gold prices using various machine learning and deep learning models. The models employed include logistic regression, decision tree classifier, naive Bayes, boosted tree model, Keras classifier, and multiple linear regression.

## Dataset
The dataset used for this project includes the following features:

Date: The date of the observation.
SPX (Standard & Poor's 500 Index): A stock market index that measures the stock performance of 500 large companies listed on stock exchanges in the United States.
GLD (Gold ETF): Exchange-traded fund that aims to track the price of gold.
USO (United States Oil Fund): Exchange-traded fund that tracks the price of oil.
SLV (Silver ETF): Exchange-traded fund that aims to track the price of silver.
EUR/USD (1 Euro = how much US Dollar): The exchange rate of euros to US dollars.
## Workflow
### Data Preprocessing and Visualization
Imported necessary libraries and files.
Performed data preprocessing, including handling missing values and visualizing data through:
Heatmap of null values.
Pairplot of target and dependent variables.
Correlation matrix of variables.
Line plot of date and gold price.
Extraction of year from date for easy analysis.
Line plot of year and gold price.
Converted numerical target variable (gold price) into categorical variables 'high' and 'low' for classification purposes.
Dropped unnecessary variables and created dummy variables for categorical features.
Scaled the data using MinMaxScaler.
### Model Training and Evaluation
Trained the following:
#### Classification Models:
Logistic Regression
Decision Tree Classifier
Naive Bayes
Boosted Tree Model
Keras Classifier (deep learning)
##### Evaluated model performance using:
Classification report
Confusion matrix
ROC AUC value and curve

#### Regression Models:
Multiple Linear Regression
Utilized multiple linear regression to predict exact gold prices.
##### Evaluated regression model performance metrics:
R2 score
Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)
Maximum error
##### Visualizations
Created visualizations to assess model performance, including:
Scatter plot of actual vs. predicted values in linear regression.
Residuals vs. predicted values plot.
Line plot of actual vs. predicted values.
Scatter plot of actual vs. predicted values with indices.
## Conclusion
This project demonstrates the application of various machine learning and deep learning techniques to predict gold prices. By evaluating different models and techniques, we aim to provide insights into the factors influencing gold prices and improve predictive accuracy.

## Installation
Before running the code, make sure to install the required packages by executing the following commands:

pip install numpy pandas matplotlib seaborn scikit-learn
