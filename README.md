# Crypto Clustering Project

## Overview
In this project, we apply advanced data analysis techniques, specifically K-means clustering and Principal Component Analysis (PCA), to classify cryptocurrencies based on their price fluctuations. The project involves data preparation, normalization, determining the optimal number of clusters (k), clustering cryptocurrencies, optimizing clusters with PCA, visualization, and analysis.

## Objectives
- **Data Preparation**: Clean and normalize the data for uniform analysis.
- **Optimal Number of Clusters**: Use the elbow method to determine the best `k` value for K-means clustering.
- **Clustering with K-means**: Apply K-means clustering to classify cryptocurrencies into distinct groups.
- **PCA Optimization**: Employ PCA to enhance cluster analysis by reducing feature dimensions.
- **Visualization**: Create visual representations of clusters before and after PCA optimization.
- **Analysis**: Analyze the impact of PCA on clustering results.

## Getting Started
1. Clone the `CryptoClustering` repository to your local machine.
2. Ensure Python 3.8+ is installed.
3. Install necessary libraries: `pandas`, `scikit-learn`, `matplotlib`, `plotly`.

## Usage
- Load the `crypto_market_data.csv` file into a DataFrame, setting `coin_id` as the index.
- Normalize the data using `StandardScaler`.
- Determine the optimal number of clusters using the elbow method.
- Apply K-means clustering using the optimal `k`.
- Perform PCA to reduce dimensions to three principal components.
- Cluster the PCA-transformed data using K-means.
- Visualize the original and PCA-optimized clusters.
- Analyze the feature weights on each principal component to understand their influence.

## Visualization
Visualizations include:
- Elbow curve to determine the optimal `k`.
- Scatter plots of clusters based on 24h and 7d price changes.
- PCA component scatter plots.

## Final Steps
- Review and document your code.
- Push your final notebook to the GitHub repository.

## Dependencies
- Python 3.8+
- Libraries: `pandas`, `scikit-learn`, `matplotlib`, `plotly`

## Repository Structure
- `Crypto_Clustering.ipynb`: Jupyter notebook with all the project code and analysis.
- `crypto_market_data.csv`: Dataset used for clustering.
- `README.md`: Project overview and instructions.

## Conclusion
This project demonstrates the power of K-means clustering and PCA in classifying cryptocurrencies. Through this analysis, we can gain insights into the dynamic world of cryptocurrency markets.

## Contact
For any queries regarding this project, please open an issue in the GitHub repository.

## Acknowledgments
- Columbia University's AI Bootcamp for the project guidelines.
- Open-source contributors for the Python libraries used in this project.

