# Hourly-Energy-Consumption-Forecast
 Hourly Energy Consumption forecast model


## Goal:
* **Leverage historical consumption data to build time series model to predict future energy consumption**


## Steps:
* Load the data
  * *Data comes already clean as it's a Kaggle Dataset - the main goal is to build the ML model in this situation, not the other parts of regular project*
* Explore & visualize the data
* Split the data to Train & Test set
* Create the ML model using XGboost
  * assign the features & target
  * evaluate the model predictions
* Leverage the created model to estimate future consumption
* Evaluate the RMSE of the model

Feel free to check the full list of steps in details within this **[Jupyter Notebook](https://github.com/Oussamahajoui/Hourly-Energy-Consumption-Forecast/blob/main/hourly%20energy%20consumption%20forecast%20model.ipynb/ 'Hourly Energy Consumption Forecast Model')**

## Findings:
Following are the model future forecast alongside the initial data we had:
![image](https://user-images.githubusercontent.com/83676274/200187465-35e6576e-7e97-465c-bbd0-d96c83e6a5a3.png 'Initial data & forecast')

As you can see the future forecast does not contain seasonal peak values as the initial data. There is still room for improvements for the model, that can be achieve by for instances:
* Adding more features *(weather data, calendar holidays, etc.)*
* Conduct better cross validation
* Try different ML algorithms, test & compare

Model score:
* RMSE Score on Test set: **1342.5605**

 ## Data Sources:
* Hourly Energy Consumption Commonwealth Edison (ComEd) - [Kaggle Data](https://www.kaggle.com/datasets/robikscube/hourly-energy-consumption?select=COMED_hourly.csv/ "Kaggle Data" )
 

###### *Made by Oussama Hajoui*
