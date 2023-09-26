# Unsupervised Learning

## Table of Contents

1. [Introduction](#introduction)
2. [Types of Unsupervised Learning](#types-of-unsupervised-learning)
    - [Clustering](#clustering)
    - [Association](#association)
    - [Dimensionality Reduction](#dimensionality-reduction)
3. [Common Algorithms](#common-algorithms)
    - [Clustering Algorithms](#clustering-algorithms)
    - [Dimensionality Reduction Algorithms](#dimensionality-reduction-algorithms)
4. [Evaluation Metrics](#evaluation-metrics)
5. [Conclusion](#conclusion)

## Introduction

Unsupervised Learning is a type of machine learning where the model is trained on an unlabeled dataset. Unlike supervised learning, there are no correct answers, and the algorithm tries to identify patterns or regularities in the data.

## Types of Unsupervised Learning

Unsupervised learning can be categorized into several types, including Clustering, Association, and Dimensionality Reduction.

### Clustering

In clustering tasks, the aim is to partition a set of data points into groups or clusters based on their similarities.

#### Example:

Customer segmentation based on purchasing behavior.

### Association

In association rule learning, the goal is to discover interesting relationships or associations among a large set of data items.

#### Example:

Market basket analysis, such as finding that customers who buy diapers often also buy baby formula.

### Dimensionality Reduction

Dimensionality reduction techniques reduce the number of input variables in a dataset, effectively aiming to simplify the dataset while retaining its essential features.

#### Example:

Principal Component Analysis (PCA) used to reduce the dimensions of a dataset.

## Common Algorithms

### Clustering Algorithms

Here are some commonly used algorithms for clustering tasks:

1. **K-Means**: Partitioning method that divides the dataset into K predefined distinct, non-overlapping subsets (or clusters).
2. **Hierarchical Clustering**: Builds a tree of clusters by successively merging or splitting groups.
3. **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)**: Groups together data points that are closely packed together.

### Dimensionality Reduction Algorithms

Here are some commonly used algorithms for dimensionality reduction:

1. **Principal Component Analysis (PCA)**: Orthogonal transformation to convert correlated features into a set of linearly uncorrelated features.
2. **t-Distributed Stochastic Neighbor Embedding (t-SNE)**: Reduces dimensionality while trying to keep similar instances close and dissimilar instances apart.
3. **Autoencoders**: Neural networks used for unsupervised learning of efficient codings.

## Evaluation Metrics

Evaluating the performance of unsupervised learning algorithms is less straightforward than supervised methods. However, some metrics are commonly used:

- **Clustering**: Silhouette Score, Davies–Bouldin index
- **Dimensionality Reduction**: Explained Variance

## Conclusion

Unsupervised learning offers various algorithms for clustering and dimensionality reduction among other tasks. Although it lacks the straightforward evaluative metrics present in supervised learning, unsupervised learning is essential for understanding complex data structures and discovering hidden patterns in the data.
