# Stroke-Prediction-Project

**ML Project**

Predicting stroke risk before it occurs can revolutionize patient care. Early identification of high-risk individuals allows for timely interventions that could prevent strokes or reduce their impact.

**Objective**: 

Understand the primary reasins that cause stroke to people and see if we can successfully detect stroke on some features using ML techniques.

Features taken into consideration for predicting Stroke or not (Binary classifier)

Independent variables:

id, gender, age, past history of hypertension, heart disease, ever married, work type, residence type, avg glucose level, BMI, smoking status

Dependent variable (DV): stroke(yes then 1 /No then 0)

data shape - (5110, 12)

SMOTE used because of imbalanced dataset- for DV (249 (stroke yes) out of 5110 ) 

## Logistic regression

Accuracy: 0.7128 (from confusion matrix), 
ROC AUC score: 0.84

## KNN 

Accuracy: 0.8706, 
ROC AUC score: 0.61

## Decision Tree

Accuracy: 0.8594, 
ROC AUC score: 0.57

## Random Forest Classifier

Accuracy: 0.9195, 
ROC AUC Score: 0.77

## XG Boost Model

Accuracy: 0.9256, 
ROC AUC Score: 0.78

## SVM Model

Accuracy: 0.8044, 
ROC AUC Score: 0.76

## Ada Boost 

Accuracy: 0.8146, 
ROC AUC Score: 0.78

Here the best model is XG Boost. 
**Feature importance found out**: Age > Working status > Work type
