# CUSTOMER_SEGMENTATION
# Customer Segmentation using K-means Clustering



## Objective

This project aims to segment customers based on their annual income and spending score, facilitating targeted marketing strategies for improved customer engagement and satisfaction.

## Approach

### 1. Data Exploration

- Conducted initial data exploration to assess dataset structure and suitability for clustering analysis.
- Gained insights into data distribution, statistics, and relevant features.

### 2. Data Preprocessing

- Performed data cleaning and handled missing values to ensure data integrity.
- Standardized features, specifically annual income and spending score, for consistent scaling, enhancing the effectiveness of the K-means algorithm.

### 3. Elbow Method Implementation

- Implemented the Elbow Method from scratch, independently of built-in functions.
- Determined the optimal number of clusters (k=5) based on within-cluster sum of squares (WCSS) analysis.
- Visualized the WCSS plot to identify the 'elbow point,' indicating the suitable number of clusters.

### 4. K-means Clustering

- Applied the K-means clustering algorithm using the scikit-learn library.
- Configured the algorithm with k=5 clusters and initialized it with the "k-means++" method for improved convergence.

### 5. Cluster Interpretation

- Analyzed and interpreted the characteristics of each cluster to define distinct customer segments.
- Identified patterns of spending behavior and annual income within each cluster.

## Result

The K-means clustering analysis yielded five distinct customer segments based on their income and spending behavior:

1. Cluster 1 (Red): Moderate annual income and moderate spending score.
2. Cluster 2 (Blue): High annual income and high spending score.
3. Cluster 3 (Green): Low annual income and high spending score.
4. Cluster 4 (Cyan): Low annual income and low spending score.
5. Cluster 5 (Magenta): High annual income and low spending score.

These insights provide valuable information for tailoring marketing strategies and enhancing customer engagement.

## Project Highlights

- Demonstrated proficiency in data preprocessing, clustering analysis, and data visualization.
- Independent implementation of the Elbow Method showcases coding skills and understanding of the clustering process.

## Usage




1. Install required libraries:


2. Run the project:

