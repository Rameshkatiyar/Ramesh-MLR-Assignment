# Project Name
> MLR-On-SharedBikesDemand (Linear Regression Assignment)


## Problem Statement:
Multiple linear regression model for the prediction of demand for shared bikes.
* Which variables are significant in predicting the demand for shared bikes?
* How well those variables describe the bike demands?


## Steps for MLR
- Reading, understanding and visualising the data
- Preparing the data for modelling (split training and testing data, rescaling etc.)
- Train the model
- Residual Analysis
- Predictions and evaluation on test set


## Conclusions
- After data processing the continuous variables: 'temp', 'atemp', 'hum', 'windspeed'
- After data processing the categorical variables: 'season', 'holiday', 'workingday', 'weathersit', 'yr', 'mnth', 'weekday'
- After model training the final model variables: 'temp', 'windspeed', 'weathersit', 'season', 'holiday', 'yr'
- Final model: cnt = 0.1656 + (temp0.4696) + (windspeed-0.1483) + (weathersit-0.1842) + (season*0.1245) + (holiday-0.0952) + (yr*0.2361)


## Technologies Used
- pandas
- numpy
- matplotlib
- seaborn
- sklearn
- statsmodels


## Contact
Created by [@Rameshkatiyar] - feel free to contact me!
