# Credit-Card-Fraud-Detection-System

Credit card fraud detection is the process of identifying purchase attempts that are fraudulent and rejecting them rather than processing the order. We investigated the data, checking for data unbalancing, visualizing the features, and understanding the relationship between different features.


# Need of This System:-

For any bank or financial organization, credit card fraud detection is of utmost importance. We have to spot potential fraud so that consumers can not bill for goods that they haven’t purchased. The aim is to create a classifier that indicates whether a requested transaction is a fraud. We solve the problem of detecting credit card fraud transactions using machine numpy, scikit learn, and few other python libraries. The model is simple and fast enough to detect the anomaly and classify it as a fraudulent transaction as quickly as possible.


# Tools and Libraries:-

We use the following libraries and frameworks in credit card fraud detection project.
    1)	Python – 3.x
    2)	Numpy – 1.19.2
    3)	Scikit-learn – 0.24.1
    4)	Matplotlib – 3.3.4
    5)	Imblearn – 0.8.0
    6)	Collections, Itertools


# Python Modules:-

a)	GridSpec - Specifies the geometry of the grid that a subplot will be placed. The number of rows and number of columns of the grid need to be set. Optionally, the subplot layout parameters 

b)	Random forest classifier - Random forest algorithms have three main hyperparameters, which need to be set before training. These include node size, the number of trees, and the number of features sampled. From there, the random forest classifier can be used to solve for regression or classification problems.

c)	train_test_split() - used to solve classification problems the same way you do for regression analysis. In machine learning, classification problems involve training a model to apply labels to, or classify, the input values and sort your dataset into categories.


# Dataset:-

We will be using the Credit Card Fraud Detection Dataset from Kaggle. The dataset utilized covers credit card transactions done by European cardholders in September 2013. There are a total of 2,84,808 transactions. The dataset consists of 31 parameters i.e time, v1,v2,….v28 , amount, class.. ‘Time’ and ‘Amount’ are the only aspects we are concerned with.This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions. It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

