# Advanced-regression-assignment
> This project aims to build regression models using regularization techniques to predict house prices in Australia based on various features of the houses.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- This project involves building predictive models for house prices using data analytics.
- Background: A US-based housing company, Surprise Housing, is entering the Australian market and aims to buy houses below their actual value to flip them at higher prices.
- Business Problem: The goal is to accurately predict house prices to make informed investment decisions.
- Dataset: The dataset consists of various features of houses sold in Australia, including information like the number of rooms, square footage, neighborhood, and more.

## Conclusions
- The optimal alpha value for Ridge Regression is 200.
- The optimal alpha value for Lasso Regression is 1.
- Lasso Regression is preferred for this dataset due to its ability to perform variable selection and simplify the model.
- Significant variables in predicting house prices include OverallQual, GrLivArea, GarageCars, and TotalBsmtSF among others.

## Technologies Used
- pandas - v1.2.4
- numpy - v1.20.3
- seaborn - v0.11.1
- matplotlib - v3.4.2
- scikit-learn - v0.24.2
