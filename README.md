# Cryptocurrencies_ppd

# Overview
Using available cryptocurrency data traded on public markets, we used unsupervised learning to “separate the wheat from the chaff” to determine if there are some investable opportunities. 

## Data preprocessing
Like any unknown dataset, performing initial preprocessing to clean up and filter out superfluous content (non-trading, trading inactivity, etc.), create dummies variables for non-numeric values and standardize data to ensure scale uniformity. 

## Reducing Data Dimensions using PCA
Following preprocessing, data was reduced to principal component analysis (PCA) to transform several correlated variables into uncorrelated variables to emphasize variation.  

## Clustering Cryptocurrencies using K-means
The next step in the analysis was taking the PCA data set, determining the K clusters through use of an elbow curve in order to prepare the data for visualization. 

## Visualizing Results
Visualizations were prepared to see class grouping relationships as well as cryptocurrency supply-demand relationships. 
