# Module 20 Credit Risk Classification

## Overview of the Analysis

The purpose of this analysis was to determine the reliability of the prediction model used to assess credit risk of borrowers. A peer-to-peer lending services company has provided a dataset of historical lending activity of their clients.
The main feature used in the prediction model was 'loan_status'. This was used in the model to predict the creditworthiness of each borrower.
First, the data is split into test and training sets. Then, a Logistic Regression model is created that helps to predict the binary outcomes of 'Healthy loan' and 'High- risk loan'.

## Results

* The logistic regression model shows high accuracy at 0.99. 
* The model has high precision (1.00) & recall (0.99) score for healthy loan prediction, indicating less probability of showing false positive & negative results.
* However, the performance of the model slightly declines for high-risk loan prediction. With lower precision (0.86) and recall (0.91) score compared to health loan predication, the model has a possibility of predicting false negative or positives for high-risk predictions.


## Summary

In conclusion, the model performs well in predicting healthy loan status. The prediction for high-risk loan could generate false positive or negative. However, the probability of this occurrance will be rare. The model can be used by the company to conduct initial credit checks on the borrowers. Other supervised learning methods such as Decision Trees can be used to further strengthen the predictions.
