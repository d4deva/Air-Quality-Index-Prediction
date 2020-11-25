# Air-Quality-Index-Prediction

## Problem Statement:
Predicting air quality is a complex task due to the dynamic nature, volatility,
and high variability in time and space of pollutants and particulates.
At the same time, being able to model, predict, and monitor air quality is becoming more and more relevant,
especially in urban areas, due to the observed critical impact of air pollution on citizens’ health and the environment.

![image](https://user-images.githubusercontent.com/65092287/100251880-46be2180-2f65-11eb-85b4-047d8aa127f0.png)
 
## Data Collection:
We have scraped the air quality data from https://en.tutiempo.net/. We have collected the data for the major cities of India like Mumbai, Delhi, Kolkata, and Bangalore. We made a dataset having more than 3500 records with 9 features.
Approach:
As we have collected the data our first approach was to clean the data and drop the unnecessary columns. Our target/dependent variable in the model was PM25. Further, we had prepared different models to predict the Air Quality Index based on different features.
### The models are as follows:
Model 1: Linear Regression using Stats model:

    We got the following score:
![image](https://user-images.githubusercontent.com/65092287/100253751-80902780-2f67-11eb-8686-483cf36f6073.png)

Model 2: Random Forest Regressor:

    After hyper tuning, the parameters we got the following results:
![image](https://user-images.githubusercontent.com/65092287/100253783-8d148000-2f67-11eb-8bae-9b1ad628da46.png)

 
We had compared both the models and selected model 2 for the prediction as the model accuracy had improved from 54% to 80% and RMSE score reduced from 47 to 30.
 
## Application:
We had made an Air Quality Index app using Tkinter. In the app, we are taking user inputs for different features that can be used to predict the Air quality index.

## App Snapshot:
 
![image](https://user-images.githubusercontent.com/65092287/100254247-10ce6c80-2f68-11eb-88b2-4d8125bf2ac8.png)
