# goldpriceprediction
## Overview
This project focuses on predicting gold prices using various machine learning and deep learning models. The models employed include logistic regression, decision tree classifier, naive Bayes, boosted tree model, Keras classifier, and multiple linear regression.

## Dataset
The dataset used for this project includes the following features:

- Date: The date of the observation.
- SPX (Standard & Poor's 500 Index): A stock market index that measures the stock performance of 500 large companies listed on stock exchanges in the United States.
- GLD (Gold ETF): Exchange-traded fund that aims to track the price of gold.
- USO (United States Oil Fund): Exchange-traded fund that tracks the price of oil.
- SLV (Silver ETF): Exchange-traded fund that aims to track the price of silver.
- EUR/USD (1 Euro = how much US Dollar): The exchange rate of euros to US dollars.
## Workflow
### Data Preprocessing and Visualization
The initial steps of this project involved importing essential libraries and data files. Subsequently, a comprehensive data preprocessing phase was executed, which encompassed addressing missing values and visually exploring the dataset. Various techniques were employed to gain insights into the data distribution and relationships, including generating a heatmap to identify missing values, creating pair plots to visualize relationships between target and independent variables, and constructing a correlation matrix to assess variable interactions. Furthermore, to facilitate analysis, the date column was parsed to extract the year, followed by a visualization of gold price trends over time. To prepare the data for classification tasks, the numerical target variable, representing gold prices, was discretized into categorical variables denoting 'high' and 'low' values. Redundant variables were removed, and categorical features were transformed into dummy variables. Finally, to ensure uniformity in feature scales, the data was normalized using the MinMaxScaler. These preprocessing steps laid a robust foundation for subsequent modeling and analysis.
### Model Training and Evaluation
Trained the following:
#### Classification Models:
- Logistic Regression
- Decision Tree Classifier
- Naive Bayes
- Boosted Tree Model
- Keras Classifier (Deep Learning)

##### Evaluated model performance using:
- Classification report
- Confusion matrix
- ROC AUC value and curve
- Training vs Validation Loss (For Keras Classifier)

#### Regression Models:
- Multiple Linear Regression

Utilized multiple linear regression to predict exact gold prices.
##### Evaluated regression model performance metrics:
- R2 score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- Maximum error
##### Visualizations
Created visualizations to assess model performance, including:
- Scatter plot of actual vs. predicted values in linear regression.
- Residuals vs. predicted values plot.
- Line plot of actual vs. predicted values.
- Scatter plot of actual vs. predicted values with indices.

## Conclusion
This project demonstrates the application of various machine learning and deep learning techniques to predict gold prices. By evaluating different models and techniques, we aim to provide insights into the factors influencing gold prices and improve predictive accuracy.

## Installation
Before running the code, make sure to install the required packages by executing the following commands:
###### pip install numpy pandas matplotlib seaborn scikit-learn
