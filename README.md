# Neural_Network_Charity_Analysis

## Overview

Using the features in the dataset I created a Binary classifier that will help predict if the applicants will be funded by the charitable organization called Alphabet.
For this analysis we had a dataset containing various measures on 34,000 organizations that have been funded by Alphabet Soup. This project compromised of the following 3 steps:
* Preprocessing the data for the neural network
* Compile, Train and Evaluate the Model
* Optimizing the model

## Compiling, Training and Evaluating the Model

For the neural network model I have two hidden layers. My first layer had 30 neurons, the second has 25 there is also an output layer. The first and second hidden layer have the "relu" activation function and the activation function for the output layer is "sigmoid".

![]()

The model was able to reach a target of 72%

![]()

The steps taken to try and increase model performance

Attempt 1: Removed additional feature, that is the 'USE_CASE' column. Rest of the model components stayed the same, however model accuracy stayed at 72%



Attempt 2: Adding Additional neurons to hidden layers and additional hidden layers are added. The accuracy stayed the same as 72%


Attempt 3: Changing activation function of output layer from "sigmoid" to "tanh." The  accuracy stayed the same as 72%




## Summary 

The model ended up with the accuracy score of 72% after optimization.Furthermore, we could further also optimize our neural network by removing more features or simply adding more data to the dataset to increase accuracy. Since our accuracy score was not particularly up to the standard with neural networks, we could have used the Random Forest classifiers. This is because random forest is a robust and accurate model due to their sufficient number of estimators and tree depth. Also the random forest models have a faster performance than neural networks and could have avoided the data from being overfitted.
