# K-Means_Clustering_Implementation

This function implements the K-Means clustering algorithm on a given dataset passed as an array in the first argument. The function also takes in the number of clusters to make and the iteration value for the algorithm.

First, random initialization is done on the data to guess the centroids.

Then, data points are assigned to the closest centroid and new centroids are calculated by averaging the data points in a centroid.

This process in repeated for the number of times specified in the 3rd argument.

The function returns the list of centroids and the centroid assignment of each data point.
