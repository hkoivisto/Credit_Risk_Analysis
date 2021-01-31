# Credit_Risk_Analysis

## Overview

In this analysis supervised machine learning is used to determine how loan and applicant features predict low risk or high risk loans. Linear Regression, Balanced Random Forest Classification, and Easy Ensemble Classification are each used to analyze a data set of over 60,000 loans. Linear Regression is run using four different sampling techniques to account for target class imbalance:  Random Oversampling, SMOTE Oversampling, Cluster Centroid Undersampling, and SMOTEEEN combination sampling. The results of the six different models is described below.

## Results

  - Random Oversampling Linear Regression
       - Balanced Accuracy: 0.58
       - Precision: 0.99
       - recall: 0.59
  - SMOTE Oversampling Linear Regression
       - Balanced Accuracy: 0.60
       - Precision: 0.99
       - recall: 0.66
   - Cluster Centroid Undersampling Linear Regression
       - Balanced Accuracy: 0.50
       - Precision: 0.99
       - recall: 0.0
  - SMOTEEEN sampling Linear Regression
       - Balanced Accuracy: 0.62
       - Precision: 0.99
       - recall: 0.57
  - Balanced Random Forest Classifier
       - Balanced Accuracy: 0.64
       - Precision: 1.00
       - recall: 1.00
  - Easy Ensemble AdaBoost Classifier
       - Balanced Accuracy: 0.65
       - Precision: 1.00
       - recall: 1.00
       
## Summary

Overall, the ensemble classifier models yielded a more accurate prediction model for this data than the linear regression models.

The recommended machine learning model is the EasyEnsemble classifier due to it's highest balanced accuracy score, though a score of 0.65 does not lend a high level of confidence to the model.
