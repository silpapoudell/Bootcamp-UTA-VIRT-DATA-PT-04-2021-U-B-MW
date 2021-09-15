# Supervised Machine Learning and Credit Risk

# Module 17  Assignment 


## Overview of the analysis:

The purpose of this analysis is to create a supervised machine learning model that can preciously predict credit risk.

## Results:

Naive Random Oversampling
Accuracy Score: 67.4%
Precision High Risk: 1%
Precision Low Risk: 100%
Recall High Risk: 72%
Recall Low Risk: 63%

SMOTE Oversampling
Accuracy Score: 66.2%
Precision High Risk: 1%
Precision Low Risk: 100%
Recall High Risk: 66%
Recall Low Risk: 66%


Cluster Centroid Undersampling
Accuracy Score: 51.3%
Precision High Risk: 0%
Precision Low Risk: 100%
Recall High Risk: 61%
Recall Low Risk: 42%


SMOTEENN Sampling
Accuracy Score: 68.1%
Precision High Risk: 1%
Precision Low Risk: 100%
Recall High Risk: 76%
Recall Low Risk: 60%


Balanced Random Forest Classifying
Accuracy Score: 64.8%
Precision High Risk: 56%
Precision Low Risk: 100%
Recall High Risk: 30%
Recall Low Risk: 100%

Easy Ensemble Classifying
Accuracy Score: 92.3%
Precision High Risk: 6%
Precision Low Risk: 100%
Recall High Risk: 91%
Recall Low Risk: 94%





## Summary:

This project aims to find the best model which can detect the high risk on investment. 
we need to find a model that lets the least amount of high risk investment pass through undetected. 


Based on above data, Would like to recommend for predicting high risk loans is Easy Ensemble Classifying Model.  