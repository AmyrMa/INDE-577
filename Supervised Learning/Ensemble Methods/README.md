# Ensemble Methods
In this file, we have used the following model
* Bagging
* Random Forest
* Ada Boosting
* Gradient Boosting

The data we used for these model is breast cancer diagnosis.
## Bagging
![alt text](https://raw.githubusercontent.com/RandyRDavila/Data_Science_and_Machine_Learning_Spring_2022/4d096531067c187165c2e980277ee7ae97a91b10/Lecture_9/Bootstrapping.png)
The term bagging referes to bootstrap aggregating, the general idea of bagging is divide the data into several small models, and use it to train and test the data, then taking the majority vote or average weight for the output.

## Random Forest
The idea of random forest can be illustrate as the following diagram:
![alt text](https://github.com/AmyrMa/INDE-577/blob/main/Supervised%20Learning/Ensemble%20Methods/randfor.png?raw=true)
It is very intuitive, we use multiple decision tree model for one dataset, and the idea is similar to the bagging.

## Ada Boosting
Ada Boosting short for the adaptive boosting. Ada boosting is most widely used with decision tree with one level.

## Gradient Boosting
Gradient boosting is a type of machine learning boosting. It relies on the intuition that the best possible next model, when combined with previous models, minimizes the overall prediction error. 
