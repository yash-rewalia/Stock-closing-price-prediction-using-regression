# Stock-closing-price-prediction-using-regression
The ultimate business objective is to leverage the regression model to provide accurate predictions of the closing price of AMRN stock, enabling stakeholders to make well-informed investment decisions, manage risks effectively, optimize portfolios, Early warning systems to alert any fraud cases and align investment strategies with financial goals.
![image](https://github.com/yash-rewalia/Stock-closing-price-prediction-using-regression/assets/142087449/4d07f118-d81b-45d5-975f-9388bc13b069)


# Project Summary
The objective of this project is to analyze the closing stock prices of Amarin Corporation plc. It is an Irish-American biopharmaceutical company founded in 1993 and headquartered in Dublin, Ireland and Bridgewater, New Jersey. The company develops and markets medicines for the treatment of cardiovascular disease. The dataset used in this project consisted of daily stock prices of AMRN for the last 1 year from today, including closing, opening, highest, and lowest and adjacent stock prices and volume of shares.

To predict the stock's closing price, I developed four models namely Linear Regression, Ridge_regression, Lasso_regression, and Random Forest model was developed. The model was trained using the historical stock price data and various features such as mean of Open, High and Low faetures.Additional features were engineered by taking lags to capture the temporal trends and patterns in the data.The performance of the model was evaluated using metrics like MSE ( Mean Squared Error) because we used LeaveOneOut cross validation so we can't use R2 score.

The analysis aimed to uncover any patterns or changes in stock prices.

![image](https://github.com/yash-rewalia/Stock-closing-price-prediction-using-regression/assets/142087449/62bc890a-540a-4c9c-b3bf-7a774ee1c19f)


Overall, the project aimed to contribute to a better understanding of the relationship between the closing stock prices of AMRN, and to explore the potential of predictive models in the financial domain. The findings and insights gained from this project can be utilized by investors, analysts, and decision-makers to make informed investment or business decisions related to AMRN's stock.

# Problem statement
Amarin Corporation plc is an Irish-American biopharmaceutical company founded in 1993 and headquartered in Dublin, Ireland and Bridgewater, New Jersey. The company develops and markets medicines for the treatment of cardiovascular disease.It is focused on discovering, developing and delivering innovative treatments and new therapeutic approaches that can make a difference in CVD patients' lives. In addition to the ground-breaking science and clinical development, Amarin is highly motivated to improve patient care while creating value for shareholders and society. These are just some of the BOLD ways we are changing the course of CVD. We fetch this real time actual data through APi with the help of rapidapi platform and this dataset has daily stock prices of the AMRN since one last year and includes closing, opening, highest, lowest and adjacent close stock prices. The main objective is to predict the stock’s closing price.

A Stock or share (also known as a company’s 'equity') is a financial instrument that represents ownership in a company. Units of stock are called "shares." Stocks are bought and sold predominantly on stock exchanges, though there can be private sales as well, and are the foundation of many individual investors' portfolios.

# Objective
The ultimate business objective is to leverage the regression model to provide accurate predictions of the closing price of AMRN stock, enabling stakeholders to make well-informed investment decisions, manage risks effectively, optimize portfolios, Early warning systems to alert any fraud cases and align investment strategies with financial goals.

Steps involved are:-

1.Know Your Data

2.Understanding your Data

3.Data Cleaning

4.Data Manipulation

5.Data Visualization

6.Hypothesis Testing

7.Feature Engineering & Data Pre-processing

8.Data Splitting and ML Model Implementation:-

a. Linear Regression

b. Ridge Regression

c. Lasso Regression

d. Random Forest Regressor

# Conclusion
The main goal of the project is to create a machine learning model which can predict the closing price of AMRN stock, keeping in mind of the opening, closing, high price and similar features.

I have developed 4 models Linear-regression, Ridge_Regression, Lasso_regression and Random_forest.
Random_forest model shows promising result with mse score of 0.0240 overall, therefore it can be used to solve this problem. It also considering all new added features and taking care of multicollinearity.

Using data visualization on our target variable, we can clearly see the stock price behaviour over the months and something happens in the month of Oct 2023 in which the hitted bottom.

We found that the distribution of all our variables is approximately normal but volume is positively skewed. so we performed log transformation on them to come on common scaling.

I considered to take mean of Open, High and Low faetures.Additional features were engineered by taking lags to capture the temporal trends and patterns.


The dataset has only daily related prices for a year, 5 to 10-year data would be more accurate as model can analyze important patterns like week opening price and weekend price. Volume of the data if provided can also be useful in making prediction. A stock prediction involved many aspects like holidays, political decisions, events, un precedented disasters, human decisions. This can be better predicted by having all these features and using time series models like ARIMA and LSTM can ve predicted more accurately.

Given the dataset and features, Our model is performing well on all data-points.
With our model making predictions with such high accuracy, we can confidently deploy this model for further predictive tasks using future data.

