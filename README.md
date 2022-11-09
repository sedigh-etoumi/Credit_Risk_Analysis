# Credit_Risk_Analysis

# Overview:

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. we are going to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

Results:
All average scores:

   Naive Random Oversampling
   balanced accuracy score: 0.6627955709509211
   precision: 0.99
recall: 0.64
SMOTE Oversampling
balanced accuracy score: 0.6583892135705619
precision: 0.99
recall: 0.68
Undersampling
balanced accuracy score: 0.6583892135705619
precision: 0.99
recall: 0.56
SMOTEENN
balanced accuracy score: 0.5912018148727876
precision: 0.99
recall: 0.40
Balanced Random Forest Classifier
balanced accuracy score: 0.9959895379250218
precision: 1.00
recall: 1.00
Easy Ensemble AdaBoost Classifier
balanced accuracy score: 0.9919790758500436
precision: 0.99
recall: 0.99
