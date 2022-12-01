# Implementation of Perceptron
Perceptron is a linear classifier (binary). Also, it is used in supervised learning. It helps to classify the given input data.
The perceptron consists of 4 parts.

1.Input values or One input layer\
2.Weights and Bias\
3.Net sum\
4.Activation Function\
## Alogrithm 
![Alt Text](https://github.com/AmyrMa/INDE-577/blob/main/Supervised%20Learning/Perceptron/perceptron.gif?raw=true)
The notations for the algorithm are as follows:
* $X^{(i)}$ is the p-dimensial input vector
* $y^{(i)}$ is the label of result
* $\eta$ is the learning rate
* $\phi(z)$ is the activation function 
* $w_t$ is the weight vector at epoch t
The perceptrons trained in following steps
1. all inputs x are multiplied with their weights w
2. add all the multiplied values and call them weighted sum
3. apply that weighted sum to the correct activation function

