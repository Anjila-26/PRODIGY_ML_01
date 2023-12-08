# Linear Regression for Housing Prices

## Overview
This repository contains Python code for predicting house prices using linear regression. The dataset used includes various features such as living area, number of bedrooms, bathrooms, and total rooms.

## File Structure
- **Data**: Contains the dataset (`train.csv`) and the test dataset (`test.csv`).
- **PRODIGY_ML_01.ipynb**: Jupyter notebook with the main code for data analysis, model training, and predictions.
- **README.md**: Short and sweet guide to understand the code.

## Instructions
1. Install the required Python libraries: pandas, seaborn, matplotlib, numpy, scipy, and scikit-learn.
2. Run the Jupyter notebook (`Linear_Regression_Housing_Prices.ipynb`) step by step to understand the analysis and model training.
3. The trained model is used to make predictions on the test dataset (`test.csv`), and results are visualized.

## Code Highlights
- Data exploration and visualization using Seaborn and Matplotlib.
- Log transformation of the target variable (`SalePrice`) for better model performance.
- Testing feature normality using the Shapiro-Wilk test.
- Training a linear regression model on the original and log-transformed data.
- Evaluation of the model using Mean Squared Error, Root Mean Squared Error, and R2-squared.
- Visualization of model predictions compared to actual prices.

## Results
The linear regression model shows reasonable predictive performance. Predicted sale prices are transformed back from the logarithmic scale for interpretability.
