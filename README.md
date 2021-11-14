# Applied-Machine-Learning
## Applied Machine Learning in Python
   \- _by the University of Michigan (Coursera)_
   
   <br/>
   
   This was a 4 week course which I started in May 2021. [Here's](https://coursera.org/share/0312d1e7996a5d5ba3bd7e05473953a9) the link to the certificate.
   
   ### Assignment+1:
   - created a classifier to predict whether a tumor is malignant or benign for breast cancer Wisconsin database
   - used k-Nearest Neighbours classifier and trained it on the dataframe obtained from above database
   - made predictions on unknown set with an accuracy of 91.6%
   ### Assignment+2:
   - curated a function that fits a polynomial Linear Regression model on the training data X_train for degrees 1, 3, 6 and 9
   - for each model found 100 predicted values over x=0 to 10 and plotted them
   - wrote a function that fits a polynomial linear regression model on the training data X_train for degrees 0 to 9 and computes R<sup>2</sup> regression score for training and test data
   - based on above R<sup>2</sup> scores, determined which degree level corresponds to a model that is underfitting, overfitting or provides a good generalization
   - trained two models a non regularized linear regression and a regularized lnear regression both on polynomial features of degree 12, computed their R<sup>2</sup> scores (-4.312, 0.8406)
   - using the UCI Mushroom dataset, trained a model to predict whether or not a mushroom is poisonous
   - trained a decision tree classifier and obtained the 5 most important features
   - explored the effect of gamma on SVM classifier accuracy by using the validation curve function to find the training and test scored for 6 values of gamma from 0.0001 to 10
   ### Assignment+3:
   - trained several models and evaluated how effectively they predict instances of fraud using data based on fraud_data.csv from kaggle
   - trained a dummy classifier on this dataset with most_frequent strategy and obtained accuracy and recall scores of 98.5 and 0.0
   - trained SVC classifier and obtained accuracy, recall and precision of 0.99, 0.35 and 0.93
   - using SVC classifier with paramaters {'C': 1e9, 'gamma': 1e-07} generated a confusion matrix with threshold -220 on the decision function
   - plotted precision-recall and ROC curves for logistic regression classifier
   - performed a grid search over the parameters 'penalty':['11', '12'], 'C': [0.01, 0.1, 10, 100] for a logistic regression classifier using recall for scoring
   ### Assignment+4:
   - predicted whether a given blight ticket will be paid on time
   - performed feature normalization and scaling and feature extraction to remove features which contributed to data leakage
   - formulated a model with a AUROC score of more than 0.75
   
   <br/>
   
   Overall achieved a grade of 92.58 %
