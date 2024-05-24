# Module 12 Report Template

## Overview of the Analysis



In this Challenge, various techniques to train and evaluate a model based on loan risk were used. 
Dataset of historical lending activity from a peer-to-peer lending services company was used to build a model that can identify the creditworthiness of borrowers.
There was a total of 77536 split into training and testing sets.
The data included:
loan size
interest rate
borrower's income
debt to income ratio
number of accounts
derogatory marks against the borrower
the total debt


The data was split into training and testing datasets
Logistic Regression model was used
Model perfeormance was evaluated by generating confusion matrix

## Results



* Machine Learning Model 1:
Precision: 94% (an average--in predicting low-risk loans, the model was 100% precise, though the model was only 87% precise in predicting high-risk loans)
Accuracy: 94%
Recall: 99% (an average--the model had 100% recall in predicting low-risk loans, but 89% recall in predicting high-risk loans)


## Summary

Class 0 has perfect scores across all metrics, indicating that the model performs flawlessly for this class.
Class 1 has slightly lower precision and recall, but they are still high, indicating good performance for this class as well.
The overall accuracy of 99% shows that the model is highly accurate.
The macro average scores provide a balanced view of the model’s performance across both classes, while the weighted average scores take into account the class distribution in the dataset.
This report suggests that the model performs exceptionally well, especially given the high imbalance in the class distribution (much more class 0 than class 1).
