# Cryptocurrencies

## Overview

Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies.

The purpose of this project is to use unsupervised machine learning to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system. 

## Results

### Elbow Curve Clustering of Cryptocurrencies

There are a total of 532 tradable cryptocurrencies after the cleaning phase of this analysis.

The first task was producing a elbow curve using the K-Means method.

![elbowcurve.png](https://github.com/RyanJL18/Cryptocurrencies/blob/main/Resources/elbowcurve.png)

The best k value appears to be 4, meaning we should use an output of 4 clusters to categorize the cryptocurrencies.

### 3D Scatter plot Clusters

![3d_scatter_plot.png](https://github.com/RyanJL18/Cryptocurrencies/blob/main/Resources/3d_scatter_pca.png)

## Summary

Using the values above we were able to group the 532 cryptocurriencies into 4 categories for further analysis.
