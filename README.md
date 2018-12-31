# IEOR-4720-Project-Team L
# Stock Price Movement Prediction using RNN and Attention RNN
## Aim
To examine the effectiveness of Attention Mechanism in RNN(LSTM) based stock price movement prediction method, based on Hong Kong stock market as well as stocks from S&P 500.

## Research Paper
Exploring Attention Mechanism in LSTM based Hong Kong Stock Price Movement Prediction, June 7, 2018 Quantitative Finance temppaper

## Datasets
1. Hong Kong stock data(daily): downloaded from Bloomberg(00800.HK to 00899.HK), some stocks may be dropped during data cleaning.
2. US stock data(daily): Randomly choose 100 stocks from S&P 500, data were downloaded here: https://www.kaggle.com/borismarjanovic/price-volume-data-for-all-us-stocks-etfs
### 1. Basic stock features: 
'Open', 'High', 'Low', 'Close', 'Volume', 
### 2. Technique Indicators (Calculated using python package TA-Lib):
'MA_Close', 'MA_Close_Returns', 'ROCP_Close', 'ROCP_Open', 'ROCP_High', 'ROCP_Low', 'ROCP_Volume', 'DIF', 'DEA', 'MACD', 'DIFROCP', 'DEAROCP', 'MACDROCP', 'RSI6', 'RSI16', 'RSI24', 'RSI6ROCP', 'RSI16ROCP', 'RSI24ROCP', 'BBAND_Up', 'BBAND_Mid', 'BBAND_Low', 'ROCP_Price_Volume', 'MA_Volume', 'MA_Volume_Returns'


## Files Instruction
1. Report: report.pdf
2. Codes:
   1) Paper_replication(tensorflow): paper_replication_model.ipynb
   2) Extention(tensorflow): 
   3) Result Visualization: 
   4) Models Validation(Keras): 
3. Indicators Creating: create_indicators.ipynb
4. Data ready for models: 
   HK data: processed_data_HK.csv
   US data: processed_data_SP.csv

## References
### 1. Papers
 
### 2. Codes
* RNN samplecode [[colab]](https://colab.research.google.com/drive/1CbSE6FLROhyE-e4GkroRrvf-fKVEMqRv)
* HUSEIN ZOLKEPLI's Stock-Prediction-Models repository [[github]](https://github.com/Circirmaa/Stock-Prediction-Models/blob/master/deep-learning/14.lstm-attention.ipynb)
### 3. Useful links
* [[Recurrent Neural Networks - LSTM Models]](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)


