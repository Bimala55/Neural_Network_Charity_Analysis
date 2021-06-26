# Neural_Network_Charity_Analysis
## Overview of the analysis:
In this project, we use the features in the provided dataset to help create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. A CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization. This project is comprised of 3 steps: Preprocessing the data for the neural network, Compile, train and evaluate the model &  optimizing the model.

## Results:
- Data Preprocessing
  - What variable(s) are considered the target(s) for your model?
      
      The IS_SUCCESSFUL column.
  - What variable(s) are considered to be the features for your model?
      
      The features that we are using are every column except the ones that we will drop.
  - What variable(s) are neither targets nor features, and should be removed from the input data?
      
      First features we drop are the 'EIN' & 'NAME'.
  
- Compiling, Training, and Evaluating the Model.
  - How many neurons, layers, and activation functions did you select for your neural network model, and why?
    
    The first hidden layer has 80 neurons, the second has 30 there is also an output layer. Each layer has an activation function. The first and second hidden layers have an activation function "relu" & the output layer is "sigmoid".
   
   
   ![first image](/Resources/image1.PNG
   )
   
  - Were you able to achieve the target model performance?
     
     I was not able to reach the target.
      
  - What steps did you take to try and increase model performance?
  
  Adding hidden layers,changing the number of neurons in each layer,changing the activation type, Drop the four non-beneficial ID columns.
  
 ## Summary
 
 The model did not reach the target of  higher than 75%  accuracy it ended up being 72.4% .The best way to increase the accuracy of the  model is to have more data. If we have solid data added to this model, the accuracy of this model will be much more concrete.
