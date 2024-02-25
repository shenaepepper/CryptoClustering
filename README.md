# CryptoClustering

This code Loads cryptocurrency market data from a CSV file into a Pandas DataFrame.
Normalizes the data using StandardScaler from scikit-learn.
Performs Principal Component Analysis (PCA) to reduce the dimensionality of the data.

Utilizes K-Means clustering algorithm to cluster the cryptocurrencies into groups.
Determines the optimal number of clusters using the Elbow method.
Predicts clusters for both original and PCA-transformed data.

Visualizes the Elbow curve to identify the optimal number of clusters.
Creates scatter plots to contrast the clusters obtained from both original and PCA-transformed data.
Overall, the code aims to analyze cryptocurrency market data, perform clustering to group cryptocurrencies, and visualize the results to gain insights into the data's structure and relationships.
