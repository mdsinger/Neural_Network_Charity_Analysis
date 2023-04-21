# Neural_Network_Charity_Analysis

## Purpose

The purpose of this analysis was to use machine learning and neural networks to predict if new applicants will be successful if funded by Alphabet Soup.

## Results

* What variable(s) are considered the target(s) for your model?

The target variable is whether new applicants will be successful if funded by Alphabet Soup.

* What variable(s) are considered to be the features for your model?

The features for this model are application type and income.

* What variable(s) are neither targets nor features, and should be removed from the input data?

Identification variables such as EIN and Name were removed from the data because they are neither targets, nor features.

* How many neurons, layers, and activation functions did you select for your neural network model, and why?

I used two hidden layers, an input layer, and an output layer. The activation functions were relu and sigmoid.

* Were you able to achieve the target model performance?

No, the highest accuracy level I acheived was 66%.

![image](https://user-images.githubusercontent.com/114033254/233732062-ad8ab320-17e5-4420-b437-697463a6a9d7.png)

## Summary

This model was not successful in predicting success for applicants of Alphabet Soup. Logistic regression might be a better fit for deciding the likelihood of success for applicants.
