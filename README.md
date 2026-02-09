# Lab 3: Clustering Analysis on Wine Dataset
This Repo is Lab 3: Clustering Analysis Using K-Means and K-Medoids Algorithms in Jupyter Notebook for MSCS 634

## Overview
This lab explores clustering techniques on the Wine dataset from the sklearn library. I applied **K-Means** and **K-Medoids** algorithms to analyze and compare clustering performance. By visualizing clusters and computing evaluation metrics, I assessed their quality and structure.

## Key Steps
1. **Data Preparation:** The dataset was loaded, explored, and standardized to ensure consistent scaling across features.  
2. **K-Means Clustering:** Performed with 3 clusters, evaluated using **Silhouette Score** and **Adjusted Rand Index (ARI)**.  
3. **K-Medoids Clustering:** Performed using PyClustering with 3 clusters, evaluated with the same metrics for comparison.  
4. **Visualization:** Side-by-side scatter plots were created to show K-Means centroids and K-Medoids medoids, highlighting cluster shapes and positions.  

## Key Insights
- **K-Means** produces compact, roughly spherical clusters and generally has a higher Silhouette Score.  
- **K-Medoids** is more robust to outliers, with medoids always being actual data points, which can better capture irregular cluster shapes.  
- Choosing between K-Means and K-Medoids depends on dataset characteristics and interpretability requirements.  

## Challenges
- Installing and using PyClustering for K-Medoids required a compatible environment.
- Having issue with PyClaster in arm64 Apple Silicon, then decided to do it in Google Colab.
- Deciding which features to visualize (Alcohol vs Flavanoids) for clear cluster separation.  

## Conclusion
This lab demonstrates how unsupervised learning techniques can uncover hidden patterns in datasets. By applying **K-Means** and **K-Medoids** to the Wine dataset, I was able to group wines based on their chemical properties without using class labels. 

Key takeaways from the lab include:  
- **Clustering effectiveness:** Metrics like **Silhouette Score** and **Adjusted Rand Index (ARI)** allow us to assess how well the algorithms formed meaningful clusters quantitatively.  
- **Algorithm behavior:** K-Means tends to produce more compact and evenly shaped clusters, while K-Medoids is more robust to outliers and adapts to irregular cluster shapes.  
- **Visualization importance:** Side-by-side plots of clusters with centroids and medoids help interpret cluster positioning and understand relationships between features.  
- **Practical implications:** Depending on the dataset and goals, one can choose K-Means for speed and simplicity or K-Medoids for robustness and interpretability.  

Overall, the lab highlights the importance of combining clustering algorithms, evaluation metrics, and visualization to gain insights from unlabeled data and make informed decisions in data analysis.

