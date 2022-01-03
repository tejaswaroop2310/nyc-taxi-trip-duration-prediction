# NYC Car Trip Duration Prediction

## Project Intro/Objective
The purpose of the project is to build a model that predicts the total ride duration of taxi trips in New York City. Primary dataset is one released by the NYC Taxi and Limousine Commission, which includes pickup time, geo-coordinates, number of passengers, and several other variables.

The dataset is based on the 2016 NYC Yellow Cab trip record data made available in Big Query on Google Cloud Platform. The data was originally published by the NYC Taxi and Limousine Commission (TLC). The data was sampled and cleaned for the purposes of this project. Based on individual trip attributes, you should predict the duration of each trip in the test set.


### Methods Used
* Descriptive Statistics
* Explorative Data Analysis
* Data Cleansing
* Model Traing 
* Model Validation


### Technologies
* Python
* Pandas
* Numpy
* Seaborn
* Matplotlib

## Project Description

Predicting a trip duration isn’t something that has not been though upon. With the use of Google maps API one can find the estimated time it would take to move between two points in the city. However, a detailed analysis of the factors affecting a trip between two points in a city can be very useful for accurate and robust prediction. This research primarily focuses on the possible important factors that are used as attributes for the trip duration prediction in the New York City. 

This data can be used by taxi vendors for better services to the users. The research work not only uses a prediction model but also gives an in-depth analysis of the factors associated with the New York City taxi trips.

__Data Pre-processing__ : In order to prepare the data for the experiment, the data is cleaned to remove outliers. It involves removing the null values, replacing missing values with dummy values, and changing the format of the date and time values so as to utilize them in the algorithm. It also includes removal of outliers. 

__Data Visualisation__ : Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

__Model Selection and Evaluation__: Here we used linear regression and xgboost algorithm for this data set . Xgboost is very efficient compared to the Linear regression but xgboost will take more time to fit the data 
Conclusion: 
##Conclusion:
- Most of trip consist of passenger either 1 or 2. 
- Average trip duration is generally highest around 3 PM during the busy streets. 
-most of the trips were done at a speed range of 10-20 km/H. 
- Vendor 2 is evidently famous among the population 
- XGBoost proved to be much more efficient in predicting the output. But it takes much more time to train it over the large dataset with more complexity as compared to Linear regression model.



## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).







## Contributer

 Teja Swaroop Piduguralla (https://github.com/tejaswaroop2310)
