## K-Means Clustering for Interest-Based Grouping

## 📋 Project Overview

This project applies K-Means clustering to group individuals based on their interests. By analyzing user preferences, we aim to segment people into homogeneous clusters, enabling personalized recommendations or targeted marketing strategies.

## 🗂 Dataset

The dataset, **kaggle_Interests_group.csv**, contains user information and interest-based features.

1. **Key features:**
    - Various interest categories as numerical values.
    - Users represented as feature vectors.


## 🏗 Methodology

1. **Data Cleaning:** Replaced missing values and standardized the dataset.
2. **Elbow Method:** Used to determine the optimal number of clusters (k).
3. **K-Means Clustering:**
    - Initialized k centroids randomly.
    - Assigned each point to the nearest centroid.
    - Updated centroids based on cluster means.
    - Repeated until convergence.
    - Dimensionality Reduction: Used PCA for visualization.
4. **Cluster Visualization:** Plotted results in a 2D space.

## 📊 Results & Insights

- Successfully segmented users into 3 clusters based on their interests.
- Observed distinct clusters with well-separated centroids.
- Identified potential outliers in user behavior.

## 🔧 How to Run

1. **Install dependencies:**
```bash 
pip install pandas numpy matplotlib seaborn scikit-learn
```
2. **Run the clustering script:**
```bash 
jupyter notebook K-Means.ipynb
```

## 📌 Key Insights

- K-Means effectively groups users with similar interests.
- PCA visualization highlights cluster separation.
- The method is useful for segmentation tasks like targeted marketing.

## 🔮 Future Improvements

- Experiment with K-Means++ for better centroid initialization.
- Test other clustering algorithms like DBSCAN or Agglomerative Clustering.
- Deploy a web-based tool for interactive analysis.