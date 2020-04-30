# Wine-Quality-Prediction

Classification is a process of categorizing a given set of data into classes, It can be performed on both structured or unstructured data. The process involves predicting the class of given data points. The classes are often referred to as target, label or categories.

## Problem Description : 

Our aim is to create a model that can classify dataset wine samples as 'good' or 'bad', based on the training we give to the model. This will be done with the help of certain physiochemical properties of the wine samples.


## Understanding our Dataset :
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

### Dataset Source :

**Original Owners**

Forina, M. et al, PARVUS -
An Extendible Package for Data Exploration, Classification and Correlation.
Institute of Pharmaceutical and Food Analysis and Technologies, Via Brigata Salerno,
16147 Genoa, Italy.

**Donor**

Stefan Aeberhard, email: stefan '@' coral.cs.jcu.edu.au

## Libraries Required :
- Sklearn 
- Matplotlib
- pandas
- numpy
- Seaborn
- Collections

## Steps :
1. Importing Libraries
2. Exploring the Dataset
3. Exploratory Data Analysis
> * Univariate Analysis
4. Data Preprocessing
5. Model Building
> * Random Forest Classifier
> * Stochastic Gradient Descent Classifier
> * Support Vector Classifier(SVC)
6. Validation
> * Grid Search CV
> * Cross Validation Score
7. Conclusion

## License :

**Citation**

Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science.

@misc{Dua:2019 ,
author = "Dua, Dheeru and Graff, Casey",<br>
year = "2017",<br>
title = "{UCI} Machine Learning Repository",<br>
url = "http://archive.ics.uci.edu/ml",<br>
institution = "University of California, Irvine, School of Information and Computer Sciences" }
