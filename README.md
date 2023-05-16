# credit-risk-classification

## Overview of the Analysis
The objective of this challenge was to leverage various machine learning techniques to train and evaluate the performance of Logistic Regression Models based on loan risk labels ('0' for healthy loans and '1' for high-risk loans) to determine the creditworthiness of potential borrowers. The dataset used to train the models came from historical lending activity of a peer-to-peer lending services company provided by the instructors.

## Results
* Machine Learning Model 1:
  *  Model 1, trained on the original data, was reasonably good in terms of overall accuracy as it predicted approximately 94.4% of the labels correctly. When looked at in more granular detail the model was great at predicting healthy loans as it posted precision and recall scores of 1.00 in that category. However, it left some room for improvement when dealing with high-risk loans, both in terms of correctly predicting the loans and identifying them within the dataset. Below is a summary of the model's performance on high-risk loans in more detail:
    *  Precision (High-Risk): 0.87
    *  Recall (High-Risk): 0.89

* Machine Learning Model 2:
  *  Model 2, trained on the resampled data, was also great in terms of overall accuracy as it predicted approximately 99.6% of the labels correctly. When looked at in more granular detail the model still posted precision and recall scores of 1.00 in the healthy loan category. It also improved in terms of correctly identifying and predicting the high-risk loans as detailed below:
    *  Precision (High-Risk): 0.87
    *  Recall (High-Risk): 1.00

## Summary
Based on the analysis, it seems that Machine Learning Model 2 matches Machine Learning Model 1 when it comes to identifying and predicting healthy loans, but it outperforms when it comes to high-risk loans. As a result, it has an overall higher level of accuracy than Machine Learning Model 1. And given that Machine Learning Model 2 correctly identified all high-risk loans while maintaining relatively good performance in terms of precision I feel comfortable recommending using it when trying to determine the creditworthiness of potential borrowers going forward.
