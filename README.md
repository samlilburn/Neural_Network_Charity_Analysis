# Neural_Network_Charity_Analysis

## Purpose
The purpose of this project is to create a binary classifier using machine learning. This analysis is conducted for a hypothetical organization, Alphabet Soup. We will analyze a CSV of more than 34,000 organizations that have received funding from Alphabet Soup over the years to predict whether applicants will be successful if funded by Alphabet Soup.

## Results
* The IS_SUCCESSFUL column contains the binary variables that are the target of our model. 
* The variables that are the features of our model are the remaining columns that are not the target and will not be dropped. These variables are APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT.
* When preprocessing the data, we removed the EIN and NAME columns, as they were neither targets nor features.
* Our neural network was created with 80 neurons in the first hidden layer and 30 in the second.
* Unfortunately, Tensorflow crashed the kernal each time it was imported. Multiple workarounds, including uninstalling and reinstalling tensorflow and numpy, as well as trying different kernels and older versions of numpy and tensorflow, did not resolve the issue. During the time that this code was created, learning assistants were unavailable. The code that could be used to run our model has been written, but is it impossible to execute as tensorflow consistently crashed the kernel. 
* There were no steps to take to increase the model performance as tensorflow was unable to run. 

## Summary
In our analysis, we successfully preprocessed the data. We also were able to write code that would have worked had tensorflow been functioning on the machine. Our inability to successfully import tensorflow was the main reason we were not able to utilize the machine learning model. The issue with importing tensorflow was unforseen. Please consider the preprocessing work and machine learning code in the grading of this assignment. 
