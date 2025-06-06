# Crypto Clustering Challenge

## Overview 
The Crypto Clustering project aims to predict if cryptocurrencies are affected by 24-hour or 7-day price change using techniques learned to analyze and group based on their market performance. Using K-Means clustering and Principal Component Analysis (PCA), the project explores how dimensionality reduction impacts clustering results and provides insights into cryptocurrency behavior.

Data for this dataset was generated by _edX Boot Camps LLC_, and is intended for educational purposes only. 

## Instructions 
#### Step 1: Data Preparation
* Use `StandardScaler()` module from `scikit-learn` to normalize the data from the CSV file 
* Create a Dataframe with the scaled data and set the "coin_id" index from the original DataFrame as the index in the new DataFrame.

#### Step 2: Find the Best Value for k Using the Scaled DataFrame 
* Use the Elbow Method to determine the optimal number of clusters (k) for the original scaled data
* Visualize by plotting the data

#### Step 3: Cluster Cryptocurrencies with K-means Using the Scaled DataFrame 
* Perform K-Means clustering on the original scaled data.
* Visualize the clusters using scatter plots.

#### Step 4: Dimensionality Reduction with PCA
* Reduce the dataset to three principal components using PCA.
* Analyze the explained variance to evaluate how much information is retained.

#### Step 5: Find the Best Value for k Using the PCA DataFrame 
* Use the Elbow Method to determine the optimal number of clusters (k) for the PCA-transformed data
* Visualize by plotting the data

#### Step 6: Cluster Cryptocurrencies with K-means Using the PCA DataFrame 
* Perform K-Means clustering on the PCA-transformed data.
* Visualize the clusters using scatter plots.

#### Step 7: Comparison of Results:
* Compare the Elbow Curves and cluster visualizations for the original scaled data and PCA-transformed data.

## Results 
**Key Finding**
* The optimal number of clusters (k) was determined to be 4 for both the original scaled data and the PCA-transformed data.
* Clustering with PCA-transformed data resulted in tighter and more distinct clusters, demonstrating the benefits of dimensionality reduction.
