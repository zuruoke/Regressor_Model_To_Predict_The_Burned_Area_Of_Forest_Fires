
A Machine Learning Regressor Model To Predict The Burned Area Of Forest Fires in the northeast region of Portugal by using meteorological data

Poor forest management and firefighting techniques make Portugal especially 
vulnerable to wildfires as climate change makes hotter, longer summers more likely.
A series of four initial deadly wildfires erupted across central Portugal in the afternoon of 17 June 2017 within minutes of each other, 
resulting in at least 66 deaths and 204 injured people - the largest loss of life due to wildfires in Portugal's history
An intense heat wave preceded the fires, with many areas of Portugal seeing temperatures in excess of 40 °C (104 °F)

The aim is to predict the burned area of forest fires, in the northeast region of Portugal, 
by using meteorological and other data (see details at: http://www.dsi.uminho.pt/~pcortez/forestfires)

In this ML kernel, I'll:

1. Prepare the data for machine learning -  
The target variable is very skewed towards 0.0 with no optimum value distribution, thus it will make sense to prepare the data for ML by modelling with the logarithm transform

2. Train a model using Random Forest and other Regressor models

3. Measure the accuracy of the model using RMSE and MSE
