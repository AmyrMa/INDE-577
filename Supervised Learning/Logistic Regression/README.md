# Logistic Regression
## Data
Breast cancer is the most common cancer amongst women in the world. It accounts for 25% of all cancer cases, and affected over 2.1 Million people in 2015 alone. It starts when cells in the breast begin to grow out of control. These cells usually form tumors that can be seen via X-ray or felt as lumps in the breast area.
There total 30 features in this data set, and the dependent variable show whether the cancer type is Malignant or Benign.
## Introduction
Logistic regression was used in the biological sciences in early twentieth centery. Logistic regression is used when the dependent varaible is categorical.\
First step is to decide on an activation function before we deciding on a loss function here we choose the sigmoid activation function
$$\sigma (Z) = \frac{1}{(1+e^{-z})}$$
![alt text](https://github.com/AmyrMa/INDE-577/blob/main/Supervised%20Learning/Logistic%20Regression/log.png?raw=true)
## Decision Boundary
To predict which class a data belongs, a threshold can be set, based upon this threshold, the obtained estimated probability is classfied into classes.
In this example, we set the threshold at 0.65 because by observing data, we see that most patients will have result as M.
