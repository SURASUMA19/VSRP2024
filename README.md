# VSRP2024

## bionumpy

- Idea is to develop a novel clustering algorithm for single-cell RNA sequencing data to identify distinct cell populations and to Combine dimensionality reduction techniques (e.g., UMAP, t-SNE) with    deep learning-based clustering.
## Approach
- Importing all necessary libraries
- Defining a clustering function single_cell_clustering that takes the data and the number of clusters as input
- PCA for Dimensionality Reduction: PCA reduces the data from its original high-dimensional space to 50 dimensions. This step simplifies the data while retaining most of the important information.
- t-SNE for Further Dimensionality Reduction:t-SNE further reduces the 50-dimensional data to 2 dimensions. This step is primarily for visualization, making it easier to plot and understand the data.
- KMeans Clustering:KMeans algorithm clusters the 2D t-SNE data into the specified number of clusters.
## References
- [bionumpy website](https://bionumpy.github.io/bionumpy/)
