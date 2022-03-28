# Credit_Risk_Analysis
---

Overview of the loan prediction risk analysis: I used machine learning in that was covered in this module to create a way to screen loan candidates with greater accuracy so that they don't default on their loans.

Results:

## Naive Random Sampling

![image_name](https://github.com/pady7/Credit_Risk_Analysis/blob/main/CreditRisk/NaiveRandom.png)

## SMOTE Oversampling

![image_name](https://github.com/pady7/Credit_Risk_Analysis/blob/main/CreditRisk/Smote.png)

## Cluster Centroid Undersampling

![image_name](https://github.com/pady7/Credit_Risk_Analysis/blob/main/CreditRisk/Cluster.png)

## SMOTEENN

![image_name](https://github.com/pady7/Credit_Risk_Analysis/blob/main/CreditRisk/Smoteen.png)

## Balanced Random Forest Classifier

![image_name](https://github.com/pady7/Credit_Risk_Analysis/blob/main/CreditRisk/BalancedRandom.png)

## Easy Ensemble AdaBoost Classifier

![image_name](https://github.com/pady7/Credit_Risk_Analysis/blob/main/CreditRisk/EasyEnsemble.png)

## Summary:
___

Sensitivity is valued more than precision when it comes to banks issuing loans because it decreases the chance a customer will default on a loan. Each one of the methods had really low precision for high risk applicants and high precision for low risk applicants. Easy Ensemble AdaBoost Classifier had the highest precision when it came to high risk customers. Moving on to the next qualifier would be to look at the sensitivity. Easy Ensemble AdaBoost Classifier scored the highest again in both high and low risk categories followed by Balanced Random Forest Classifier. The final part to look at is the balanced accuracy score one which model to use. Easy Ensemble AdaBoost Classifier scored the highest again in this category so this is the one I would go with since it is the more accurate, precice and most sensitive.

