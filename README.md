# Homework 14
# Deep Learning

The objective of this homework is to determine whether using the Crypto Fear and Greed Index (FNG) is predictive of BTC closing prices. The questions to answer are: 

Which model has a lower loss?
The approach using FNG data has higher loss, whereas using the prior closing price is more predictive when applying the LSTM modeling approach. 

The following plot shows the FNG time series. 


![image](https://user-images.githubusercontent.com/1499520/135772804-9932b903-cd98-4c87-beb0-16d4562644ad.png)



The following plot shows the closing prices. 


![image](https://user-images.githubusercontent.com/1499520/135773133-4057774f-80e5-4ee7-8db0-bd89ef756b8c.png)


Visual inspection shows that there is little strucutural correlation betweeen the two time series.  It is unlikely given the lagged data used by the LSTM model that using the FNG time series data will be predictive of the closing price. 


Which model tracks the actual values better over time?
The model using the prior closing price tracks the actual values better over time.

Which window size works best for the model?

Using the closing prices, the actual and predicted prices are shown below for various window sizes (1,2,4,6,8,10).  Window sizes of 1,2 and 8 better represent the actual price. 

Window size = 1:


![image](https://user-images.githubusercontent.com/1499520/135773008-82bb680d-04bf-4b4e-9230-6d4bc959a62d.png)


Window size = 2:


![image](https://user-images.githubusercontent.com/1499520/135773025-d854554c-e42d-4609-9cac-f4400eb73186.png)


Window size = 4:


![image](https://user-images.githubusercontent.com/1499520/135773028-a46274e8-7977-4ac3-93ed-abd839591949.png)


Window size = 6:


![image](https://user-images.githubusercontent.com/1499520/135773038-f05afd33-afd5-4f56-8659-8bf0574593f5.png)


Window size = 8:


![image](https://user-images.githubusercontent.com/1499520/135773047-7a4eaa09-16ca-4186-bd72-54a2f6da4afa.png)


Window size = 10:


![image](https://user-images.githubusercontent.com/1499520/135773051-85f16045-613d-4aac-8540-ca6b84b489e2.png)


Using FNG data: 

Window size = 1:

![image](https://user-images.githubusercontent.com/1499520/135773073-b8f62c19-4e93-4e3f-83a4-0e9b07c75a3a.png)


Window size = 2:


![image](https://user-images.githubusercontent.com/1499520/135773078-fd0484f0-07ca-4579-b0a3-f720ee9d78c8.png)


Window size = 4:


![image](https://user-images.githubusercontent.com/1499520/135773083-fa1b3836-909b-4eb5-ac80-4de5a244c02f.png)


Window size = 6


![image](https://user-images.githubusercontent.com/1499520/135773091-50abc6d1-3598-4f44-b540-446c8eff69c0.png)


Window size = 8


![image](https://user-images.githubusercontent.com/1499520/135773098-c159123c-68ed-49a3-a2c4-253148ad2b15.png)


Window size = 10:


![image](https://user-images.githubusercontent.com/1499520/135773104-5fd2aac5-be25-41d8-b1d4-0cb6b61e154f.png)


