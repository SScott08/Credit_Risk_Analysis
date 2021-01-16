# Credit_Risk_Analysis
Overview

LendingClub is a peer-to-peer lending service company that I assessed credit risk for. The number of good loans outnumber the number of risky loans, so I applied different techniques to train and evaluate the unbalanced classes. I used imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. I also evaluated the performance of these models and made a recommendation on whether they should be used to predict credit risk.

Results

Native Oversampling

![brfc](https://user-images.githubusercontent.com/68204195/104790162-a0fc8700-574b-11eb-8a83-a34467bf9c24.png)
 
precision: 0.01
recall: 0.74
f1: 0.02

SMOTE Oversampling

![cc](https://user-images.githubusercontent.com/68204195/104790026-3b0fff80-574b-11eb-8fce-1d1e8c275b78.png)


precision: 0.01
recall: 0.63
f1: 0.02

 
 
 


Summary

After comparing all the models used, none of them performed to the accuracy or precision needed to predict high risk loans. Having a dataset that is unbalanced with a small number of high risk loans is having an effect of the model performance, even when offsetting the distribution. I would recommend balancing the data by adding more high risk loan data to increase accuracy. 
