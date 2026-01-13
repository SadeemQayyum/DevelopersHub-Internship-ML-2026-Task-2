Task 2: Stock Price Prediction Using Linear Regression

Objective

The objective of this task is to predict short term stock prices using historical market data. This task focuses on applying a regression based machine learning model to analyze stock price trends and evaluate prediction accuracy.

Dataset Description

The dataset consists of historical stock price data downloaded using the Yahoo Finance API.
It includes daily trading information such as:

Open price

High price

Low price

Closing price

Trading volume

The dataset represents one year of stock price data for a selected company.

Tools and Libraries Used

Python

Pandas for data handling

yfinance for downloading stock data

Matplotlib for data visualization

Scikit learn for machine learning

Steps Performed

Imported required Python libraries

Downloaded historical stock price data

Selected relevant features for prediction

Split the dataset into training and testing sets

Trained a Linear Regression model

Predicted stock prices on test data

Evaluated model accuracy using R squared score

Visualized actual and predicted prices

Results and Observations

The model achieved an accuracy of 96 percent

Predicted prices closely followed actual prices

The model captured short term trends effectively

Minor prediction errors occurred due to market volatility

Conclusion

This task demonstrates that Linear Regression can be effectively used for short term stock price prediction. The high accuracy indicates strong model performance, but real world market fluctuations limit perfect predictions. The model is suitable for basic trend analysis and learning purposes.

How to Run

Open the Jupyter Notebook file

Run each cell sequentially

Ensure required libraries are installed and internet access is available
