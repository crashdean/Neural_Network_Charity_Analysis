# Neural_Network_Charity_Analysis
 
 
## Overview of the Analysis

## Purpose

The fictional company Alphabest Soup needs to understand which applicant will be successful if given funding.  Use a deep learning model to 
determine if the data from over 34,000 orginizatons is successful.

## Results

### Data Processing

- Is_Successful is the target coulmn of the dataset
- APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, and ASK_AMT columns are features of the 
  model.
- EIN, NAME, STATUS, and SPECIAL_CONSIDERATION columns are nither targets nor features.

- Screenshot of data processing:

![](https://github.com/crashdean/Neural_Network_Charity_Analysis/blob/main/Resources/data_processing.png)

### Compiling, Training, and Evaluating the Model

- The first layer had 50 neurons with the sigmoid function. The second layer had 30 neurons with the relu function. The
  third layer had 20 neurons with therelu function,  The output layer used the sigmoid function.   The first layer used 
  the sigoid function because it help with the efficientcy of the model.
- The model did not acheive the 75% performance target.
- I changed the number of layers and neutrons in 3 differnt models to achieve a small gain in the performance.

![](https://github.com/crashdean/Neural_Network_Charity_Analysis/blob/main/Resources/deep_learning_model.png)


## Summary
