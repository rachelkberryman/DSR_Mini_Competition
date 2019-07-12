# DSR Mini Competition
3-day Kaggle Competition for participants of Data Science Retreat.

## About the Mini Competition
The mini-competition allows participants to complete a start to finish data science project. 
Participants will recieve training data (in CSV format) and a supplementary dataset.

The target variable is **Sales**. 
On the final day, participants will receive a test data CSV in the same format (same columns, etc) as the training CSV. 

## Scoring Criteria:
### 1. RMSPE 
Submissions are evaluated on the Mean Squared Error. You can find the scikit-learn metric for easily calculating MSE [here](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.mean_squared_error.html#sklearn.metrics.mean_squared_error). 
The highest score (lowest MSE) will receive a score of 10 for the scoring criteria section.
Each lower score (higher MSE) will receive a score of 10-(1 * number in ranking). If they are ranked second, score will be 10-2 = 8. 

### 2. Test Coverage
(@Adam please fill in here)

### 3.Reproducability
Your final model and any feature engineering steps/pipelines may be in Python script form, or in a jupyter notebook.
They should be in a repository that Rachel and Adam can access.
If we can run your package/script/notebook with no errors, you will receive bonus points of __.
For each error in running that must be corrected, bonus points will decrease by 1. 
(@Adam please fill in here)
