# Cryptocurrencies

## Overview of the analysis
 
For this project, we aim to learn about cryptocurrencies and how they can be grouped into a classification system for new investments. This is an unsupervised learning problem since we don't know what the output will be. Clustering was chosen as the way to categorize the cryptocurrencies. Afterwards, we incorporated data visualization to present our findings.

## Results

The crypto_data.csv was retrieved from [CryptoCompare](https://min-api.cryptocompare.com/data/all/coinlist). It consists of 6 columns: 	Coin Name,	Algorithm,	IsTrading (Boolean),	Proof Type,	Total Coins Mined, and	Total Coin Supply and 1252 rows. We started by preparing the data for the principal component analysis by removing the null values, label encode the data using get dummies and scale the data using Standard Scaler. Then we used PCA to reduce dimension to three principal components. Finally, we used K-means algorithm to predict the K clusters for the cryptocurrencies’ data. The elbow curve suggested 4 clusters  is the best value. 

![bokeh_plot](https://user-images.githubusercontent.com/66279829/173300310-b3467ab4-8c58-4c0d-aaf3-463e693f1c37.png)
![bokeh_plot (1)](https://user-images.githubusercontent.com/66279829/173300345-a8466924-3d17-4725-8ce0-a3f57a252aa1.png)
![newplot (1)](https://user-images.githubusercontent.com/66279829/173300364-ce515375-0691-4370-bd72-0e60bc7db4d1.png)


