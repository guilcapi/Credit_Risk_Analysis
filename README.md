# Credit_Risk_Analysis

## Overview

Apply machine learning to solve a real-world challenge: credit card risk. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, different techniques are used to train and evaluate models with unbalanced classes.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, the data is oversampled using the RandomOverSampler and SMOTE algorithms, and undersampled using the data from the ClusterCentroids algorithm. Then, a combinatorial approach of over- and undersampling using the SMOTEENN algorithm to see if that is better. Also reduce bias using two other ML models, BalancedRandomForestClassifier and EasyEnsembleClassifier. The performance of these models will be evaluated whether they should be used to predict credit risk.

## Results

### Oversampling

- Naive Random Oversampling

![](/Resources/3.png)

- SMOTE

![](/Resources/4.png)

### Undersampling

- Cluster Centroids

![](/Resources/5.png)

### Combination (Over and Under) Sampling

- SMOTEENN

![](/Resources/6.png)

### Ensemble Learners

- Balanced Random Forest Classifier

![](/Resources/1.png)

- Easy Ensemble AdaBoost

![](/Resources/2.png) 

## Summary

Easy Ensemble AdaBoost Classifier is the most effective ML model providing the best f1 score which balances accuracy and precision to consider the score. Precision is found to be low for all the models. 

Recommendation would be to use the Easy Ensemble AdaBoost Classifier as it classified the most true positives. 
