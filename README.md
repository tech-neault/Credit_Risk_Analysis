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

<i> High Risk Performance:</i>

- precision: 0.01 (very low)
- recall: 0.61  (good)

<i>Low Risk Performance:</i>

- precision: 1.00 (perfect)
- recall: 0.69 (good)

#### SMOTE
![SMT](https://github.com/tech-neault/Credit_Risk_Analysis/blob/main/Images/SMOTEoversampling.png)
Balanced Accuracy Score: 0.6159507435206336

<i>High Risk Performance:</i>

- precision: 0.01 (very low)
- recall: 0.59 (good)

<i>Low Risk Performance:</i>

- precision: 1.00 (perfect)
- recall: 0.65 (good)

#### ClusterCentroids
![CC](https://github.com/tech-neault/Credit_Risk_Analysis/blob/main/Images/ClusterCentroids.png)
Balanced Accuracy Score: 0.6159507435206336

<i>High Risk Performance:</i>

- precision: 0.01 (very low)
- recall: 0.60 (good)

<i>Low Risk Performance:</i>

- precision: 1.00 (perfect)
- recall: 0.46 (good)

#### SMOTEENN
![SMTNN](https://github.com/tech-neault/Credit_Risk_Analysis/blob/main/Images/SMOTEENNsampling.png)
Balanced Accuracy Score: 0.5270606459826519

<i>High Risk Performance:</i>

- precision: 0.01 (very low)
- recall: 0.70 (great)

<i>Low Risk Performance:</i>

- precision: 1.00 (perfect)
- recall: 0.58 

#### BalancedRandomForestClassifier
![BRFC](https://github.com/tech-neault/Credit_Risk_Analysis/blob/main/Images/BalancedRandomForestClassification.png)
Balanced Accuracy Score: 0.7877672625306695

<i>High Risk Performance:</i>

- precision: 0.04 (low)
- recall: 0.67 (good)

<i>Low Risk Performance:</i>

- precision: 1.00 (perfect)
- recall: 0.91 (excellent)

#### EasyEnsembleClassifier
![EEC](https://github.com/tech-neault/Credit_Risk_Analysis/blob/main/Images/EasyEnsembleClassifier.png)
Balanced Accuracy Score: 0.925427358175101

<i>High Risk Performance:</i>

- precision: 0.07 (low)
- recall: 0.91 (excellent)

<i>Low Risk Performance:</i>

- precision: 1.00 (perfect)
- recall: 0.94 (excellent)


## Summary 



