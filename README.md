# Wine-Quality-Prediction

Classification is a process of categorizing a given set of data into classes, It can be performed on both structured or unstructured data. The process starts with predicting the class of given data points. The classes are often referred to as target, label or categories.

## Problem Description : 

Our aim is to create a model that can classify dataset wine samples as 'good' or 'bad', based on the training we give to the model. This will be done with the help of certain physiochemical properties of the wine samples.

## Understanding our Dataset
We will be using a [Wine Data Set](https://archive.ics.uci.edu/ml/datasets/Wine) from the UCI Machine Learning repository which has a very good collection of datasets for experimental research purposes. The direct data link is [here](https://archive.ics.uci.edu/ml/machine-learning-databases/wine/).

The dataset is related to red variants of the Portuguese "Vinho Verde" wine.

The features represented through columns are as follows: 

- fixed acidity
- volatile acidity
- citric acid
- residual sugar
- chlorides
- free sulfur dioxide
- total sulfur dioxide
- density
- pH
- sulphates
- alcohol
- quality (score between 0 and 10) (based on sensory data)

Fisrt, some EDA is done using matplotlib and seaborn. Then different classifier models are used to predict the quality of the wine.

1. Random Forest Classifier

2. Stochastic Gradient Descent Classifier

3. Support Vector Classifier(SVC)

Then, cross validation evaluation technique is used to optimize the model performance.

1. Grid Search CV

2. Cross Validation Score
