# Analyzing Credit Risk

A machine learning credit risk analysis using resampling models and classifiers.

## Overview
This project will use several methods of machine learning to assess credit risk. The following models will be used:
- RandomOverSampler
- SMOTE
- ClusterCentroids
- SMOTEENN
- BalancedRandomForestClassifier
- EasyEnsembleClassifier

For each model, we'll look at the Balanced Accuracy Score, as well as the precision and recall for risk performance (high and low)


## Results
#### RandomOverSampler
![ROS](https://github.com/tech-neault/Credit_Risk_Analysis/blob/main/Images/randomoversampling.png)
Balanced Accuracy Score: 0.648767580808264

<i> High Risk Performance</i>

-precision: 0.01 
-recall: 0.61  

<i>Low Risk Performance:</i>

-precision: 1.00 
-recall: 0.69 

#### SMOTE
![SMT](https://github.com/tech-neault/Credit_Risk_Analysis/blob/main/Images/SMOTEoversampling.png)
Balanced Accuracy Score: 0.6159507435206336

<i>High Risk Performance:</i>

-precision: 0.01 
-recall: 0.59 

<i>Low Risk Performance:</i>

-precision: 1.00 
-recall: 0.65 

#### ClusterCentroids
![CC](https://github.com/tech-neault/Credit_Risk_Analysis/blob/main/Images/ClusterCentroids.png)
Balanced Accuracy Score: 0.6159507435206336

<i>High Risk Performance:</i>

-precision: 0.01 
-recall: 0.60 

<i>Low Risk Performance:</i>

-precision: 1.00
-recall: 0.46 

#### SMOTEENN
![SMTNN](https://github.com/tech-neault/Credit_Risk_Analysis/blob/main/Images/SMOTEENNsampling.png)
Balanced Accuracy Score: 0.5270606459826519

<i>High Risk Performance:</i>

-precision: 0.01 
-recall: 0.70 

<i>Low Risk Performance:</i>

-precision: 1.00 
-recall: 0.58 

#### BalancedRandomForestClassifier
![BRFC](https://github.com/tech-neault/Credit_Risk_Analysis/blob/main/Images/BalancedRandomForestClassification.png)
Balanced Accuracy Score: 0.7877672625306695

<i>High Risk Performance:</i>

-precision: 0.04 
-recall: 0.67 

<i>Low Risk Performance:</i>

-precision: 1.00 
-recall: 0.91 

#### EasyEnsembleClassifier
![EEC](https://github.com/tech-neault/Credit_Risk_Analysis/blob/main/Images/EasyEnsembleClassifier.png)
Balanced Accuracy Score: 0.925427358175101

<i>High Risk Performance:</i>

-precision: 0.07 
-recall: 0.91 

<i>Low Risk Performance:</i>

-precision: 1.00
-recall: 0.94


## Summary 



