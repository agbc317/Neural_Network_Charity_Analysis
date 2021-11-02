# Neural_Network_Charity_Analysis

## Overview of the analysis: The purpose of this analysis is to predict the most profitable investments.

## Results:
- What variable(s) are considered the target(s) for your model?

The variable used as the target for this model is the IS_SUCCESSFUL variable.
- What variable(s) are considered to be the features for your model?

The variables that are considered features include the application types, ask amount, income amounts, special considerations, use case, classification, and organization.
- What variable(s) are neither targets nor features, and should be removed from the input data?

- How many neurons, layers, and activation functions did you select for your neural network model, and why?

<img width="1121" alt="Screen Shot 2021-11-01 at 7 35 13 PM" src="https://user-images.githubusercontent.com/82230495/139763157-b0039932-c461-4410-b0d7-15fd28821386.png">

My model has two hidden layers, one with 65 neurons and the second with 75 neurons. Both of them are using the relu activation function. I also have an output layer with a sigmoid activation function. I went through 50 different trials and found that this was the combination that had the highest accuracy I was able to achieve. I also changed my number of epochs to 300 from 100. 

<img width="517" alt="Screen Shot 2021-11-01 at 7 35 49 PM" src="https://user-images.githubusercontent.com/82230495/139763564-eec28665-9794-459d-b7ac-500716c087b2.png">


- Were you able to achieve the target model performance?

I was not able to achieve the target model performance. I could get to .71 accuracy but once I got there any changes that I made drove my accuracy down to .43 accuracy.

- What steps did you take to try and increase model performance?

I changed the number of hidden layers and neurons within each of those layers. I tried changing the activation function for all of the layers as well. 

## Summary: 
The overall results of the deep learning model were that I was able to predict the successful investments with about 70% accuracy although it was very sensitive to any changes in the model.

I would recommend using a model with more neurons as it seems that with more neurons the model became more accurate. I would also recommend increasing the number of epochs as this also seemed to help the accuracy of the model.
