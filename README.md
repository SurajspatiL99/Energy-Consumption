# Time Series Forecasting for Hourly Energy-Consumption
- Led a data-driven analysis of the PJM-West region Hourly Energy Consumption, identifying key trends and patterns and developing a predictive model to forecast future demand
- Utilized pandas for data preprocessing and feature engineering, to extract valuable insights from the raw data and create new features that improved model performance
- Leveraged Seaborn's powerful visualization capabilities to create clear and concise plots that effectively communicated complex patterns in the data
- Developed an XGBoost Regressor model to predict future energy consumption using time series data
- Conducted K-folds cross-validation technique to evaluate the model's performance and ensure robustness, further improving the model's accuracy, generalization ability, and reliability

### This is actual Hourly Energy-Consumption for 18 years

![image](https://user-images.githubusercontent.com/101862962/221345394-c30d0403-4533-47c5-9846-5fe0b256d611.png)

## The following are the treads in energy consumption:-
 1. by time of the day
 ![image](https://user-images.githubusercontent.com/101862962/221345567-49569ce0-ed83-479d-81e4-2cb5525f75a0.png)
 
 2. by day of the week 
 ![image](https://user-images.githubusercontent.com/101862962/221345584-b2dc5d6e-28f5-437c-bf67-3c0b227db567.png)
 
 3. by month of the year
 ![image](https://user-images.githubusercontent.com/101862962/221345596-8999c388-67a3-4221-acda-398ad0c99290.png)
 
 4. by week of the year
 ![image](https://user-images.githubusercontent.com/101862962/221345614-3b7502d9-ff4d-490f-be6b-21d7a2e27312.png)

### Performing 5 fold cross validation

![image](https://user-images.githubusercontent.com/101862962/221345469-d3c1deb9-4a09-45d9-b327-472a8cb5d7ab.png)

### The following is the prediction for year 2019 using the trained XGBoost model

![image](https://user-images.githubusercontent.com/101862962/221345717-65e97671-a0f9-43c1-acd2-37f4e5b936cd.png)

### These were the important features according to XGBoost

![image](https://user-images.githubusercontent.com/101862962/221345756-04e630e0-aeb1-4fb7-876c-daa7e4caa200.png)

