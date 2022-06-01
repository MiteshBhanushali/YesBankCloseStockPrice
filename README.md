# Yes Bank Close Stock Price prediction
Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has been in news because of the fraud case involving Rana Kapoor. Owing to this fact, it was interesting to see how that impacted the stock prices of the company and whether Time series models or any other predictive models can do justice to such situations. This dataset has monthly stock prices of the bank since its inception and includes closing, starting, highest and lowest stock prices of every month

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

# Regression Approach
It will be a regression model to predict the final bonds_aaa values with the above predicted clusters.

The solution code is divided into the following sections:

* Data understanding
* Preprocessing
* EDA
* Handle missing values
*  Cluster Classification
    * Feature Selection and Dimensionality Reduction using PCA
    * Baseline Model building
    * Cross Validation and Hyperparameter tuning
    * Model Evaluation
    * Model Selection
    * Ensemble Model Building

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)


# TIME SERIES ANALYSIS
### Time Series Analysis is a series that often presents itself in day to day situations and requires forecasting, be it stock prices, weather, etc.
  ##### In this project, we will forecast the "Closing Price " of Yes Bank (BSE) stock using various techniques.
  ###### The first step is to acquire the data that we perform using the Yahoo finance library, and then we present the Dickey-Fuller test, which is used to measure the stationarity of any Time Series.
###### After this step, we plot various graphs to ease the analysis using visual representation. Which is followed by multiple plots drawn to represent -
  - Seasonality
  - Trend
  - Correlation
  ###### These plots are followed by sampling the data into two parts the first 80% for training the model and the remaining for testing the model. We perform curve fitting using the ARIMA model based on minimisation of SMAPE(squared mean absolute percentage error).
  ##### To conclude, the predictions are adequately accurate, but as the model is dynamic, its value will vary in different time frames.

