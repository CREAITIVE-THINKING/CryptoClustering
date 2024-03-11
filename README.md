# Cryptocurrency Clustering and K-Means Project Documentation

This project aims to segment cryptocurrencies based on their market data using Principal Component Analysis (PCA) and K-means clustering. The goal is to identify patterns in the cryptocurrency market and group similar cryptocurrencies together.

## Overview

The project involves several key steps:
1. **Data Preprocessing**: Normalize the market data using `StandardScaler` from scikit-learn.
2. **PCA Transformation**: Reduce the dimensionality of the data to capture essential features with less redundancy.
3. **Determining Optimal k**: Use the elbow method to find the best number of clusters for K-means clustering.
4. **K-means Clustering**: Segment the cryptocurrencies into clusters based on their PCA-transformed features.
5. **Analysis**: Interpret the clustering results and the significance of the principal components.

## Technologies Used

- **Pandas**: For data manipulation and analysis.
- **Scikit-learn**: For applying `StandardScaler`, PCA, and K-means clustering.
- **Matplotlib**: For plotting the elbow curve to determine the optimal k value.
- **hvPlot**: For creating interactive scatter plots of the clustered data.

## Key Findings

- The PCA transformation effectively reduced the dataset's dimensionality while retaining around 89.5% of the variance, indicating a successful dimensionality reduction with minimal loss of information.
- The optimal number of clusters (k) was identified as 5 using the elbow method, indicating that the cryptocurrency market data can be effectively segmented into 5 distinct groups.
- The scatter plot visualization of the clustered data provided insights into the distribution and relationship between different cryptocurrencies based on their market movements.

## Steps to Reproduce

1. Load and normalize the market data.
2. Apply PCA to reduce the dimensions to three principal components.
3. Determine the optimal number of clusters using the elbow method.
4. Perform K-means clustering with the optimal k.
5. Visualize the clustering results using scatter plots.

## Conclusion

This project demonstrated the power of PCA and K-means clustering in uncovering hidden patterns in high-dimensional data. By reducing the dimensionality of the cryptocurrency market data and segmenting it into meaningful clusters, we gained valuable insights into the similarities and differences between various cryptocurrencies.

For more detailed analysis and future work, consider exploring other clustering algorithms and dimensionality reduction techniques to compare their effectiveness in different scenarios.  Reviewed documentation and used GPT-4 to assist.

