# Combined-Cycle-Power-Plant-Assignment

This is an assignment for the Machine Learning for Product Managers from Duke University (on coursera). 

We will build a model to predict the electrical energy output of a Combined Cycle Power Plant, which uses a combination of gas turbines, steam turbines, and heat recovery steam generators to generate power.  We have a set of 9568 hourly average ambient environmental readings from sensors at the power plant which we will use in our model.

The columns in the data consist of hourly average ambient variables:

- Temperature (T) in the range 1.81°C to 37.11°C,
- Ambient Pressure (AP) in the range 992.89-1033.30 milibar,
- Relative Humidity (RH) in the range 25.56% to 100.16%
- Exhaust Vacuum (V) in the range 25.36-81.56 cm Hg
- Net hourly electrical energy output (PE) 420.26-495.76 MW (Target we are trying to predict)

The dataset may be downloaded as a csv file here: https://archive.ics.uci.edu/ml/datasets/combined%2Bcycle%2Bpower%2Bplant

The goal is to select an appropriate model for modelling this prediction. We will try out various models such as Linear Regression, Liner Regression with Kfold validation, Ridge Regression, Lasso Regression and Polynomial Regression models. Based on the model that has the lowest MSE, we will select that model. 
