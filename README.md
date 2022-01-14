# Credit Risk Analysis

## Overview

This analysis was created to model different resampling options in order to best predict credit risk. Imbalanced-learn and scikit-learn libraries were used to test oversampling, undersampling, and a combination of the two. Two machine learning models used to reduce risk, BalancedRandomForestClassifier and EasyEnsembleClassifier, were also ran before evaluating results. 

## Results

We will only be looking at balanced accuracy score, precision, and recall within our analysis to decide which model is best for credit risk prediction. The closer each result is to 1.00, the better. 

Balanced Accuracy Score - the average of recall obtained on each class
Precision - quantifies the number of positive class predictions that actually belong to the positive class
Recall - quantifies the number of positive class predictions made out of all positive examples in the dataset

Results for eash model, shown below, were added to an excel sheet and attached for comparison. 

Model Name	Naive Random Oversampling	SMOTE Oversampling	Undersampling	Combination Sampling	Balanced Random Forest Classifier	Easy Ensemble AdaBoost Classifier
Balanced Accuracy Score	0.62	0.65	0.51	0.64	0.79	0.93
Precision	0.99	0.99	0.99	0.99	0.99	0.99
Recall	0.65	0.66	0.44	0.57	0.91	0.94
![image](https://user-images.githubusercontent.com/90646961/149574928-91b1c5f6-a0e2-48e7-abad-d2fe04d2e812.png)


## Summary

There is a summary of the results
There is a recommendation on which model to use, or there is no recommendation with a justification
