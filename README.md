# credit-risk-classification
Module 20 Challenge


This challenge required us to use various techniques to train and evaluate a model based on loan risk that can identify the creditworthiness of borrowers.

To prepare the data, I loaded the dataset and split it into variables with target being the variable we are attempting to predict and then split the dating into training and testing.

Trained a logistic regression model on the training data to predict the loan status using LogisticRegression from Scikit-Learn with a random_state parameter so that my results can be reproduced.

Finally, generated prediction sand evaluated the model using the confusion matrix and a classification to display our accuracy, precision, and recall.

This is the final results: 

[[18663   102]
 [   56   563]]

                
                
                precision    recall  f1-score   support

  Healthy Loan       1.00      0.99      1.00     18765
High-Risk Loan       0.85      0.91      0.88       619

      accuracy                           0.99     19384
     macro avg       0.92      0.95      0.94     19384
  weighted avg       0.99      0.99      0.99     19384

Based on these results, I believe that it is a good model that can be helpful in evaluating creditworthiness.
