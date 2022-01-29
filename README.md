# Neural Network Charity Analysis

## Overview of the Neural Network Charity Analysis

### Purpose

In this analysis I will use the features in the provided dataset to help create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Neural Network Charity Analysis Results

- Data Preprocessing

	- What variable(s) are considered the target(s) for your model?
	
		'IS_SUCCESSFUL' column
    
	- What variable(s) are considered to be the features for your model?
	
		All the columns will be considered features, except for the ones that we plan to drop.
    
	- What variable(s) are neither targets nor features, and should be removed from the input data?
	
		'EIN' and 'NAME'	columns
	
- Compiling, Training, and Evaluating the Model

	- How many neurons, layers, and activation functions did you select for your neural network model, and why?
	
		The model has two hidden layers. The first hidden layer has 80 neurons with an activation function "relu". The second hidden layer has 30 neurons, and also has an activation function "relu". Our output layer has an activation function "sigmoid". 

	- Were you able to achieve the target model performance?
	
	  No I was not able to reach the target. 
  
	- What steps did you take to try and increase model performance?
	
	  Adding hidden layers, changing the number of neurons in each layer, changing the activation type, and changing the number of epochs.

## Neural Network Charity Summary

Overall, after dropping two features that I anticipated would not have impact on the model, the models accuracy ended up being 72.8%. I suspect I have to drop more features to increase the accuracy to 75% and ultimately improve how well the neural network performs. I could also attempt at obtaining more data to input, to ultimately increase the accuracy of this model.
