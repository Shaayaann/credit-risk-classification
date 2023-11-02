# credit-risk-classification
## Purpose of the Analysis:
The analysis aims to evaluate the performance of two machine learning models (Module 1 and Module 2) in predicting the likelihood of high-risk loans based on financial information. The data has been oversampled to address class imbalance.

## Financial Information and Prediction:
The data involves information related to loans, specifically focusing on distinguishing between "Healthy Loan" and "High-Risk Loan." The goal is to predict whether a loan is high-risk based on various financial features.

## Variables Overview:
Target Variable:
"Healthy Loan" (Class 0)
"High-Risk Loan" (Class 1)

## Methods Used:
Oversampling: To address class imbalance and enhance the model's ability to predict the minority class.

## Results:
Machine Learning Model 1:
Accuracy: 0.99
Precision (High-Risk Loan): 0.87
Recall (High-Risk Loan): 0.89
F1-Score (High-Risk Loan): 0.88

Machine Learning Model 2 (Oversampling):
Accuracy: 1.00
Precision (High-Risk Loan): 0.87
Recall (High-Risk Loan): 1.00
F1-Score (High-Risk Loan): 0.93

## Summary:
Both models show high accuracy, with Model 2 demonstrating perfect accuracy.
Model 2 has a higher recall for the high-risk class, indicating better performance in capturing true high-risk instances.
The choice of the preferred model depends on the problem context. If correctly identifying high-risk loans is crucial, Model 2 may be preferred due to its higher recall.

## Recommendation:
Considering the emphasis on identifying high-risk loans, Model 2 is recommended due to its superior recall in predicting the "High-Risk Loan" class. However, the final decision should consider the specific business objectives and the consequences of false positives and false negatives in the context of the financial domain.
