# Module 12 Report Template

## Overview of the Analysis

The goal of the analysis is to develop and train a machine learning model that is able to correctly identify the trustworthy borrowers from the non-trustworthy ones. 
Included in this dataset are details of past lending experiences, with many options of variables that could correctly predict potential fraud. 
In the analysis, two methods are used. The first one is LogisticRegression, and the other, RandomOverSampler. 

## Results

* LogisticRegression:
  * balanced_accuracy_score = 0.9520479254722232
  * precision 0=1.00, 1=0.85
  * recall 0=0.99, 1=0.91

* RandomOverSampler:
  * balanced_accuracy_score = 0.9947308560359689
  * precision 0=0.99, 1=0.99
  * recall 0=0.99, 1=0.99


## Summary

* Between the two models, the second method of RandomOverSampler seemed to provide the most accurate predictions. This is because the model uses the credit risk data to predict the people who will default on their loans. 
* Because of this, I believe that the second model would be better suited for this scenario. 
