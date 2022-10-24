# Stock price prediction

## Project Description
This project uses Machine Learning and Deep Learning concepts to predict the closing stock prices of Apple Inc. (AAPL) based on historical stock price data for 10 years.

## Overview of steps

1. Apple Inc. (AAPL) quote historical data is downloaded from [Yahoo Finance ](https://finance.yahoo.com/quote/AAPL/history?p=AAPL). This stock data is used for historical data analysis and future stock price prediction.
2. Data visualization is used to analyse the closing stock prices over the years.
3. The dataset is then split into training set (80%) and testing set (20%).
4. Model is built, compiled and trained with different parameters.
5. Model is evaluated and the predicted closing stock prices are displayed against the actual prices using data visualization.

## Techniques used

### Data input and preprocessing
- The dataset .csv file is uploaded using the pandas library basic operations.
- The values in the training and testing datasets are normalized between 0 and 1 with MixMaxScaler.

### Data visualization
- Matplotlib library in python is used for data visualization throughout the project.

### Model building and training
- Long Short Term Memory networks (LSTMs) are a special type of Recurrent Neural Network capable of long-term dependencies.
- LSTMs have feedback connection, are able to store past important information, and forget irrelevant information. This makes them very suitable for stock price prediction problems.
- 'adam' optimizer (a stochastic gradient descent method) is used to decrease the loss by adjusting the weights in the network.
- Root Mean Square Error (rmse) is used as a loss function to evaluate the model performance.
- The model is compiled with the parameters above and then trained for 1 epoch.


### Final prediction
- Matplotlib library is used to plot the predicted closing stock prices against the actual prices.
