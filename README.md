# Rainwater_Harvesting_Catchment_Area_Prediction

This repo contains 3 Machine Learning models which predicts the amount of rainfall in different states of India, amount of rainfall in different districts of West Bengal, and also predicts the underground catchment area depending on the predictions of the first two models.

## Model 1 [Rainfall_India]
### This model predicts the amount of rainfall received by the different states of India for the next 365 days. The 'rainfall in india 1901-2015' dataset has been used to train, test and validate the model.
![india](https://user-images.githubusercontent.com/90722648/202116688-50842fba-dbd8-456e-8460-3f4afc4a79eb.png)

## Model 2 [Kolk_Rainf_Pred]
### In this model, we use the rainfall, precipitation and moisture content data given in the official website of West Bengal Meteorological Department. After scaling and normalisisng this data, we use it to test and train this model. It predicts the amount of rainfall received by the different districts of West Bengal for the next 365 days.

![wb](https://user-images.githubusercontent.com/90722648/202116780-9d3c7b09-b151-449a-ba28-3d1b693c761e.png)
## Model 3 [Underground_Area_pred]
### This model calculates the underground catchment area for storing the excess rainwater collected via rainwater harvesting, depending on the predicted rainfall for the next 365 days, obtained from the Machine Learning model 1 and 2.
![train test](https://user-images.githubusercontent.com/90722648/202116758-814fe179-f8df-4597-a839-f5619816fe05.png)
