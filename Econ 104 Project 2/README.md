# Project 2

**Description:** In this project, we fit multiple models to a time series dataset in order to find the best fit. The dataset we used was the USMacroG dataset of 12 Macroeconomic variables, and we filtered the set to 5 specific variables. We aimed to predict GDP and consumption growth based on the other three variables. 
* First, we looked at the autocorrelation functions of each variable and then fit multiple Arima models of different orders to the variables based on that.

* For each model, we utilized a training testing split and looked at the MSE/RMSE in terms of the accuracy of our models. We also looked at the AIC/BIC scores to look at which models were more accurate for our data.

* Next, we fit a VAR model to our variables of interest, GDP and Consumption growth, and conducted a granger test of causality and IRF test between the two. We also ran similar diagnostic tests like with the other models

* In the end, we settled on certain models that we thought were most optimal for our dataset. 
