# Clustering Analysis on Wholesale Customers Dataset

This project explores the performance of various clustering algorithms on the **Wholesale Customers** dataset. The aim is to understand how different preprocessing techniques and cluster sizes affect clustering outcomes based on multiple evaluation metrics.

---

## Dataset Details

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wholesale+customers)
- **Total Records**: 440
- **Features**: 7
- **Context**: Annual spending by wholesale customers across different product categories.

---

## Algorithms Compared

- **K-Means**
- **Hierarchical Clustering (HCLUST)**
- **MeanShift**

---

## Preprocessing Approaches

The dataset was analyzed under various preprocessing setups:

- Raw (No Processing)
- Normalization
- Transformation
- PCA
- Transformation + Normalization (T+N)
- Transformation + Normalization + PCA (T+N+PCA)

---

## Cluster Configurations

Evaluated with:
- 3 Clusters
- 4 Clusters
- 5 Clusters

---

## Metrics Used for Evaluation

- **Silhouette Score**
- **Calinski-Harabasz Index**
- **Davies-Bouldin Score**

---

## Highlights

| Evaluation Metric       | Best Result     |
|-------------------------|-----------------|
| Best Algorithm          | MeanShift       |
| Optimal Cluster Count   | 3               |
| Highest Silhouette Score| 0.9076          |

---

## Visual Summaries

Performance results are visualized using grouped bar charts showing metric scores across preprocessing techniques and cluster counts.
