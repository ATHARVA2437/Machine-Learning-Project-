# 🛍️ Mall Customer Segmentation using Unsupervised Learning

## 📌 Overview

This project focuses on segmenting mall customers using unsupervised machine learning techniques to support personalized marketing strategies. By analyzing customer attributes such as age, gender, annual income, and spending score, the goal is to identify distinct customer groups for targeted engagement and improved service delivery.

## 👥 Team Members

- **Vedant Ghodmare** (Roll No. 62) – [ghodmarevr@rknec.edu](mailto:ghodmarevr@rknec.edu)  
- **Atharva Rathi** (Roll No. 64) – [rathiaa_1@rknec.edu](mailto:rathiaa_1@rknec.edu)  
- **Group ID**: 5  
- **Course**: ECSP303 – Machine Learning Mini Project  
- **Institution**: Shri Ramdeobaba College of Engineering and Management

## 📂 Dataset

- **Source**: Kaggle – Mall Customer Segmentation Dataset  
- **Size**: 200 records  
- **Features**:
  - `CustomerID` (excluded from modeling)
  - `Gender` (encoded)
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1–100)`

## 🧹 Data Preprocessing

- Handled missing values (none found)
- Encoded categorical data (Gender)
- Normalized numerical features using Min-Max scaling
- Feature selection: Age, Annual Income, Spending Score
- Applied PCA for dimensionality reduction and visualization

## 📊 Visualizations

- Distribution plots (Age, Income, Spending Score)
- Scatter plots (`Age vs Spending`, `Income vs Spending`)
- Pair plot and correlation heatmap
- Cluster visualizations for K-Means and Agglomerative Clustering

## 🤖 Algorithms Used

- **K-Means Clustering**  
  - Optimal `k=5` determined via Elbow Method  
  - Evaluated using Silhouette Score

- **Agglomerative Clustering**  
  - Linkage: Average  
  - Distance: Euclidean  

- **DBSCAN**  
  - Density-based clustering without fixed `k`

- **MeanShift Clustering**  
  - Bandwidth estimated automatically for adaptive clusters

## ✅ Evaluation

- **Inertia (WCSS)** for K-Means
- **Silhouette Score** for cluster quality
- Visual inspection of cluster separation

## 💡 Key Insights

- Segmentation revealed groups such as high-income/high-spenders and low-income/conservative spenders
- Agglomerative Clustering offered more hierarchical relationships
- PCA enhanced interpretability and 2D/3D visualization
- Density-based methods (DBSCAN, MeanShift) handled noise and non-linear patterns effectively

## 🔮 Future Enhancements

- Add more features like purchase history and visit frequency
- Explore hybrid clustering or ensemble models
- Conduct time-series analysis to track customer behavior trends
- Integrate clustering results into marketing automation pipelines

## 📚 References

- [Scikit-learn: KMeans](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html)  
- [Scikit-learn: Agglomerative Clustering](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.AgglomerativeClustering.html)  
- [Scikit-learn: StandardScaler](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html)  
- [Seaborn Heatmap](https://seaborn.pydata.org/generated/seaborn.heatmap.html)

## 🔗 Project Repository

GitHub Link: [https://github.com/ATHARVA2437/Machine-Learning-Project-](https://github.com/ATHARVA2437/Machine-Learning-Project-)
