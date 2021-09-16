# Supervised Machine Learning and Credit Risk


## Overview of the analysis:

The purpose of this analysis is to create a supervised machine learning model that can preciously predict credit risk.

## Results:

Naive Random Oversampling
Accuracy Score: 67.4%
Precision High Risk: 1%
Precision Low Risk: 100%
Recall High Risk: 72%
Recall Low Risk: 63%

<img width="539" src="https://github.com/gyanwaliElizaa/Bootcamp-UTA-VIRT-DATA-PT-04-2021-U-B-MW/blob/main/Pypoll-03/result.PNG">


SMOTE Oversampling
Accuracy Score: 66.2%
Precision High Risk: 1%
Precision Low Risk: 100%
Recall High Risk: 66%
Recall Low Risk: 66%


<img width="539" src="https://github.com/gyanwaliElizaa/Bootcamp-UTA-VIRT-DATA-PT-04-2021-U-B-MW/blob/main/Pypoll-03/result.PNG">

Cluster Centroid Undersampling
Accuracy Score: 51.3%
Precision High Risk: 0%
Precision Low Risk: 100%
Recall High Risk: 61%
Recall Low Risk: 42%


<img width="539" src="https://github.com/gyanwaliElizaa/Bootcamp-UTA-VIRT-DATA-PT-04-2021-U-B-MW/blob/main/Pypoll-03/result.PNG">


SMOTEENN Sampling
Accuracy Score: 68.1%
Precision High Risk: 1%
Precision Low Risk: 100%
Recall High Risk: 76%
Recall Low Risk: 60%


<img width="539" src="https://github.com/gyanwaliElizaa/Bootcamp-UTA-VIRT-DATA-PT-04-2021-U-B-MW/blob/main/Pypoll-03/result.PNG">


Balanced Random Forest Classifying
Accuracy Score: 64.8%
Precision High Risk: 56%
Precision Low Risk: 100%
Recall High Risk: 30%
Recall Low Risk: 100%

<img width="539" src="https://github.com/gyanwaliElizaa/Bootcamp-UTA-VIRT-DATA-PT-04-2021-U-B-MW/blob/main/Pypoll-03/result.PNG">


Easy Ensemble Classifying
Accuracy Score: 92.3%
Precision High Risk: 6%
Precision Low Risk: 100%
Recall High Risk: 91%
Recall Low Risk: 94%


<img width="539" src="https://github.com/gyanwaliElizaa/Bootcamp-UTA-VIRT-DATA-PT-04-2021-U-B-MW/blob/main/Pypoll-03/result.PNG">






## Summary:

This module is for finding the best model which can detect whether loan is high risk or not.  
That correlating statistic for this is the recall rate for high risk. 

The model that I would recommend to use is the Easy Ensemble Classifying model. 