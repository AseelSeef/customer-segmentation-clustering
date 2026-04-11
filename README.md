# 🛍️ Customer Segmentation Using Clustering

![Python](https://img.shields.io/badge/Python-3.9+-blue)
![ML](https://img.shields.io/badge/Machine%20Learning-Clustering-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 📌 Overview
This project applies **unsupervised machine learning techniques** to segment customers based on behavioral and value-driven features from a large e-commerce dataset.

The goal is to identify meaningful customer groups to support:
- 🎯 Targeted marketing strategies
- 🔁 Customer retention improvement
- 💰 Increased business profitability

The dataset includes customer behavior across multiple regions and includes features such as frequency, recency, customer lifetime value (CLV), average unit cost, and age.

---

## 🧠 Problem Statement
The business lacks a clear understanding of distinct customer groups and their purchasing behavior. Without segmentation, marketing efforts are inefficient and not personalized.

This project addresses this by applying clustering techniques to uncover hidden customer segments.

---

## 🧪 Approach

### 1. Data Preprocessing
- Handling missing values and inconsistencies
- Feature engineering (Frequency, Recency, CLV, Avg Unit Cost, Age)
- Feature scaling for clustering performance

### 2. Exploratory Data Analysis (EDA)
- Distribution analysis of key features
- Identification of skewed behavior in Frequency and Recency
- Outlier detection using IQR method

### 3. Dimensionality Reduction
- PCA for visualization of cluster structure
- t-SNE for nonlinear structure exploration

### 4. Clustering Methods
- K-Means Clustering
- Hierarchical Clustering (Dendrogram analysis)

---

## 📊 Key Results

### 🔹 Outlier Detection (IQR)
- Most features show moderate variability
- Outliers represent meaningful customer behavior, not data errors

---

### 🔹 Elbow Method
- Inertia decreases significantly until k = 4–5
- Elbow point suggests optimal cluster range: **4–5 clusters**

---

### 🔹 Silhouette Score
- k = 5 achieved slightly better score (**0.267**) than k = 4 (**0.253**)
- Indicates improved cluster separation

---

### 🔹 Hierarchical Clustering
- Dendrogram suggests **4 natural clusters** based on linkage distance

---

### 🔹 K-Means Performance
- k = 4 → inertia: 171,013.90
- k = 5 → inertia: 145,078.79
- Better cohesion observed with higher k

---

### 🔹 Final Cluster Decision
- Combined evaluation suggests **5-cluster solution** as optimal balance between:
  - Statistical performance
  - Business interpretability

---

## 📈 Cluster Insights
- High-value customers: high frequency, high engagement
- At-risk customers: high recency, inconsistent activity
- Growth potential customers: moderate engagement, upsell opportunity
- Low-value customers: low frequency and spending

---

## 📉 Visualizations
- 📊 Boxplots: cluster behavior comparison
- 📉 PCA: linear separation of clusters
- 🔵 t-SNE: nonlinear structure validation
- 🌳 Dendrogram: hierarchical grouping structure

📄 [View Full Report](./customer-segmentation-clustering.pdf)

---

## 💼 Business Impact
This segmentation enables:
- Personalized marketing campaigns
- Improved customer retention strategies
- Identification of high-value customer groups
- Efficient allocation of marketing budget
- Increased customer lifetime value (CLV)

---

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib / Seaborn
- PCA
- t-SNE
- K-Means Clustering
- Hierarchical Clustering

---

## 🚀 Recommendations
- Deploy cluster-based marketing strategies
- Use personalized campaigns per segment
- Focus retention on high-value customers
- Reactivate at-risk customers with targeted offers
- Optimize marketing spend using segmentation insights

---

## ⭐ Summary
This project demonstrates how unsupervised learning and clustering techniques can uncover hidden customer patterns and support data-driven business decisions in e-commerce systems.z
