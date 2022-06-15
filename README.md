# Project Name
> Outline a brief description of your project.


## Table of Contents
* [Problem Statement](#Problem Statement)
* [Description and Data Loading](#Description and Data Loading)
* [Data cleaning](#Data cleaning)
* [Exploratory Data Analysis](#Exploratory Data Analysis)
* [Linear Regression](#(#Exploratory Data Analysis))
* [Feature Selection](#Feature Selection)
* [Model evaluation](#Model evaluation)


## General Information
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

## The company wants to know:
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

## Objective:

- Develop a model to find the variables which are significant the demand for shared bikes with the available independent variables.
- It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. 



## Conclusions
- Our current model has an overall good accuracy. 
- Evaluating our model with test data gave us good values for 
  - __*R-Squared          : 0.8058*__
  - __*Adjusted R-squared : 0.7945*__
  - __*RMSE               : 0.096*__
- Equation of the Model
- __cnt = 0.1405 + 0.2343 `*` Year + 0.0872`*`Month_sep + 0.0669`*`weekday_Sat - 0.0551`*`season_spring + 0.0615`*`season_summer - 0.0972`*`season_winter - 0.2902`*`weathersit_Light_Snow -0.0817`*`weathersit_Mist + 0.0557`*`workingday + 0.48`*`temp - 0.1501`*`windspeed__ 
- Important Features for __increasing cnt of Rental Bikes__
    - __Month_sep__
    - __Saturday_Weekday__
    - __Season_Summer__
    - __Workingday__
    - __Temperature of the day__
- Features that __negatively affect the overall cnt of rental bikes__
    - __spring_season__
    - __summer_season__
    - __winter_season__
    - __Light Snow Weather__
    - __Mist Weather situation__
    - __windspeed__


- Coding Language
  - Python 3.0
- Libraries Used  
  - Numpy
  - Pandas
  - Seaborn
  - Matplotlib  
- Libraries used for model building
  - scikit-learn   



