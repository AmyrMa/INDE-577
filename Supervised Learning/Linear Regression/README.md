# Implementation of Linear Regression Model
## Data
Breast cancer is the most common cancer amongst women in the world. It accounts for 25% of all cancer cases, and affected over 2.1 Million people in 2015 alone. It starts when cells in the breast begin to grow out of control. These cells usually form tumors that can be seen via X-ray or felt as lumps in the breast area.
There total 30 features in this data set, and the dependent variable show whether the cancer type is Malignant or Benign.
## Introduction
Linear Regression is a machine learning algorithm based on supervised learning. Regression models a target prediction values based on independent varaibles. It is mostly used for finding out the realationship between variables and forecasting. 
![alt text](https://static.javatpoint.com/tutorial/machine-learning/images/linear-regression-in-machine-learning.png)

The linear model has the following equation:\
$Y =\beta X+\epsilon$
Where $\beta$ is the coefficient terms and X is our design matrix, also is the matrix of our independent varaibles. and $\epsilon$ is our model error. 

## Cost function
the different values for coefficients will produce different line of regression. the cost function is used to estimate the values of the coefficient for the best fit line.

## Important assumtions of Linear Regression
* Linear relationship between the features and target
* Small or no multicollinearity between the features
* Homoscedasticity Assumption
* Normal distribution of error terms
* No autocorrelations
