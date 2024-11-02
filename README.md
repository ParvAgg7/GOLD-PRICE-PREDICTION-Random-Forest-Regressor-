# GOLD-PRICE-PREDICTION-Random-Forest-Regressor-

Overview

This project involves predicting the price of gold (GLD) using various financial and commodity features. The primary goal is to build a machine learning model that can accurately forecast gold prices based on historical data of related features such as crude oil price (USO), silver price (SLV), and currency exchange rate (EUR/USD). The project includes data exploration, feature engineering, model training, evaluation, and visualization of results.
Project Steps:

Data Loading and Exploration: Load the dataset, check for missing values, and understand the data                                   distribution through summary statistics.


Correlation Analysis: Identify relationships between features using correlation matrices and visual                         heatmaps.


Data Preprocessing: Prepare the data for model training by selecting relevant features and target                          variables, and splitting the data into training and testing sets.

Model Training: Train a RandomForestRegressor to build a predictive model.


Model Evaluation: Use metrics like R-squared to assess the performance of the model and visualize the                   comparison between actual and predicted gold prices.


Visualization: Plot distributions and results to gain better insights into data patterns and model                    performance.

Libraries Used

  Pandas: For data manipulation, cleaning, and exploration.

  
  NumPy: Used implicitly within Pandas for numerical operations.

  
  Matplotlib: For plotting and visualizing data and model results.

  
  Seaborn: For creating advanced visualizations like heatmaps and distribution plots.

  
  Scikit-Learn (sklearn):

  
  train_test_split: For splitting the dataset into training and testing subsets.

  
  RandomForestRegressor: For building a regression model to predict GLD prices.

  
  LinearRegression (optional): Used for comparison purposes.

  
  Metrics (r2_score): To evaluate the model's performance.
