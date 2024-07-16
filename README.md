# Customer Segmentation Project

This project involves customer segmentation using KMeans clustering to identify distinct customer groups based on their annual income and spending scores. The goal is to segment customers into different clusters to better understand their behavior and tailor marketing strategies accordingly.

## Project Overview

1. **Data Preprocessing**: 
   - Imported necessary libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, and `sklearn`.
   - Loaded the dataset and performed initial exploration, including checking for missing values and understanding the data structure.
   - Selected relevant features (`Age`, `Annual Income (k$)`, and `Spending Score (1-100)`) for clustering.

2. **KMeans Clustering**:
   - Used the KMeans algorithm to cluster customers based on their annual income and spending scores.
   - Determined the optimal number of clusters using the elbow method.
   - Visualized the clusters and their centroids to interpret the results.

3. **Visualization**:
   - Plotted the customer clusters and their centroids using Matplotlib and Seaborn.
   - Each cluster is represented by a different color, and centroids are highlighted for better visualization.
