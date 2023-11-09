# deep-learning-challenge

## 1. Data Preprocessing
> 
What variable(s) are the target(s) for your model?
* 'IS_SUCCESSFUL' column from application_df is the target variable for the model

What variable(s) are the features for your model?
* The features in terms of variables are every other column from application_df by dropping the 'IS_SUCCESSFUL' column from the unaltered dataframe

What variable(s) should be removed from the input data because they are neither targets nor features?
*Not being a target or a feature of the dataset, both 'EIN' and 'NAME' columns should be removed.


## 2. Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
* The first model used 8 hidden_nodes_layer1 and 5 hidden_nodes_layer2 -- these were random selections from which we later build upon during optimization.

Were you able to achieve the target model performance?
* The 75% accuracy target match was unsuccessful

What steps did you take in your attempts to increase model performance?
* In order to increase the model's performance the following actions were performed:
  > Addition of more layers to the model.
  >
  > Adding more hidden nodes.
  >
  > Removal of more colums during pre-processing.
  >
  > Changing the activation functions for each layer.


## 3. Summary:
The model had an overall final accuracy of 73.24% in classification prediction. There is more training required, by optimization to improve the accuracy of the model, this can be achieved with more refined correlation between the input and output. The pre-processing stage of the dataset was satisfactory, however the issue might lie in the inefficient use of ativation codes for the models. Perhaps experimentation with different combinations of layers, nodes and activation codes might improve the accuracy score.
