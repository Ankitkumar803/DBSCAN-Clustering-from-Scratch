# DBSCAN-Clustering-from-Scratch

This notebook demonstrates how to implement Density-Based Spatial Clustering of Applications with Noise (DBSCAN) from scratch in Python.

DBSCAN is a popular clustering algorithm used in machine learning and data mining. It is especially useful when dealing with data that has non-uniform density or contains noise. The algorithm groups together points that are close to each other and identifies points that are far from any cluster as noise.

In this notebook, we will go through the following steps to implement DBSCAN:

- Load the dataset
- Implement DBSCAN algorithm
- Evaluate the performance of the algorithm
- Visualize the clusters
## Dataset
We have created a artifical [dataset for DBSCAN](https://www.kaggle.com/datasets/ankit8467/dataset-for-dbscan/settings).

## Implementation
The DBSCAN algorithm consists of two main steps:

Finding the core points
Forming clusters around the core points
A point is a core point if there are at least min_samples points within a distance of eps (epsilon) around it. A cluster is formed by connecting core points that are within a distance of eps of each other. Points that are not core points and are not within a distance of eps of any core point are considered noise.

## Visualization
We will visualize the clusters using a scatter plot with different colors for each cluster.

## Conclusion
In this notebook, we have implemented the DBSCAN algorithm from scratch in Python and applied it to the Iris dataset. We have also evaluated the performance of the algorithm using the adjusted Rand index and visualized the clusters using a scatter plot.

## References
[Density-Based Spatial Clustering of Applications with Noise (DBSCAN)](https://en.wikipedia.org/wiki/DBSCAN)
[scikit-learn: Clustering with DBSCAN](https://scikit-learn.org/stable/modules/clustering.html#dbscan)
