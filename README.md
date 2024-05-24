# Deep-Learning-Challenge
## Background

In this Challenge, the nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

## Overview of the Analysis

Data Preprocessing

1. What variable(s) are the target(s) for your model?
   - From application_df, target variable is `IS_SUCCESSFUL`
2. What variable(s) are the features for your model?
   - All other columns from application_df are features, with the exception of `EIN` and `NAME`
3. What variable(s) should be removed from the input data because they are neither targets nor features?
   - `EIN` and `NAME` columns were dropped 

Compiling, Training, and Evaluating the Model

1. How many neurons, layers, and activation functions did you select for your neural network model, and why?
   - First attempt, 2 layers with 8 & 5; second attempt, 3 layers with 10, 8, & 6; third attempt, 3 layers with 12, 10, 8. These were all randomly selected.
2. Were you able to achieve the target model performance?
   - No, I didn't reach the 75% accuracy target. I was only able to get 73% accuracy.
3. What steps did you take in your attempts to increase model performance?
   - Attempted to add more layers with additional nodes.

## Summary

Overall, the deep learning model achieved approximately 73% accuracy in solving the classification problem. Enhancing the correlation between input and output variables would likely improve prediction accuracy. This improvement could be attained by performing more thorough data preprocessing initially, experimenting with different activation functions, and iterating the model until higher accuracy is achieved.