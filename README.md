# Laptop-Price-Prediction

This project predicts the price of a laptop on giving its specification.


## Tutorial



https://github.com/mohit-iitbh/Laptop-Price-Prediction/assets/150344621/ca3b9b55-5e4a-4397-a6ff-a96d0a31df9c




<video width="800" height="400" controls autoplay loop>
  <source src="Laptop_price_prediction.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

## Overview
This system is designed to predict the price of a laptop in real-time, providing a comfortable environment to the user. We have developed a machine learning model using XG Boost Regressor to accurately predict the price of a laptop. 

## Data
This laptop dataset contains prices of a laptop on giving with its specification. Most of the columns in a dataset are noisy and contain lots of information. But with feature engineering we will get more good results. The only problem is we are having less data but we will obtain a good accuracy over it.
[Laptop Price Dataset](laptop_data (2).csv)

## Installation 
Version of the packages:<p>
1.numpy==1.26.2<p>
2.pandas==2.1.3<p>
3.scikit-learn==1.3.2<p>
4.validators==0.22.0<p>
5.zipp==3.17.0<p>
6.streamlit==1.28.2<p>

## Results:
Accuracy achieved on the models:<p>
1.Linear Regression: Accuracy (R2 Score)-> 79.06% <p>
2.Ridge Regression: Accuracy (R2 Score)-> 79.33%<p>
3.Decision Tree Regressor: Accuracy (R2 Score)-> 80.11%<p>
4.Random Forest Regressor: Accuracy (R2 Score)->85.36%<p>
5.XG Boost Regressor: Accuracy (R2 Score)->86.64%<p>

## Contribution:
Mohit Agarwala:- Modelling and hyperparameter tuning and assistance in deployment.<br />
Rahul Kumar:- Major work on deployment and assistance in modelling.<br />
Aditi Shukla:- Have done EDA, feature engineering and data cleaning.
