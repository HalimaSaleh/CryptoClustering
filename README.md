# CryptoClustering
# Clustering Cryptocurrencies with K-Means and PCA

## Overview
This project demonstrates clustering of cryptocurrencies based on market data using K-Means clustering and Principal Component Analysis (PCA).

## Steps Involved
1. **Data Preparation:**
   - Load cryptocurrency market data from CSV files.
   - Preprocess data, including scaling using StandardScaler.

2. **Clustering with K-Means:**
   - Apply K-Means to the original dataset to find optimal clusters using the Elbow method.
   - Visualize the Elbow curve to determine the best number of clusters.

3. **Dimensionality Reduction with PCA:**
   - Use PCA to reduce data dimensionality while retaining variance.
   - Cluster cryptocurrencies using K-Means on PCA-transformed data.

4. **Visualization and Analysis:**
   - Plot clusters using scatter plots colored by cluster labels.
   - Analyze impact of dimensionality reduction on clustering accuracy.

## Results
- **Original vs. PCA Data:** 
  - PCA transformation simplifies visualization and potentially improves clustering.
  - Consider trade-offs between dimensionality reduction and information retention.

## Dependencies
- Python 3.x
- Libraries: pandas, scikit-learn, hvplot

## Usage
1. Ensure Python and required libraries are installed.
2. Run provided notebooks to replicate the analysis.
3. Adjust parameters and visualize results based on specific datasets and goals.

## This project is prepared by Halima Saleh