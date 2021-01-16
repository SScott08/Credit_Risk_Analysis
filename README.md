# Credit_Risk_Analysis
Overview

LendingClub is a peer-to-peer lending service company that I assessed credit risk for. The number of good loans outnumber the number of risky loans, so I applied different techniques to train and evaluate the unbalanced classes. I used imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. I also evaluated the performance of these models and made a recommendation on whether they should be used to predict credit risk.

Results

Native Oversampling


 
precision: 0.01
recall: 0.74
f1: 0.02

SMOTE Oversampling

![smote](https://user-images.githubusercontent.com/68204195/104790595-7e1ea280-574c-11eb-9859-449bfdd58025.png)


precision: 0.01
recall: 0.63
f1: 0.02

 Undersampling
 
 

precision: 0.01
recall: 0.67
f1: 0.01

Combination Sampling






![ros](https://user-images.githubusercontent.com/68204195/104790553-5cbdb680-574c-11eb-8258-5c7bf38c5556.png)

precision: 0.01
recall: 0.70
f1: 0.02

Balanced Random Forest Classifier

![brfc](https://user-images.githubusercontent.com/68204195/104790162-a0fc8700-574b-11eb-8a83-a34467bf9c24.png)

precision: 0.01
recall: 0.70
f1: 0.06

Easy Ensemble AdaBoost Classifier

![eec](https://user-images.githubusercontent.com/68204195/104790207-c12c4600-574b-11eb-82b6-27915b62e227.png)

precision: 0.09
recall: 0.92
f1: 0.16


Summary

After comparing all the models used, none of them performed to the accuracy or precision needed to predict high risk loans. Having a dataset that is unbalanced with a small number of high risk loans is having an effect of the model performance, even when offsetting the distribution. I would recommend balancing the data by adding more high risk loan data to increase accuracy. 
