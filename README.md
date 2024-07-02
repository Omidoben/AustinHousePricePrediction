
# House Price Prediction Using XGBoost

## Overview

This project focuses on predicting house prices using an XGBoost regression model. The dataset contains various features such as location, property details, and other attributes that influence house prices. The goal is to build a predictive model that can accurately estimate the latest sale price of a house based on these features. The model is evaluated using metrics like RMSE, MAE, and R-squared to ensure its performance and reliability.





## Objectives
#### Data Preprocessing:

- Clean and preprocess the dataset to handle missing values, encode categorical variables, and transform features as necessary.
- Split the data into training and test sets to evaluate model performance.
#### Exploratory Data Analysis (EDA):

- Analyze the distribution of house prices and other key features.
- Visualize relationships between features and the target variable to gain insights into factors affecting house prices.
#### Feature Engineering:

- Create new features or transform existing ones to enhance the predictive power of the model.

#### Model Building and Tuning:

- Implement the XGBoost model using the tidymodels framework in R.
- Tune hyperparameters using techniques like grid search and ANOVA racing to optimize model performance.
#### Model Evaluation:

- Evaluate the model using metrics such as RMSE, MAE, and R-squared on both training and test datasets.
- Interpret the results and assess the model's accuracy and generalizability.
#### Visualization and Interpretation:

- Visualize the importance of features in the model using variable importance plots.
- Interpret the results, including the impact of log-transformation on the prediction errors.
#### Deployment:

- Prepare the model for deployment using the vetiver package in R.


## Libraries 
- Tidyverse
- Tidymodels
- vip
- finetune
- vetiver
- DataExplorer
- patchwork
- ggcorrplot

