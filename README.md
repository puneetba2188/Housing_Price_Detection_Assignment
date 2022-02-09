# Project Name
Ridge and Lasso on house sale price prediction
> The purpose of this assignment is to build a regression model using regularisation in order to predict the actual value of the properties and decide whether to invest in them or not..

# Problem Statement
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

Which variables are significant in predicting the price of a house, and

How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression


## Table of Contents
* [General Info]
* [Technologies Used]
* [Conclusions]
* [Acknowledgements]


## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

The company is looking at prospective properties to buy to enter the market. We are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
Which variables are significant in predicting the price of a house, and  How well those variables describe the price of a house.
Determine the optimal value of lambda for ridge and lasso regression.

## Conclusions
a) The model was overfitted without doing the regularization validated with Linear Regression model
b) After using Ridge and Lasso model no more overfitted . The lambda values are 2 and .001 for ridge and lasso respectively.
Important Predictors are : OverallQual , GrLivArea , TotalBsmtSF , GarageArea , MSZoning_RH ,YearBuilt


## Technologies Used
Python - version 3.9
Numpy - version 1.20.1
Pandas - version 1.2.4

statsmodels - version 0.12.2
scikit-learn - version 0.24.2

## Contact
Created by [Puneet Bansal(puneet.bansal2188@gmail.com]
