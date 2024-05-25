# Kai-credit-risk-classification

## Background
In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

## Overview of the Analysis
It is important to know that to evaluate the performance of logistic regression model in predicting credit risk is the purpose of this analysis. Certainly, this analysis aims to determine how accurately the model can identify healthy loans('0') and high-risk loans('1'). By assessing the model's accuracy, precision, and recall, we can recommend whether this model is suitable for loan approval process. This analysis used the logistic regression model. Firstly, it loaded the data and to spilt data into training dataset and testing dataset. Then, it made an logistic regression model to predict. Finally, it made confusion matrix and the classification report for the model.

## Results
- Accuracy Score: 99% --> this means that almost predictions are correct.
- Precision Score:
- Healthy Loan (0): 100% --> this means that the model perfectly identifies all healthy loans with no false positives.
- High-Risk Loan (1): 84% --> some healthy loans are misclassified as high-risk, but the majority of predictions are correct.
- Recall Score:
- Healthy Loan (0): 99% --> almost healthy loans are correctly classified
- High-Risk Loan (1): 99% --> The model successfully identifies almost all high-risk loans, indicating very few high-risk loans are missed.

## Summary
This model demonstrates wonderful overall performance in predicting credit risk beacuse of the accuracy score of 99%.

## Recommendation
According to the evaluation results, the logistic regression model performs very well in predicting credit risk. Its high recall score (99%) for high-risk loans this is very important as it ensures that most high-risk loans are correctly identified, thus minimizing the risk of default. Despite the slightly lower precision (84%) for high-risk loans, the overall performance of the model justifies its use.

