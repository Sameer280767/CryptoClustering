# Crypto Clustering Project
## Description
The Crypto Clustering Project involves the analysis and clustering of cryptocurrency market data. In this project, we use K-Means clustering and Principal Component Analysis (PCA) to group cryptocurrencies based on their price change percentages. The goal is to identify patterns and relationships within the cryptocurrency market.

## Table of Contents
- Usage
- Data Sources
- Libraries Used
- Analysis Steps
- Results


### Usage
- ##### Load the cryptocurrency market data CSV file into a Pandas DataFrame.
- ##### Explore and preprocess the data, including normalizing the features using StandardScaler.
- ##### Perform K-Means clustering on the original and PCA-transformed data.
- ##### Visualize the Elbow curve to determine the optimal number of clusters (k).
- ##### Use the optimal k to cluster the cryptocurrencies and add the cluster labels to the DataFrame.
- ##### Explore and analyze the results using visualizations, such as scatter plots and cluster comparisons.


## Libraries Used
- #### Pandas
- #### scikit-learn
- #### hvPlot

## Analysis Steps
##### Load and preprocess the data.
##### Normalize the features using StandardScaler.
##### Determine the optimal number of clusters (k) using the Elbow curve.
##### Perform K-Means clustering on the original and PCA-transformed data.
##### Add cluster labels to the DataFrame.
##### Visualize and interpret the results.

##Results
The project results in a clustered dataset, with each cryptocurrency assigned to a specific cluster. Visualizations provide insights into the relationships between cryptocurrencies based on their price change patterns.
