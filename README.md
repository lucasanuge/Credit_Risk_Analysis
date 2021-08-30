# Credit_Risk_Analysis

## Overview of Project
The purpose of this project is to apply machine learning to solve credit card risk. Using a given dataset from LendingClub, we will be oversampling the data using **RandomOverSampler** and **SMOTE** algorithms, undersampling the data using **ClusterCentroids** algorithm, a combined approach of oversampling and undersampling using **SMOTEEN** algorithm, and lastly compare **BalancedRandomForestClassifier** and **EasyEnsembleClassifier** machine learning models to reduce bias.

## Results
- Cluster Centroids Undersampling showed the worst results with a balanced accuracy score of 0.5443. This shows that is can only successfully predict credit risk correctly at only 54.43% of the time. This is nearly a 50/50 chance hence is only slightly better than a coin toss.
![Cluster Centroids Undersampling](images/Cluster_Centroids_Undersampling.PNG)

Looking at the Imbalanced Classification Report (ICR), on the f1 column, we see that the average/total is 0.56 and the F-score to be just 0.01. The results from the ICR are also too low to predict credit risk.
![Cluster Centroids Undersampling](images/Cluster_Centroids_Undersampling_f.PNG)
