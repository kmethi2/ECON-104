# Project 3
**Description:** In this project, we analyzed two types of data, Panel Data and Qualitative Dependent Variable data. 

* Panel Data Model
  * In this section of the project, we utilized the Grunfeld investment panel dataset from the AER package, with 5 macroeconomic variables concerning US manufacturing firms.
  * After doing some analysis of the variables and their correlation, we first fit the pooled model which didn't take into effect any time or individual differences.
  * Next, we fit a fixed effects model with time, individual effects, and both effects together and tested that against our pooled model for each type of effect
  * Lastly, we fit a random effects model to the data and compared that with the fixed and pooled model and then concluded our optimal model from our results

* Qualitative Dependent Variable Models
  * In this section of the project, we worked with a dataset concerned with predictign whether an individual is a foreigner or not based on other variables.
  * After doing some general analysis of our variables, we first fit a general linear probability model to the data and analyzed how well it did in its predictions.
  * We then fit probit and logit models and ran similar analyses to see how effective the models were in accurately predicting the binary variable.
  * After selecting our preferred model, we conducted some final tests to see ow reliable our model was in predicting whether an individual was a foreigner or not
