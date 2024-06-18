COMPANY ; CODTECH IT SOLUTIONS
MENTOR : G.SRAVANI
DOMIAN : DATA SCIENCE
DURATION  : 20TH MAY TO JUNE 20TH

LIBRARIES
pandas: Used for data manipulation and creating DataFrames.
matplotlib.pyplot (not explicitly imported but implied for later visualization): Used for creating plots._Used for K-Means clustering.sklearn.metrics.silhouette_score_ Used to calculate the silhouette score_
Data:

A sample dataset (data) is created as a dictionary containing book genres, average ratings, and number of pages.
This data is converted to a pandas DataFrame (df).
K-Means Clustering:

The number of clusters (k) is defined as 3 (initially, you can experiment with different values).
A KMeans model (kmeans) is created with the specified number of clusters and a random state for reproducibility.
The model is fitted using the DataFrame columns "Avg_Rating" and "Num_Pages". This tells KMeans to cluster the data points based on these two features.
Cluster labels are assigned to each data point in the DataFrame using the kmeans.labels_ attribute. This creates a new column "Cluster" that indicates which cluster each book belongs to.
Silhouette Score:

The silhouette_score function is used to calculate the silhouette score for the clustering. It takes the data (containing features) and the cluster labels as input.
The score is printed.
Visualization (Optional):

The code mentions using matplotlib to visualize the clusters using a scatter plot.
