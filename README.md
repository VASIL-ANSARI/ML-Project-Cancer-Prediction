# ML-Project-Cancer-Prediction
My Kaggle Project(Based on Medical Treatment)
Kaggle Problem link: 
Some libraries/Subpackages used are: https://www.kaggle.com/c/msk-redefining-cancer-treatment
1.nltk
2.sklearn.calibration
3.sklearn.naive_bayes
4.mlxtend.classifier
5.sklearn.linear_model
6.seaborn
7.sklearn.metrics 

Algorithm applied:
1.Naive Bayes
2.Random Forest(using oneHotEncoding)
3.Random Forest(using ResponseEncoding)
4.Logistic Regression
4.Linear Support Vector Machine(Linear SVM)
5.K Nearest Neighbours
6.Stacking Model
7.Maximum Voting classifier

Evaluation is done on basis of multi log-loss
1.Log-loss for Naive Bayes Model is: 1.2174351082980228
2.Log-loss for Logistic Regression is: 1.0139465030649317
3.Log-loss for KNN is : 0.9686092822627863
4.Log-loss for LinearSVM is: 1.0518829636631724
5.Log-loss for Random Forest Classifier is : 1.1440820641479814(using one hot encoding) and 1.220569827205813(using Response Encoding)
6.Log-loss for Stacking Model is:[training_set:0.497983218669304,test_set:1.1751619600947567,cross_validation_set:1.09245098514981767
7.Log-loss for Maximum Voting Classifier is:[training_set: 0.8677287779975493,test_set:1.2148355813599823,cross_validation_set:1.142669504]

As per the Evaluation Logistic Regression is the best Model to be fitted in this problem .
