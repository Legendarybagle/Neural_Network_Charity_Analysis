# Neural_Network_Charity_Analysis

## Overview
With machine learning and neural networks, use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results
* Data Processing
 * the 'STATUS' variable was the target for the machine learning algortithm.
 * every other value was used as a feature except for "NAME" and "EIN" which were dropped as they were unique idetifiers and thus entirely useless for the algorithm.
* Compiling, Training, and Evaluating the Model
 * soghetti
 * I used 8 Neurons in hidden layer 1 with "relu" activation function, and 5 nuerons in hidden layer 2 with "sigmoid" activation function. I played around with the numbers and functions until I found somehting that worked the best and this got 0.99895 accuracy which was the best.
 * I was able to achieve over 75% accuracy with this model.
 * in order to increase performance I moved the number of neurons in the first hidden layer from 5 to 8.
