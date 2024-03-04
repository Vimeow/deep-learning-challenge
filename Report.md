Date: 04/03/2024
Person: Vy Nguyen
Assignment: Module 21 - Deep learning challenge using neuron network model (Keras)

# Module 21 Report

## Overview of the Analysis

The nonprofit organization Alphabet Soup is seeking a solution to assist in the selection of funding recipients with the highest likelihood of success in their endeavors. In this project, a machine learning and neural network model was developed which utilized the dataset provided by the Alphabet Soup to develop a binary classifier capable of predicting the success of applicants who receive funding from Alphabet Soup.

## Results:

### Data Preprocessing

1. What variable(s) are the target(s) for your model?
   The 'IS_SUCCESSFUL' variable is the target.

2. What variable(s) are the features for your model?
   Other variables except 'IS_SUCCESSFUL' variable are the features for the model.

3. What variable(s) should be removed from the input data because they are neither targets nor features?
   'EIN' and 'NAME' variables were removed, because they were neither targets nor features for the model.

### Compiling, Training, and Evaluating the Model

1. How many neurons, layers, and activation functions did you select for your neural network model, and why?

To start the model with, I randomly selected three layers:

-First hidden layer with 4 neurons and "relu" as an activation function.
-Second hidden layer with 4 neurons and "relu" as an activation function.
-An Output layer with 1 neuron and "sigmoid" as an activation function.

2. Were you able to achieve the target model performance?

I did not manage to reach the target of achieving a model accuracy of 75%.

3. What steps did you take in your attempts to increase model performance?

In my first attempt, I added more layers, and increased the number of neurons in each layer which resulted in the increased in accuracy from 72.2% to 72.6%.

In my second attempt, I used Auto optimisation method to choose the best model. However, the accuracy still only 72.9%.

In my third attempt, I increased the number of layers, neurons and epochs that Auto optimisation method could create. However, there were too many combinations (trials) generated and the accuracy at the end still not reached 75.0%, only 73.1%.

### Summary:

In summary, the created neural network model achieved about 73% accuracy. A few attempts to change the number of layer, neuron and epoch as well as using different activation function seems to not improve the model accuracy. To increase the accuracy of the model, potentially simplify the number of features in the dataset and choosing those features with high correlation with the target variable might help with training the model.
