# Credit_Risk_Analysis using Machine Learing

## Overview
The purpose of this analysis is to understand how to utilize Machine Learning statistical algorithms to make predictions based on data patterns provided. In this challenge, we focus on Supervised Learning using a free dataset from LendingClub, a P2P lending service company to evaluate and predict credit risk. This reason why this is called "Supervised Learning" is because the data includes a labeled outcome.

To complete this analysis, we use different Machine Learning techniques to train and evaluate the data with unbalanced classes. The dataset from the LendingClub has an unbalanced classification problem due to the number of good loans outweighing the amount of risky loans. In order balance out the classifications to allow for more meaningful predictions and improve the accuracy score, we needed to employ various Machine Learning algorithms to resample the data. Various libraries and algorithms were used to build and evaluate models using resampling including:
1. Imbalanced-learn
2. Scikit-learn
3. RandomOverSampler
4. SMOTE algorithms
5. ClusterCentroids algorithm
6. SMOTEENN algorithm
7. BalancedRandomForestClassifier (bias reduction model)
8. EasyEnsembleClassifier (bias reduction model

## Purpose: 
1. Explain how a machine learning algorithm is used in data analytics.
2. Create training and test groups from a given data set.
3. Implement the logistic regression, decision tree, random forest, and support vector machine algorithms.
4. Interpret the results of the logistic regression, decision tree, random forest, and support vector machine algorithms.
5. Compare the advantages and disadvantages of each supervised learning algorithm.
6. Determine which supervised learning algorithm is best used for a given data set or scenario.
7. Use ensemble and resampling techniques to improve model performance.

## Results:
The results for the six machine learning models including their respective balanced accuracy, precision, and recall scores are as follows:      

### Naive Random Oversampling
![Naive Random Oversampling](https://github.com/ashwinihegde28/Credit_Risk_Analysis/blob/main/images/NaiveIRandomOversampling.PNG)     
1. Balanced Accuracy: 0.6413263312262552
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = 0.60/0.68

### SMOTE Oversampling
![SMOTE Oversampling](https://github.com/ashwinihegde28/Credit_Risk_Analysis/blob/main/images/SMOTEOversampling.PNG)     
1. Balanced Accuracy: 0.6374415316001305
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = 0.60/0.68

### Undersampling
![Undersampling](https://github.com/ashwinihegde28/Credit_Risk_Analysis/blob/main/images/Undersampling.PNG)     
1. Balanced Accuracy: 0.5292734810302525
2. Precision:  The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = 0.70/0.57

### Combination Under-Over Sampling
![Combination Under-Over Sampling](https://github.com/ashwinihegde28/Credit_Risk_Analysis/blob/main/images/Combination(Over%20and%20Under)Sampling.PNG)     
1. Balanced Accuracy: 0.6376117496807152
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = .70/.57

### Balanced Random Forest Classifier
![]()  
1. Balanced Accuracy: 0.7877672625306695
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = .67/.91

### Easy Ensemble AdaBoost Classifier
![]()
1. Balanced Accuracy: 0.925427358175101
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk =  0.91/0.94


## Summary
- Maximum Balanced accuracy is closest to 1 is the best machine learning model. So the Easy Ensemble AdaBoost Classifier is the best model to choose with its .93 balanced accuracy. The other models were below .80 balanced accuracy. 
- The precision for all models were similar and within an appropriate range. 
- The recall score also needs to fall within 0 and 1, with numbers closer to 1 being the better model. The Easy Ensemble AdaBoost Classifier tops in the recall score, making it the final best machine learning model to choose for further credit card analysis.




