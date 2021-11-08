# Neural_Network_Charity_Analysis 

## Neural_Network_Charity_Analysis Overview
  The purpose of this analysis was to use features in the provided dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Neural_Network_Charity_Analysis Results
 - Data Preprocessing
  - The "IS_SUCCESSFUL" column is the target for the model.
  - All other columns besides "IS_SUCCESSFUL", "EIN", and "Name" are the features for the model.
  - EIN and NAME are the variables removed from the input data.

 - Compiling, Training, and Evaluating the Model
  - There were 100 neurons, 3 layers, and 2 activation function selected for the neural network model.
  - I was not able to achieve the target model performance.
  - In order to optimize the model to improve its accuracy as close to 75% as possible, I retrained the model 3 times.

## Neural_Network_Charity_Analysis Summary
 - The results of the model before optimization was a loss of 0.9015 and an accuracy of 0.4879. After training the model 3 times for optimization the final loss 5.5332 and an accuracy of 0.4755. I recommend using a different activation function for a different result on each layer. 
