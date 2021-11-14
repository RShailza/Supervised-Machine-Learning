# Supervised-Machine-Learning
Predicting Credit Risk
**************************************************************

## Considering the models and initial prediction

I think, It is hard to say if the LogisticRegression model will perform better than the RandomForestClassifier or vice versa. Because, we are looking for binary outcome that is If the loan from LendingClub will become high risk or not. I think LogisticRegression will be faster due to simplicity of the model but RandomForest might be more precise.

## After fitting the model

After fitting the data with LogisticRegression training data have score of 0.65 and testing data score is 0.51.
whereas LogisticRegression have training score of 1.0 and testing score of 0.64.
By looking at the scores we can say RandomForest model performed better.

## Initial prediction before scaling

I think after scaling RandomForest might perform better when data is scaled because its is a stronger classifier than logistic regression.


## After scaling the model

After scaling the data with LogisticRegression training data have score of 0.71 and testing data score is 0.75.
whereas LogisticRegression have training score of 1.0 and testing score of 0.64.
From scaling outcomes, LogisticRegression performed better than RandomForest. RandomForest model outcome stayed the same with or without scaling. Does this mean RandomForest may not need scaling sometimes?





