# Customer Segmentation Project

## Overview

This project demonstrates a comprehensive customer segmentation analysis using clustering techniques and Principal Component Analysis (PCA). The analysis involves the following steps:

1. **Data Preprocessing**
2. **Exploratory Data Analysis (EDA)**
3. **Hierarchical Clustering**
4. **K-Means Clustering**
5. **Principal Component Analysis (PCA)**
6. **Clustering with PCA**
7. **Visualization**
8. **Model Saving**

## Key Features

### Data Preprocessing

- Load and preprocess the customer data.
- Standardize the features for optimal clustering performance.

### Exploratory Data Analysis (EDA)

- Visualize the distribution of categorical features like 'Sex' and 'Occupation'.
- Utilize Seaborn for insightful data visualizations.

### Hierarchical Clustering

- Perform hierarchical clustering using the Ward's method.
- Plot dendrogram to visualize the clustering process.

### K-Means Clustering

- Determine the optimal number of clusters using the elbow method.
- Apply K-Means clustering to segment the customers.
- Evaluate and label the clusters for better interpretability.

### Principal Component Analysis (PCA)

- Apply PCA to reduce dimensionality.
- Analyze the explained variance to understand the importance of each component.
- Visualize the PCA components with a heatmap.

### Clustering with PCA

- Re-run K-Means clustering on the PCA-transformed data.
- Compare and evaluate the performance of clustering with PCA.

### Visualization

- Scatter plots to visualize the clusters based on different features.
- Heatmaps to visualize PCA components.
- Comprehensive plots to compare clustering results.

### Model Saving

- Save the standard scaler, PCA model, and K-Means model using `pickle` for future use.

## Repository Structure

- `KMEANS-PCA Data.csv`: Dataset used for clustering analysis.
- `customer_segmentation.ipynb`: Jupyter Notebook containing the entire analysis and visualizations.
- `std_scaler.pickle`: Saved standard scaler model.
- `pca.pickle`: Saved PCA model.
- `kmeans_df_pca.pickle`: Saved K-Means model after PCA transformation.

## How to Run

1. Clone the repository.
2. Ensure you have the required Python packages installed (`numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, `scipy`, `pickle`).
3. Run the Jupyter Notebook to see the analysis and visualizations.
4. Use the saved models for further predictions or analysis.

## Visualizations

- Count plots for categorical features.
- Dendrogram for hierarchical clustering.
- Elbow plot for determining the optimal number of clusters.
- Scatter plots for customer segmentation.
- Heatmap for PCA components.

## Conclusion

This project provides a thorough customer segmentation analysis, highlighting the importance of data preprocessing, exploratory data analysis, and the application of advanced clustering techniques. The saved models facilitate easy integration into other systems for real-time customer segmentation.

## Contributing

Feel free to contribute or raise issues if you find any bugs or have suggestions for improvement. Enjoy exploring customer segmentation with this project!
