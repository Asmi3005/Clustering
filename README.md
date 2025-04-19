# Clustering Assignment - Comparative Performance Study

## 📌 Objective
This project presents a comparative performance study of different clustering algorithms using various preprocessing techniques and evaluation metrics on a small dataset from the UCI Machine Learning Repository.

## 📊 Dataset
**Wholesale Customers Data Set**  
Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/wholesale+customers)  
This dataset contains annual spending in monetary units on diverse product categories for customers from a wholesale distributor.

## 🧪 Clustering Algorithms Used
- KMeans Clustering
- MeanShift Clustering
- Agglomerative Clustering

## ⚙️ Preprocessing Techniques Applied
- Raw (No preprocessing)
- Normalization
- Standardization
- PCA
- Normalization + Standardization
- Normalization + Standardization + PCA

## 🧮 Evaluation Metrics
- Silhouette Score
- Calinski-Harabasz Index
- Davies-Bouldin Score

## 📈 Results & Visualization
Bar plots were generated to compare clustering quality across different algorithms and preprocessing techniques for each evaluation metric. Results are sorted and analyzed based on Silhouette Score.

## ✅ Conclusion
KMeans performed best overall, especially when combined with **Standardization**, achieving high Silhouette scores and strong values on other metrics. Preprocessing significantly improved clustering results across all algorithms. For future work, other clustering methods like DBSCAN could be explored, along with larger datasets.

