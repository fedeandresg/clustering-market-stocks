![Logo](https://images.shiksha.com/mediadata/images/articles/1652097279phpcHa5PV.jpeg)

# DATA SCIENCE - Clustering market stocks using K-Means
# Machine Learning

In this project I will be extracting live Stock Market data from `Yahoo Finance`. 

I will analize their performance since 2020 (beggining of Covid-19).

The purpose is to find similarities among various companies using their stock stock market prices and then group them into different clusters using the K-means algorithm.

This is an unsuppervised machine learning problem and I will use an **`Unsuppervised Machine Learning`** technique with the help of the K-means algorithm.

## Context

There is a need to identify the veracity or falsity of the statistical data in the bank notes report.

It is recommended that models be defined to verify whether the new data to be entered can be classified as genuine (1) or false (0).

## Dataset

The [dataset](https://github.com/fedeandresg/Detecting-fraudulent-bank-notes-using-ML/blob/main/BankNote_Authentication.csv) has information on statistical measures assigned to each bank note. It has 1372  rows (bank notes) and 5 columns (atribites-statistical measures).

Source: https://www.kaggle.com/ritesaluja/bank-note-authentication-uci-data

UCI: http://archive.ics.uci.edu/ml/datasets/banknote+authentication

## Data preprocessing

No **`Data preprocessing`** tasks were performed, because the data are scarce and the target to be predicted `Class` is balanced.
Univariate and bivariate analyses were carried out to determine the frequency distributions of each attribute and the correlation between them.

They can be viewed at the following link:

[notebook](https://github.com/fedeandresg/Detecting-fraudulent-bank-notes-using-ML/blob/main/bank_notes.ipynb)

## Classification models - Machine Learning

The following classification models were used for the project:

- Logistic regression
- Support Vector Machine
- Support Vector Machine (rbf kernel)
- Randon Forest Classifier
- Kneighbors Classifier
- Multilayer Perceptron (neural network)

All models presented great results in terms of accuracy. The confusion matrices confirm the fact that they all predict the label 'Class' very well.

They can be viewed at the following link:

[notebook](https://github.com/fedeandresg/Detecting-fraudulent-bank-notes-using-ML/blob/main/bank_notes.ipynb)

