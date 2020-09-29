# Kaggle Project- Titanic

The most famous project on Kaggle. Everyone starts their data science journey with this project and I did the same. Did this project as the final project for my Machine learning Project. Worked on this project in a team of two.

## Overview:
[Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic) 
This is the legendary Titanic ML competition – the best, first challenge for you to dive into ML competitions and familiarize yourself with how the Kaggle platform works. The competition is simple: use machine learning to create a model that predicts which passengers survived the Titanic shipwreck.

The data has been split into two groups:

### training set (train.csv)
### test set (test.csv)

Used the training set to build your machine learning models. For the training set the outcome is provided known as ground truth for each passenger. The data provide quite a space to perform feature engineering to create our own new feature from the existing feature. The model used the passenger feature to generate the ground truth.

To test how well the model performs, the test set is put into use. The site does not provide the ground truth for each passenger. The prediction of model will be from our model. The model will predict from each passenger feature that whether or not they survived the sinking of Titanic. 

## Variable Notes

A proxy for socio-economic status (SES)
1st = Upper
2nd = Middle
3rd = Lower

age: 
Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

sibsp: The dataset defines family relations in this way...
Sibling = brother, sister, stepbrother, stepsister
Spouse = husband, wife (mistresses and fiancés were ignored)

parch: The dataset defines family relations in this way...
Parent = mother, father
Child = daughter, son, stepdaughter, stepson
Some children travelled only with a nanny, therefore parch=0 for them.

## Final Code: Copy_of_Final_Report.ipynb
The code includes following parts:</br>
Data Exploration: info() , describe(), distplot(), isnull(),sum(), drop(),fillna()
Encoding Categorial Variable: replace(),loc(),mean(),var()
Testing Set: removing missing values, Dropping Columns with significant missing data, Encoding Categorial Variable.
Functions Creation: 
-feature_Selection(df,corr,var), 
-calc_train_error(X_train_data, Y_train_data, model)
-calc_validation_error(X_test_data, Y_test_data, model)
-calc_metrics(X_train_data, Y_train_data,X_test_data,Y_test_data, model)
Taking Logarithmic of the Data
Algorithm Applied: Linear Regression, Feature Scalling (MinMaxScaler(), WithPCA, KNN Regression, KNN_withfeaturescaling, KNN_withPCA,RidgeRegression, RidgeRegression_featureScaling, RidgeRegression_WithPCA, LassorRegression(FeatureScaling, WIThPCA), Desicion Tree, Random_Forest, AdaBoost, Gradient_Boost, Prediction, SupportVectorMachine, Tensorflow)


