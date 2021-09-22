# Credit Risk Analysis
## Overview of the Analysis
Credit risk is an inherently unbalanced classification problem due to good loans easily outnumbering risky loans. For this analysis
different techniques were used to train and evaluate models with unbalanced classes. This was done through both under and oversampling the
data provided from LendingClub. Finally, two machine learning models (Balanced Random Forest Classifier and Easy Ensemble Classifier) were
used to predict credit risk.
## Results
Below are the classification reports associated with the under/oversampled methods as well as with the two machine learning models. Within the classification reports are the numbers for the precision and the avereage accuracy of each of the models.

**Naive Random Oversampling**
![Naive Random Oversampling](https://github.com/swlim314/Credit_Risk_Analysis_Week_17/blob/c35a85c00c3f2b940a5096a17578079974caabd0/Resources/Naive%20Random%20Oversampling.png)

**Smote Oversampling**
![Smote Oversampling](https://github.com/swlim314/Credit_Risk_Analysis_Week_17/blob/c35a85c00c3f2b940a5096a17578079974caabd0/Resources/SMOTE%20Oversampling.png)

**Cluster Centroids Undersampling**
![Cluster Centroids Undersampling](https://github.com/swlim314/Credit_Risk_Analysis_Week_17/blob/c35a85c00c3f2b940a5096a17578079974caabd0/Resources/ClusterCentroids%20Undersampling.png)

**SMOTEENN Over-Under Sampling**
![SMOTEENN Over-Under Sampling](https://github.com/swlim314/Credit_Risk_Analysis_Week_17/blob/c35a85c00c3f2b940a5096a17578079974caabd0/Resources/SMOTEENN%20Over-Under%20Sampling.png)

**Balanced Random Forest Classifier**
![Balanced Random Forest Classifier](https://github.com/swlim314/Credit_Risk_Analysis_Week_17/blob/c35a85c00c3f2b940a5096a17578079974caabd0/Resources/Balanced%20Random%20Forest%20Classifier.png)

**Easy Ensemble AdaBoostClassifier**
![Easy Ensemble AdaBoostClassifier](https://github.com/swlim314/Credit_Risk_Analysis_Week_17/blob/c35a85c00c3f2b940a5096a17578079974caabd0/Resources/Easy%20Ensemble%20AdaBoostClassifier.png)

## Summary
Looking at the machine learning models, with F1 representing the average accuracy of the tests calculated from the precision and accuracy statistics, it appears that the ClusterCentroids undersampling method provided the worst average accuracy at 56% while
Easy Ensemble AdaBoost Classifier provided the best average accuracy at 97%. Based on the average score, I would recommend using
Easy Ensemble AdaBoost Classifier for the loan prediction risk.
