# Cryptocurrencies

## Overview

The purpose of this project is to analyze, and create, a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment. This investment comes from Accountability Accounting, a prominent investment bank, who is interested in offering a new cryptocurrency investment portfolio for its customers. 

## Results

Having finished the preprocessing and data wrangling phase, there are a total of 532 tradeable cryptocurrencies. The output of the analysis is currently unknown, so unsupervised machine learning is applied to identify clusters of the cryptocurrencies.

![elbow_curve](https://user-images.githubusercontent.com/111096246/214393822-9ace1ae5-d3f8-47df-aa81-8ee229aa7ce0.PNG)

An elbow curve was created utilizing the K-Means method, ranging from k values of 1 to 10. As can be noted in the figure above, the best k value would be 4. Therefore, an output of 4 clusters will be used to categorize the cryptocurrencies.

A 3D scatter plot was generated using the PCA algorithm in order to minimze the the cryptocurrency dimension to three principal components.

![3D_Scatter_Plot](https://user-images.githubusercontent.com/111096246/214393967-94f75b97-4446-4f2e-9154-3bb420a06bdf.PNG)

A table was created with the headers: #, CoinName, Algorithm, ProofType, TotalCoinsMined, TotalCoinSupply, and Class. For some reasoin the headers do not display unless the mouse hovers over the respective header.

![Tradeable_Cryptocurrencies](https://user-images.githubusercontent.com/111096246/214394640-e280f972-036c-4802-8ae8-bc1a8294126c.PNG)

A 2D scatter plot was then created using the same algorithm as the 3D scatter plot, however this time the number of principal components was just two.

![2D_Scatter_Plot](https://user-images.githubusercontent.com/111096246/214394333-03237c85-da47-4f2c-88d4-b86e22483ea2.PNG)

## Summary

Based on the similarities between the cryptocurrencies, we have identified and classified 532 of them. For further analysis, each cryptocurrency should be analyzed individually, and more thoroughly.
