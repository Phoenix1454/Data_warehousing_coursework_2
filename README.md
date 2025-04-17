# 📊 Data Warehousing Coursework 2 - Customer Segmentation (Task B)

This project performs customer segmentation using RFM (Recency, Frequency, Monetary) analysis and K-Means clustering. It is part of the university coursework for the Data Warehousing and Business Intelligence module.

## 📁 Task B Overview

- **Objective**: Segment customers based on purchasing behavior using RFM metrics.
- **Tools Used**: Python, Pandas, Scikit-learn, Matplotlib, Seaborn
- **Dataset**: Preprocessed customer transaction data (including Recency, Frequency, Monetary)

## 🧪 Methodology

### 1. RFM Feature Engineering
- **Recency**: Days since last purchase
- **Frequency**: Number of transactions
- **Monetary**: Total spending

### 2. Data Scaling
Used `StandardScaler` to normalize the RFM values before clustering.

### 3. K-Means Clustering
- Elbow Method used to determine the optimal number of clusters.
- Final model applied with `k=4` based on elbow curve inspection.

### 4. Cluster Profiling
Mean values of Recency, Frequency, and Monetary were computed per cluster to derive customer insights.

### 5. Visualization
- Pair plots visualized the cluster distributions.
- Cluster characteristics identified for marketing strategy formulation.

## 📈 Results

| Cluster | Recency | Frequency | Monetary |
|---------|---------|-----------|----------|
|   0     | 43.52   | 1.00      | 1292.17  |
|   1     | 47.61   | 2.14      | 2801.48  |
|   2     | 69.35   | 1.00      | 1321.64  |
|   3     | 53.22   | 1.36      | 78834.98 |

Each cluster represents a different customer segment, helping guide CRM and marketing strategies.


## 📚 References

- [Scikit-learn KMeans Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html)
- [StandardScaler - Scikit-learn](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html)
- [RFM Analysis in Marketing](https://www.optimizely.com/optimization-glossary/rfm-analysis/)
- [Pairplot - Seaborn Documentation](https://seaborn.pydata.org/generated/seaborn.pairplot.html)

## ✍️ Author

Amit — MSc Data Science Student  
GitHub: [@Phoenix1454](https://github.com/Phoenix1454)

---

📌 *This project is part of university coursework and is for academic use only.*
