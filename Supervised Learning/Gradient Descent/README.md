# Gradient Descent
The Gradient Descent method lays the foundation for machine learning and deep learning techniques. In this project, we will use Breast Cancer Diagnosi data set to test our model.
## Introduction 
The Gradient Descent method lays the foundation for machine learning and deep learning techniques. The idea of the Gradient Descent is to find local minimum or maximum of a function in order to reduce it's cost.
## Requirements 
The given function has to be differentiable and convex, here are some examples:
![alt text](https://raw.githubusercontent.com/AmyrMa/INDE-577/main/Supervised%20Learning/Gradient%20Descent/grad_1.webp)
To check if the function is convex, we find the second derivative of the function and see if it is always postive.

## Algorithms 
In the case of a univariate function, it is simply the first derivative at a selected point. In the case of a multivariate function, it is a vector of derivatives in each main direction (along variable axes). Because we are interested only in a slope along one axis and we don’t care about others these derivatives are called partial derivatives.
