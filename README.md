# Homework 14
# Deep_Learning

The objective of this homework is to determine whether using the Crypto Fear and Greed Index (FNG) is predictive of BTC closing prices. The questions to answer are: 

Which model has a lower loss?
The approach using FNG data has higher loss, whereas using the prior closing price is more predictive when applying the LSTM modeling approach. 

The following plot shows the FNG time series. 


![image](https://user-images.githubusercontent.com/1499520/135772804-9932b903-cd98-4c87-beb0-16d4562644ad.png)



The following plot shows the closing prices. 


![image](https://user-images.githubusercontent.com/1499520/135772834-cd5fdb00-5b89-491d-9d18-a725cb10214e.png)



Visual inspection shows that there is little strucutural correlation betweeen the two time series.  It is unlikely given the lagged data used by the LSTM model that using the FNG time series data will be predictive of the closing price. 


Which model tracks the actual values better over time?
The model using the prior closing price tracks the actual values better over time.

Which window size works best for the model?
