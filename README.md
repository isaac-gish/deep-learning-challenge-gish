# deep-learning-challenge-gish
Module 21 Challenge

## Overview
From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. 
The purpose of this analysis is to create a model measuring the likelhood of success who receive funding from "my business team" Alphabet Soup. 

### Results
* What is the target for your model?
     * The target for the model was the "IS_SUCCESSFUL" Column which is saved in the y variable.
* What is the features for your model?
     * The features for the model are every column EXCEPT for the "IS_SUCCESSFUL" column which is saved in the X variable.
* What variables should be removed for the sake of your model?
     * The EIN and NAME variables should be removed because these are only for the purpose of identification and are not needed for the model to get data to create an accuratae model.
* How many neurons/hidden layers/activation functions did you choose for your model and why?
     * After trying many models the model that gave me the highest accuracy included 3 layers, and a different amount of neurons in each. I ran 80/40/20 neurons respectively for each hidden model with a relu acivation in each input layer and sigmoid in the output layer. I decided to use 3 hidden layers because I thought I needed more processing power to get a higher accuracy. I decided to use 80/40/20 because I saw no difference in accuracy having each hidden layer at 80 neruons, but I did notice the model iterating slower.
* Were you able to acheie the wanted performance?
     * I was not able to acheive the wanted 75% accuracy, I was consistently between 72.5% and 73.5% accuracy with .56 loss.
* What steps did you take to try to increase the accuracy?
     * I tried to use different optimizations in compiling the model, increasing the amount of neurons, increasing the amount of hidden layers, and increasing the epochs.
### Summary
Overall, I was not able to meet the wanted 75% accuracy with my model, but I was able to get closer than my original model had by adding a 3rd hidden layer. This model would only be 73% accurate in predicting whether or not an organization would be successful so I would not reccommend it to be used in a real situation. 


## Code Classifications

All code for this challenge is found in the Starter_Code file. I was not asked to rename this file so I did not. 
All code in this file is mine, except for what was already provided. 
My model was updated several times but i just replaced the code that was there because I could not figure out how to open a HDF5 file.  
