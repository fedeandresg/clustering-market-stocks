![Logo](https://assets.bwbx.io/images/users/iqjWHBFdfxIU/iO1E2bPiwKKY/v1/-1x-1.jpg)

# DATA SCIENCE - Clustering market stocks using K-Means
# Machine Learning

In this project I will be extracting live Stock Market data from `Yahoo Finance`. 

I will analize their performance since 2020 (beggining of Covid-19).

The purpose is to find similarities among various companies using their stock stock market prices/attributes and then group them into different clusters using the K-means algorithm.

This is an unsuppervised ML problem so I will use an **`Unsuppervised Machine Learning`** technique with the help of the K-means algorithm.

## Context

The need to research the equity market as of 2020, when the pandemic begins, is presented.

It is intended to group the stocks by common characteristics so that the research department can define a study for the construction of investment portfolios.

## Dataset

We will use yahoo finance as a data source.

[Link](https://finance.yahoo.com/)

## Data analysis

An analysis of the attributes is carried out for each of the stocks. 

In particular, 2 stocks were selected to evaluate their historical evolution, difference between opening and closing prices and volume.

[Notebook](https://github.com/fedeandresg/clustering-market-stocks/blob/main/Stock_Market_Clustering.ipynb)

## Clustering model - Machine Learning

For the project, the K-means algorithm was used to group the stocks. It was decided to use 6 clusters. 

Values were normalized to improve the consistency of the analysis and the dimensionality reduction technique (PCA) was applied. 

Also a pipeline was defined for the process and finally the structure of the clusters was plotted.

[Notebook](https://github.com/fedeandresg/clustering-market-stocks/blob/main/Stock_Market_Clustering.ipynb)

