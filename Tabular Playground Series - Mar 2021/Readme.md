# Competition link -
https://www.kaggle.com/c/tabular-playground-series-mar-2021/data


# Data Description -
For this competition, you will be predicting a binary target based on a number of feature columns given in the data. All of the feature columns, cat0 - cat18 are categorical, and the feature columns cont0 - cont10 are continuous.

# Solution Approach
Perform EDA to understand the dataset better.
Used XGBoost and Lightgbm(tuned via Optuna) to get the results.
To boost the performance agggregated the results from both the models.
