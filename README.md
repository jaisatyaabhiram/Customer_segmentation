# 🛍️ Customer Segmentation using K-Means and PCA

## ✅ Day 3 of "7 Days of AI: Build Real Projects with Me!"

This project focuses on **Unsupervised Learning** using clustering techniques to segment customers based on features such as income and spending score. It applies **K-Means Clustering** and **Principal Component Analysis (PCA)** for both analysis and visualization.

---

## 🎯 Topics Covered

- **K-Means Clustering**
  - Cluster assignment
  - Centroid updates
  - Distance metric (Euclidean distance)
- **Elbow Method**
  - To find the optimal number of clusters (k)
- **Principal Component Analysis (PCA)**
  - Dimensionality reduction
  - 2D visualization of high-dimensional data

---

## 📊 Project Objective

Segment customers into distinct groups based on:
- **Age**
- **Annual Income**
- **Spending Score**

This type of analysis is helpful for marketing strategies such as targeting specific customer groups with personalized campaigns.

---

## 🗃️ Dataset

The dataset includes the following columns:

| CustomerID | Gender | Age | Annual Income (k$) | Spending Score (1–100) |
|------------|--------|-----|---------------------|--------------------------|
| 1          | Male   | 19  | 15                  | 39                       |
| 2          | Male   | 21  | 15                  | 81                       |
| 3          | Female | 20  | 16                  | 6                        |
| 4          | Female | 23  | 16                  | 77                       |
| 5          | Female | 31  | 17                  | 40                       |

*Note: The full dataset contains 200 entries.*

---

## ⚙️ Technologies Used

- Python 🐍
- Pandas & NumPy for data handling
- Matplotlib & Seaborn for visualization
- Scikit-learn for K-Means and PCA

---

## 📌 Steps Performed

1. **Data Preprocessing**
   - Removed irrelevant columns like `CustomerID`
   - Converted categorical variables (e.g., Gender) using label encoding (if needed)

2. **Exploratory Data Analysis**
   - Plotted distributions of features like income and spending score

3. **Elbow Method**
   - Identified optimal number of clusters using the WCSS (Within-Cluster Sum of Squares)

4. **K-Means Clustering**
   - Applied K-Means algorithm to cluster customers

5. **PCA Visualization**
   - Reduced data to 2D using PCA
   - Visualized clusters in 2D space

---

## 📈 Results

- Identified **distinct customer segments**
- Gained insight into how spending habits and income correlate
- Visualized customer groups using color-coded scatter plots

---

## 🖼️ Sample Visualization

*Include a PCA or K-Means Cluster plot here if available*


