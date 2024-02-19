# Clustering Assignment README

## Introduction
This repository contains the code and results for a clustering assignment, which aims to conduct a comparative performance study of different clustering algorithms using various preprocessing techniques with different numbers of clusters on different evaluation parameters. The assignment is completed using a small dataset obtained from the UCI Machine Learning Repository.

### Dataset Used
The dataset selected for this assignment is the Online Shoppers Purchasing Intention Dataset, which can be found at [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset).

## Clustering Analysis
In this assignment, we performed clustering analysis using PyCaret, a Python library for automating machine learning workflows. Three different clustering techniques were applied:

1. K-means Clustering
2. Agglomerative Clustering
3. Density-Based Spatial Clustering

### Preprocessing Techniques
Several preprocessing techniques were employed to observe their effects on clustering performance:

1. No Data Preprocessing
2. Using Normalization (N)
3. Using Transform (T)
4. Using PCA (Principal Component Analysis)
5. Using T+N
6. Using T+N+PCA

### Number of Clusters
Clustering was conducted for different numbers of clusters: 3, 4, 5, and 6.

## Instructions
To replicate the analysis or explore the results:
1. Clone or download this repository to your local machine.
2. Open the provided Colab notebook in Google Colab or any Jupyter Notebook environment.
3. Follow the instructions in the notebook to execute the code cells.
4. Explore the generated results, tables, graphs, and conclusions.

## Results and Conclusion
The results of the clustering analysis, along with tables, graphs, and conclusions, are provided within the notebook. Each preprocessing technique and clustering algorithm's performance is evaluated based on various evaluation parameters (Silhouette, Calinski-Harabasz, Davies-Bouldin), providing insights into their effectiveness under different scenarios.

Additionally, the Technique for Order of Preference by Similarity to Ideal Solution (TOPSIS) method was used to identify the best clustering technique and the optimal number of clusters. The results indicate that the best clustering technique is K-means clustering with 3 clusters.

## Contributors
- Chhavi Dhankhar

Thank you for exploring this clustering assignment repository!
