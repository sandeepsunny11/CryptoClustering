# Crypto Market Clustering with K-Means and PCA
This assignment applies clustering analysis on cryptocurrency market data using K-Means and Principal Component Analysis (PCA) to identify patterns in market trends. 
We analyze the performance of different cryptocurrencies by normalizing the data, finding the optimal number of clusters, and visualizing the data using both the original and PCA-reduced features.

This project uses the following Python libraries:
pandas,
scikit-learn,
matplotlib,
hvplot, and
numpy

# Project Workflow
Data Preparation: 
Load the cryptocurrency market data from a CSV file.
Normalize the data using StandardScaler to remove bias introduced by different value ranges.

# K-Means Clustering
Apply the K-Means algorithm to the normalized data to group similar cryptocurrencies.
Determine the optimal number of clusters (k) using the Elbow Method by plotting inertia values.

# Visualization
Scatter plots are used to visualize the clusters of cryptocurrencies, initially based on the original data, and later using PCA-reduced data.

 # Principal Component Analysis (PCA)
PCA is used to reduce the dataset to 3 components, which capture the majority of the variance.
A second round of clustering is performed on this reduced dataset, and the results are compared with the original clusters.

# Analysis
The assignment also includes an analysis of feature weights on each principal component, highlighting the influence of each feature on the clustering process.
