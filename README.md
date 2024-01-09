# Advanced Regression Assignment

## **Problem Statement**

A US-based housing company named *Surprise Housing* has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

Which variables are significant in predicting the price of a house
- How well those variables describe the price of a house.
- Also, determine the optimal value of lambda for ridge and lasso regression.

**Business Goals**:

You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information

This assignment aims at designing and buidling an optimal Regression model to predict the price of houses in the Australian Real Estate market based upon the top features identified as per the regression model. It will be then used by management to understand the driving factors to buy a house in the real estate market. It will also allow management to understand the pricing dynamics if they want to explore a new real estate market.

## Conclusions

- As per the Lasso Regresison model(alpha = 0.001), Customers prefer

1. Houses which have just been contructed and sold i.e Newly Contructed Houses.
2. Houses whose Overall material and finish of the house is Excellent to Very Excellent.
3. Houses located within Crawford Neighborhood.
4. Houses with Typical Functionalities.

- As per the Ridge Regresison model(alpha = 8.0), Customers prefer

1. Houses with Typical Functionalities.
2. Houses located within Crawford or Stone Brook Neighborhood.
3. Houses whose Overall material and finish of the house is Very Good.
4. Houses whose Overall Condition is Excellent.

## Technologies Used

- [Python](https://www.python.org/) - version 3.11.5
- [Pandas](https://pandas.pydata.org/) - version 2.1.4
- [Numpy](https://numpy.org/) - version 1.26.2
- [Matplotlib](https://matplotlib.org/) - version 3.8.0
- [Seaborn](https://seaborn.pydata.org/) - version 0.13.1
- [Scikit-Learn](https://scikit-learn.org/stable/) - version 1.2.2

## Acknowledgements

The project was built using help and guidance based upon
- Live sessions of upGrad on Industry Relevance of Advance Linear Regression Models
- UpGrad tutorials on Advance Linear Regression

## Contact

Created by [@sharmaankit091](https://github.com/sharmaankit091)