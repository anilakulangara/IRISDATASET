# IRIS DATASET CLUSTERING PROJECT

## Overview

This project applies clustering techniques to the Iris dataset using KMeans and Hierarchical Clustering. The goal is to group data points based on similarity without using class labels.

## Dataset

The Iris dataset consists of 150 samples from three species of Iris flowers (Setosa, Versicolor, and Virginica). Each sample has four features:

-Sepal length

-Sepal width

-Petal length

-Petal width

Since this is a clustering problem, the species column is dropped before analysis.

## Implementation

1. Loading and Preprocessing (1 mark)

*Load the Iris dataset from sklearn.datasets.

*Convert it into a Pandas DataFrame.

*Drop the species column as clustering is unsupervised.


2. Clustering Algorithm Implementation (8 marks)

A) KMeans Clustering (4 marks)

KMeans is a centroid-based clustering algorithm that partitions data into k clusters by minimizing the sum of squared distances between data points and their assigned cluster centers.

It iterates between assigning points to the nearest cluster and updating cluster centroids until convergence.

Suitability for Iris Dataset:

Works well with small datasets like Iris.

Computationally efficient.

B) Hierarchical Clustering

Hierarchical clustering builds a tree-like structure of nested clusters (dendrogram) by either a bottom-up (agglomerative) or top-down (divisive) approach.

Clusters are merged based on distance metrics until a single cluster remains.

Suitability for Iris Dataset:

Does not require pre-specifying the number of clusters.

Useful for understanding hierarchical relationships in data.

Can reveal structure in small datasets.

## Conclusion

KMeans and Hierarchical clustering both provide insights into the Iris dataset.

KMeans is efficient but requires predefined k, while Hierarchical clustering helps visualize cluster relationships.
