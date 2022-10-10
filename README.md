# Credit Risk Analysis

## Purpose and Overview of the Analysis

Fast-lending wants to use Machine Learning to get a more accurate identification of good candidates for loans, leading to lower default rates. The purpose of this project was to apply machine learing to solve the risk of credit card loans. To assess the data needed, we employed many different models and techniques including the imbalanced-learn and scikit-learn libraries for building and evaluating models using resampling. Then we will use two different machine learning models that help reduce bias – EasyEnsembleClassifier and BalancedRandomForestClassifier. From here, we will be able to evaluate the performance of each model and make a recommendation on which one should be used to predict credit risk.

## Results

The following are the results of the imbalanced classification reports for 6 different machine learning models

### Naive Random Oversampling

![](naive.png)
• Balanced Accuracy: 0.6517620089359456
• Precision for high-risk loans: 0.01
• Precision for low-risk loans: 1.00
• Recall high-risk: 0.63
• Recall low-risk 0.67

### SMOTE Oversampling

![](smote.png)
• Balanced Accuracy: 0.618433510198984
• Precision for high-risk loans: 0.01
• Precision for low-risk loans: 1.00
• Recall high-risk: 0.59
• Recall low-risk 0.65

### Undersampling

![](undersampling.png)
• Balanced Accuracy: 0.618433510198984
• Precision for high-risk loans: 0.01
• Precision for low-risk loans: 1.00
• Recall high-risk: 0.61
• Recall low-risk 0.45

### Combination

![](combination.png)
• Balanced Accuracy: 0.6375241226214794
• Precision for high-risk loans: 0.01
• Precision for low-risk loans: 1.00
• Recall high-risk: 0.70
• Recall low-risk 0.57

### Balanced Random Forest Classifier

![](brfc.png)
• Balanced Accuracy: 0.7877672625306695
• Precision for high-risk loans: 0.04
• Precision for low-risk loans: 1.00
• Recall high-risk: 0.67
• Recall low-risk 0.91

### Easy Ensemble AdaBoost Classifier

![](eeac.png)
• Balanced Accuracy: 0.925427358175101
• Precision for high-risk loans: 0.07
• Precision for low-risk loans: 1.00
• Recall high-risk: 0.91
• Recall low-risk 0.94

## Summary

With machine learning, the closer the number is to 1, the more accurate the model is. In this respect, the Easy Ensemble AdaBoost Classifier model was easily the most accurate for both high and low risk, with a score of 0.91 and 0.94 respectively. Out of all the machine learning models, the company should use this one to assess loan risk.
