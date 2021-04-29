## Problem Statement
The problem is to build and test a model that will predict the tone (neutral or negative) of the text message. To do this, you will need to train the model on the data provided. The resulting model has to predict the class (neutral or negative) and test results reported on test data that was not used to train the model. An ideal model should not miss predicting a negative tone in the message text.

## Data
There is one .csv file that has 18900 rows with 3 columns: TextID, text, sentiment

### Inferences
To capture the almost every negative tone text message, we will have to look at recall metrics. We need to focus on improving the negative class recall so as to make sure we don't miss out on any negative text

### Future Improvements
1. HyperParameter Tuning of each Model
2. Checking Feature Importance and keeping only the necessary features
3. Trying other ML models
4. Use word embeddng approach/ Deep Learning Approach
