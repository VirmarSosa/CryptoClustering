![image](https://github.com/VirmarSosa/CryptoClustering/assets/118692087/0ba8bddb-e3c6-44b2-958a-041bc4df82f9)

# CryptoClustering

The code is used an unsupervised learning algorithm in Python to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.
Create a data frame with the scaled data and set the "coin_id" index.

## K-value algorithm
Find the Best Value for k Using the Original Scaled Data Frame The best K value is 4 after the calculation.
Apply the K-means algorithm to cluster Cryptocurrencies.

## PCA & K-value algorithm
Perform a PCA to reduce the features to three principal components.
Calculate the total explained variance. The result is 0.8950316570309841.
Find the Best Value for k after PCA and the best K value is 4.
Apply the K-means algorithm to cluster Cryptocurrencies after PCA.
