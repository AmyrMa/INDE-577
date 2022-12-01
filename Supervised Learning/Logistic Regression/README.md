# Logistic Regression
Logistic regression was used in the biological sciences in early twentieth centery. Logistic regression is used when the dependent varaible is categorical.\
First step is to decide on an activation function before we deciding on a loss function here we choose the sigmoid activation function
$$\sigma (Z) = \frac{1}{(1+e^{-z})}$$
![alt text](https://github.com/AmyrMa/INDE-577/blob/main/Supervised%20Learning/Logistic%20Regression/log.png?raw=true)
## Decision Boundary
To predict which class a data belongs, a threshold can be set, based upon this threshold, the obtained estimated probability is classfied into classes.
In this example, we set the threshold at 0.65 because by observing data, we see that most patients will have result as M.
