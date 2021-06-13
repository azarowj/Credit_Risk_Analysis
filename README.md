# Credit_Risk_Analysis

## Overview

- The primary purpose of this project is to train multiple machine learning models to determine credit risk. Then we evaluate the performance of the various models and make a recommendation on whether or not they should be used to predict credit risk. We will use RandomOverSampler, SMOTE, ClusterCentroids, SMOTEEN, BalancedRandomForestClassifier, and EasyEnsembleClassifier as our models.

## Results
What the various metrics mean:
  - Balanced Accuracy Score: How often our model is correct. Between 0 and 1. The closer to 1, the better the model.
  - Precision: How reliable a positive classification is. Low precision is indicative of a large number of false positives
  - Recall: Ability of the classifier to find all of the positive samples. Low recall is indicative of a large number of false negatives.
 
Our Results:
  RandomOverSampler:
  - The balanced accuracy score was approximately 0.65
  - The precision score was 0.01 for high-risk and 1 for low-risk
  - The recall score was 0.7 for high-risk and 0.61 for low-risk
  - An image of these results can be found [here](https://github.com/azarowj/Credit_Risk_Analysis/blob/main/RandomOverSampling.png)

  SMOTE:
  - The balanced accuracy score was approximately 0.66
  - The precision score was 0.01 for high-risk and 1 for low-risk
  - The recall score was 0.63 for high-risk and 0.69 for low-risk
  - An image of these results can be found [here](https://github.com/azarowj/Credit_Risk_Analysis/blob/main/SMOTE.png)
 
 ClusterCentroids:
  - The balanced accuracy score was approximately 0.54
  - The precision score was 0.01 for high-risk and 1 for low-risk
  - The recall score was 0.69 for high-risk and 0.4 for low-risk
  - An image of these results can be found [here](https://github.com/azarowj/Credit_Risk_Analysis/blob/main/ClusterCentroids.png)
 
 SMOTEEN:
  - The balanced accuracy score was approximately 0.67
  - The precision score was 0.01 for high-risk and 1 for low-risk
  - The recall score was 0.76 for high-risk and 0.58 for low risk
  - An image of these results can be found [here](https://github.com/azarowj/Credit_Risk_Analysis/blob/main/SMOTEENN.png)
 
 BalancedRandomForestClassifier:
  - The balanced accuracy score was approximately 0.79
  - The precision score was 0.03 for high-risk and 1 for low-risk
  - The recall score was 0.7 for high-risk and 0.87 for low-risk
  - An image of these results can be found [here](https://github.com/azarowj/Credit_Risk_Analysis/blob/main/BalancedRandomForest.png)
  
 EasyEnsembleClassifier:
  - The balanced accuracy score was approximately 0.93
  - The precision score was 0.09 for high-risk and 1 for low-risk
  - The recall score was 0.92 for high-risk and 0.94 for low-risk
  - An image of these results can be found [here](https://github.com/azarowj/Credit_Risk_Analysis/blob/main/EasyEnsemble.png)
  

## Summary
