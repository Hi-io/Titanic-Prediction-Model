# Titanic-Prediction-Model
This is a model created to join into machine learning competition from Kaggle. 
We'll use machine learning (Multiple Linear Regression) to create a model that predicts which passengers survived the Titanic shipwreck.

To make the predictive model we will use the following data:
* Ticket Class: 1st, 2nd, 3rd
* Sex: Male or Female
* Age in years
* Number of sibilings / spouses aboard the Titanic
* Number of parents / children aboard the Titanic

We use the ** Multiple Linear Regression** model to give each of these data a coefficient and create the model with the smallest possible margin of absolute error.

### Multiple Linear Regression Model
In reality, there are multiple variables that impact the survivor rate. When more than one independent variable is present, the process is called multiple linear regression. An example of multiple linear regression is predicting Titanic survivors using the data mentioned before.

**Coefficient:** [-0.09639983  0.49457377 -0.00578526  0.03080681 -0.04160372]

**Intercept:**  0.7530729994245616

 **Coefficient** and **Intercept**  are the parameters of the fitted line.
Given that it is a multiple linear regression model with 5 parameters and that the parameters are the intercept and coefficients of the hyperplane, sklearn can estimate them from our data.
