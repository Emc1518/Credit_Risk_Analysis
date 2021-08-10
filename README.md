# Credit_Risk_Analysis

## Overview 

The purpose of this analysis is to build a machine learning model that will use known data to predict whether a loan is high rish or low risk in new data. 

## Results:

#### Machine Learning Models

1. Naive Random Oversampling

![naive random](https://user-images.githubusercontent.com/81889167/128803626-a2afa338-3eb8-4f11-97d6-db5f94cb3a57.png)


- Accuracy Score: 67.4%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 72%
- Recall Low Risk: 63%

2. SMOTE Oversampling

![SMOTE](https://user-images.githubusercontent.com/81889167/128803641-e5bc6713-2bfc-4e5a-ac81-8cfc578bdbea.png)

- Accuracy Score: 66.2%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 66%
- Recall Low Risk: 66%

3. Cluster Centroid Undersampling

![cluster centroid](https://user-images.githubusercontent.com/81889167/128803663-ed9cb0fe-fc60-401b-b0f6-6d826f755494.png)

- Accuracy Score: 51.5%
- Precision High Risk: 0%
- Precision Low Risk: 100%
- Recall High Risk: 59%
- Recall Low Risk: 44%

4. SMOTEENN Sampling

![smoteenn](https://user-images.githubusercontent.com/81889167/128803679-f4dfd83c-410b-4f8b-8827-29b80270fff8.png)

- Accuracy Score: 61%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 76%
- Recall Low Risk: 60%

5. Balanced Random Forest Classifying

![random forest](https://user-images.githubusercontent.com/81889167/128803699-45dd9c9a-3b72-4b49-9da1-098961992c5d.png)

- Accuracy Score: 64.8%
- Precision High Risk: 56%
- Precision Low Risk: 100%
- Recall High Risk: 30%
- Recall Low Risk: 100%

6. Easy Ensemble Classifying

![easy ensemble](https://user-images.githubusercontent.com/81889167/128803714-ce80bd6a-7dfe-483b-83df-9195d670998b.png)

- Accuracy Score: 92.3%
- Precision High Risk: 6%
- Precision Low Risk: 100%
- Recall High Risk: 91%
- Recall Low Risk: 94%


## Summary: 

The results produced by every model in this analysis show that they are not precise enough in determining high credit risk. The exception to this is the Easy Ensemble Classifying model that is able to detect 92% of high risk credit but the model is only precise in 6% of those detections. This would negatively affect individuals with good credit trying to take out loans. It would be a mistake to recommend any of these models as they would cause the bank to lose revenue on loans that would otherwise be profitable.
