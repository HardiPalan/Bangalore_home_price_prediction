# Bangalore Home Price Prediction

This project aims to predict home prices in Bangalore based on various features such as location, square footage, number of bedrooms (BHK), and bathrooms. We have used machine learning models to build a predictive system using historical data to assist users in estimating house prices.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Model Building](#model-building)
- [Results](#results)

## Project Overview

Real estate prices in Bangalore have been volatile, with significant variations based on location and other factors. In this project, a machine learning model is built to predict house prices in Bangalore using data from various sources. The goal is to provide users with a tool to estimate the prices based on available property details.

## Dataset

The dataset used in this project contains the following key features:
- **Location**: Locality where the property is located
- **Total sqft**: Total area of the property in square feet
- **Bath**: Number of bathrooms
- **BHK**: Number of bedrooms, halls, and kitchens
- **Price**: Price of the property (dependent variable)

## Exploratory Data Analysis

A detailed Exploratory Data Analysis (EDA) was performed to understand the distribution and relationships of the features. Key steps include:
- Handling missing values
- Removing outliers based on domain knowledge (e.g., unrealistic price per square foot)
- Visualizing correlations between features using heatmaps
- Studying location-based price trends

## Model Building

Several machine learning algorithms were employed to build predictive models, including:

1. **Linear Regression**: Simple and interpretable model for a baseline prediction.
2. **Lasso Regression**: To manage overfitting and select important features.
3. **Decision Tree**: For capturing non-linear relationships in the data.

Key evaluation metrics:
- **R² Score**
- **Mean Absolute Error (MAE)**

## Results

The Random Forest model provided the best results in terms of prediction accuracy. The final model metrics are as follows:

- **R² Score**: 0.84
- **Mean Absolute Error (MAE)**: 11.2%

This suggests that the model can explain 84% of the variance in house prices, with an average error of 11.2% in predicting the prices.
