# Advanced-Regression

# Project Name
>  Advanced Regression - Surprise Housing


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)



## General Information
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.
- The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
- The company wants to know:
- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.
- Also, determine the optimal value of lambda for ridge and lasso regression.

## Conclusions
- For Ridge regression, the alpha value = 1.0
- From the Ridge regression, the top 5 important variables are:
-- GrLivArea
-- TotalBsmtSF
-- OverallQual
-- OverallCond
-- GarageCars

- For Lasso regression, the alpha value = 0.0001 
- From the Lasso regression, the top 5 important variables are : 
-- GrLivArea
-- TotalBsmtSF
-- OverallQual
-- OverallCond       
-- YearBuilt        


## Technologies Used
- Python 3.2
- library - pandas
- library - numpy
- library - matplotlib.pyplot
- library - seaborn
- library - warnings
- library - sklearn
- library - statsmodels.api
- library - PolynomialFeatures, MinMaxScaler, LabelEncoder
- library - LinearRegression, Ridge, Lasso
- library - mean_squared_error, r2_score
- library - variance_inflation_factor
- library - train_test_split
- library - MinMaxScaler

## Analysis done by Roshni Siddoju
The following file are added to the GIT

1. data_defination.docx
2. train.csv
3. Assignment_Part_2.pdf
4. Roshni Siddoju_Advanced Regression.ipynb
