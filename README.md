# nyc-taxi-trip-duration-prediction
Predicting a trip duration isn’t something that has not been though upon. With the use of Google maps API one can find the estimated time it would take to move between two points in the city. However, a detailed analysis of the factors affecting a trip between two points in a city can be very useful for accurate and robust prediction. 
This research primarily focuses on the possible important factors that are used as attributes for the trip duration prediction in the New York City. This data can be used by taxi vendors for better services to the users. The research work not only uses a prediction model but also gives an in-depth analysis of the factors associated with the New York City taxi trips. 

Data Pre-processing :
In order to prepare the data for the experiment, the data is cleaned to remove outliers. It involves removing the null values, replacing missing values with dummy values, and changing the format of the date and time values so as to utilize them in the algorithm. It also includes removal of outliers.
 Data Visualisation :
 Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

Model Selection and Evaluation :
Here we used linear regression and xgboost algorithm for this data set . Xgboost  is very efficient compared to the Linear regression but xgboost will take more time to fit the data 
Conclusion:
•	Most of trip consist of passenger either 1 or 2.
•	Average trip duration is generally highest around 3 PM during the busy streets.
•	most of the trips were done at a speed range of 10-20 km/H.
•	Vendor 2 is evidently famous among the population
•	XGBoost proved to be much more efficient in predicting the output. But it takes much more time to train it over the large dataset with more complexity as compared to Linear regression model.


