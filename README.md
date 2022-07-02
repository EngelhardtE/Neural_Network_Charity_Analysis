
# Neural_Network_Charity_Analysis

## Overview

The purpose of this project was to use machine learning and neural networks to help a charity predict if recipients of their funding would be successful in using it to accomplish their philanthropic goals. Given a csv of over 34,000 potential organizations, a neural network in formed using Python to determine where the money should be granted. 

The three main steps to completing this project are as follows: 

- Preprocessing the data for the neural network

- Compile, train and evaluate the model

- Optimizing the model

## Results

### Data Preprocessing 

- The target variable was IS_SUCCESSFUL 

- For this model, feature variables include everything except for the following: IS_SUCCESSFUL, NAME, EIN

- NAME and EIN were dropped because they were deemed unnecessary for determining which organizations were most likely to be successful if granted funding


### Compile, Train and Evaluate the Model

- For this neural network model, I chose to use 3 hidden layers with 80, 30, and 15 nodes respectively. Sigmoid and relu activation were used. 

![Nodes ](Resources/Nodes.png) 

- I was only able to achieve accuracy of 72.87%, missing the goal of 75%. 
- In order to attain a higher accuracy score across my three attempts, I adjusted the number of nodes per hidden layer, as well as the activation methods. 

## Summary
