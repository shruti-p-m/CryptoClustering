# CryptoClustering
This challenge contains a jupyter notebook file named Crypto_Clustering.ipynb and the Resources folder. 

The Resources folder contains a crypto_market_data.csv file which holds the data used in the Crypto_Clustering.ipynb.

## Crypto_Clustering.ipynb
This script uses unsupervised learning techniques to make predictions based on the data within crypto_market_data.csv. 

The script scales the data using StandardScaler. With the scaled data, the best value for k is found using the elbow method. Using K-means, the cryptocurrencies are clustered. 

The script then performs PCA and reduces the data to three principal components (PC), and finds the best value for k using the elbow method. With the PCA data, the cryptocurrencies are clustered using K-means.

The script then creates a composite graph of the graphs made with the elbow method using the scaled data and the PCA data, as well as creating a composite graph of the clusters made with the scaled data and the PCA data.
