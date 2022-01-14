# Credit Risk Analysis

## Overview

This analysis was created to model different resampling options in order to best predict credit risk. Imbalanced-learn and scikit-learn libraries were used to test oversampling, undersampling, and a combination of the two. Two machine learning models used to reduce risk, BalancedRandomForestClassifier and EasyEnsembleClassifier, were also ran before evaluating results. 

## Results

We will only be looking at balanced accuracy score, precision, and recall within our analysis to decide which model is best for credit risk prediction. The closer each result is to 1.00, the better. 

Balanced Accuracy Score - the average of recall obtained on each class
Precision - quantifies the number of positive class predictions that actually belong to the positive class
Recall - quantifies the number of positive class predictions made out of all positive examples in the dataset

Results for each model, shown below, were added to an excel sheet and attached for comparison. 

![image](https://user-images.githubusercontent.com/90646961/149574928-91b1c5f6-a0e2-48e7-abad-d2fe04d2e812.png)

[Credit Risk Scores.xlsx](https://github.com/brefrank/credit_risk_analysis/files/7872792/Credit.Risk.Scores.xlsx)

## Summary

After completing our analysis, it is clear that the random forest and AdaBoost classifier models yield the best results. This is because they are both emsemble learning models that run multiple algorithms and make a final predictions based on an accumulation of results. Athough the two have similar precision and recall results, AdaBoost had a significantly higher balanced accuracy score than the others and would be the best model for predicting credit risk.
