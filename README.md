## ABOUT DATASET
* <b>source:</b> [Kaggle](https://www.kaggle.com/datasets/rohanrao/nifty50-stock-market-data?select=BHARTIARTL.csv)
    * It contains 52 .csv files of various companies 
* <b><u>BHARTIARTL.csv</u></b> : I have used this file for analysyis and modeling
    * Reason ( Why this dataset? ) : I am an Airtel mobile user so decided to do analysis on this dataset. 
    * Features in Dataset : Refer [Kaggle](https://www.kaggle.com/datasets/rohanrao/nifty50-stock-market-data?select=BHARTIARTL.csv)
    * Dataset Contains Stock prices from 2002-02-18 to 2021-04-30
    * Dataset of parent company Airtel contains data of two sub companies 'BHARTI' and 'BHARTIARTL'
    * I have trained my model on 'BHARTI' similar approach can be done on 'BHARTIARTL'

## ABOUT NOTEBOOK
* <b><u>Airtel_Stock_Price.ipynb :</u></b>
    * Notebook contains the code, analysis, and results of a project aimed at predicting stock prices.
    * The notebook contains machine learning algorithms, such as Polynomial Regression, LSTM, to make predictions.
    
## MODELS USED
* <h3><b><u>Polynomial Regression</u></b></h3> 
    <b>Reason( Why? ) :</b> I have used this model because  it can capture nonlinear relationships between variables. In the case of stock price prediction, it is often the case that the relationship between the predictors and the response variable is not linear. By using a polynomial regression, you can fit a curve to the data that better captures the underlying relationship, potentially improving the accuracy of your predictions.
* <h3><b><u>Long Short-Term Memory</u></b> </h3>
    <b>Reason( Why? ):</b> I have used LSTM because LSTM is well-suited for time-series data analysis and prediction. LSTM networks have the ability to remember past information for long periods of time and selectively forget information that is no longer relevant, making them particularly effective for analyzing sequences of data with complex dependencies. For stock price prediction, LSTM can be used to analyze historical data and identify patterns that may be indicative of future trends in the stock market. By training the network on a dataset of past stock prices and associated market conditions, the LSTM can learn to recognize patterns and make predictions about future stock prices.
