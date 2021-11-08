# Neural_Network_Charity_Analysis

## Overview of the analysis: ##

Alphabet Soup’s is a non-for-profit organization that is dedicated to help organizations that works on protecting the environment, improve people wellbeing and unify the world.In this project, Alphabet Soup would like to analyse the impact of each donation and potential recipients for those funds. Ideally, this will help the company to make sure that the foundation’s funds are utilized efficiently. Therefore, we will work to predict which organizations worth receiving those funds and which one are considered a high risk. To do this accurately, and since this project is complex, we have decided to design and train a deep learning neuron network model using a Python Tensor flow library. This module will evaluate all types of input data and produce a clear decision-making result to determine which organizations should receive donations.

## Results:

Data Preprocessing:

* 	What variable(s) are considered the target(s) for your model?

o	The 'IS_SUCCESSFUL,' column from this dataset will be the targeted data point for these predictions.

* What variable(s) are the features for your model?

o	All other variables (columns) were included as features for this prediction except 'IS_SUCCESSFUL, "NAME" & "EIN

* What variable(s) are neither targets nor features, and should be removed from the input data?

o	The following columns "NAME" and "EIN" should be dropped. 

* How many neurons, layers, and activation functions did you select for your neural network model, and why?

o	In the first neural network model we performed 8 In the hidden_nodes_layer1and 5 in the hidden_nodes_layer2. For the 1st & 2nd hidden layer the activation was “relu”, while in the Output layer we used “Sigmoid”. The total parameters were 403.We used 100 epochs to train the module. The accuracy was 53% and the loss was 70%.

![alt text](http://url/to/img.png)

o	To achieve the 75% accuracy (was not met), we had to make the following changes to the module in attempt 1, 2 & optimization: 70 In the hidden_nodes_layer1 and 30 in the hidden_nodes_layer2. The total parameters were 5,241. We used 100 epochs to train the module. The accuracy was 55% and the loss was 72.4%.

![alt text](http://url/to/img.png)

o	 In the 2nd attempt we changed the layers to 90 In the hidden_nodes_layer1 and 50 in the hidden_nodes_layer2. The total parameters were 8,561. We used 100 epochs to train the module. The accuracy was 55.7% and the loss was 72.6%.

![alt text](http://url/to/img.png)

o	In the optimization model we changed the layers to 100 In the hidden_nodes_layer1 and 50 in the hidden_nodes_layer2. The total parameters were 9,501. We used 100 epochs to train the module. The accuracy was 55.9% and the loss was 72.5%.

![alt text](http://url/to/img.png)

In each attempt and in the optimization the model's weights are saved every 5 epochs. 

## Summary:

The model indicates that there is a 72.50% accuracy (after optimization) that the organizations worth receiving those funds from Alphabet Soup. If we would like to produce more accuracy, we would need more data points to be included in this module.
