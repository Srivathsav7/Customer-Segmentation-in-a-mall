# Customer-Segmentation-in-a-mall
Getting clusters based on annual income of customers and how their spending score(1-100) is.

Variables in the dataset:
Customer ID
Gender
Age
Annual Income
Spending Score

Only two features are selected from the datset for determining the clusters, after that we take into account the elbow method to determine the right number of clusters
that are needed for our given problem. 

WCSS is the sum of squares of distances between each point in a cluster and its centroid, when the value of WCSS is almost parallel after a ertain point, this point 
is chosen as the right value of k.

Random initialization occurs when the centroids are chosen differently than the obvious, this can be avoided in python by using init='kmeans++'.



