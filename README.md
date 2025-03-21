# California Housing Market Trend Prediction

## Introduction
California’s housing market is known for its diversity and complexity, shaped by factors ranging from property characteristics to geographic location. This project aims to predict median house values in California using a variety of features, including:

- Median housing age
- Total number of rooms and bedrooms
- Total population and number of households
- Median household income
- Proximity to the ocean
According to the Federal Reserve Bank of Chicago (2018), neighborhood-level property and geographic characteristics can significantly influence housing values. Additionally, recent studies (Shi et al., 2022) suggest that natural landscape features, such as proximity to the ocean, may also impact property prices.

Our goal is twofold:

- Predict median house values using multiple features from the dataset 
- Identify which features are the most influential predictors of housing prices in California
Dataset
The dataset is sourced from Kaggle and originates from the 1990 California Census, published by the U.S. Census Bureau and USGS (United States Geological Survey).

- Observations: 20,640
- Features: 10
- Target variable: Median house value
- Notable variable: ocean_proximity (categorical geographic feature)

## Methods
This project is implemented using R and applies the following modeling techniques:

- Multiple Linear Regression
- LASSO Regression for feature selection and regularization
We evaluate the performance of our models using metrics such as RMSE (Root Mean Squared Error) and R^2 (coefficient of determination) to assess predictive accuracy.

## Objective
We seek to answer the following questions:

- How well can we predict median house values based on the available features?
- Which features are the most important predictors?
- How do different modeling approaches compare in terms of accuracy?
