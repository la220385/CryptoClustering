# Crypto Clustering

In this project, I leveraged Python and unsupervised learning techniques to predict how cryptocurrencies are affected by changes in their prices over different time periods.

## Overview

This project aims to cluster cryptocurrencies based on their performance metrics such as 24-hour and 7-day price changes using K-means clustering. The data will be scaled and optimized using Principal Component Analysis (PCA) to enhance the clustering process.


## Files

- `crypto_market_data.csv`: Dataset containing various cryptocurrencies performance metrics.
- `Crypto_Clustering.ipynb`: Jupyter notebook with all the project code.

### Data Preparation

1. **Load Data**: Start by loading your cryptocurrency data into a DataFrame.
2. **Explore Data**: Generate summary statistics and visualize the data.
3. **Scale Data**: Use `StandardScaler()` to normalize the data.

### Clustering Cryptocurrencies

#### Find the Optimal Number of Clusters (k)

- Implement the elbow method to determine the best `k`:
  - Create a range of k values.
  - Plot inertia to find the elbow point.

#### Cluster with K-Means

- Apply K-means clustering to the scaled data.
- Analyze and visualize the clusters.

### Optimize with PCA

- Perform PCA to reduce dimensions.
- Compare clustering results from PCA-transformed data to original data.

### Visualization

- Visualize the clusters using scatter plots and identify patterns.

## Key Learnings

- **Web Scraping**: Techniques for extracting data programmatically.
- **Data Analysis**: Skills in manipulating large datasets.
- **Clustering**: Understanding of K-means and its application.
- **PCA**: Benefits of dimensionality reduction in clustering.

## Tools and Resources Used

- **Python**: Primary programming language.
- **Pandas**: Data manipulation and analysis.
- **hvPlot**: Visualization of the clusters.
- **Scikit-learn**: Implementation of standard scaler, PCA, and K-means.
- **Jupyter Notebook**: Interactive coding environment.


## Conclusion
This project successfully implemented unsupervised learning techniques to analyze and cluster cryptocurrencies based on their performance metrics. By utilizing the K-means clustering algorithm, we identified distinct groups of cryptocurrencies that share similar price change behaviors over various periods. The application of Principal Component Analysis further refined our clustering approach by reducing the dimensionality of our dataset, which enhanced the clustering performance and visualization clarity.

