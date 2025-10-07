# 🛍️ Task 2: Customer Segmentation Using K-Means Clustering

## 🎯 Objective
Segment mall customers based on their spending habits and propose targeted marketing strategies for each cluster.  
The goal is to understand customer behavior through unsupervised learning and visualize the discovered segments.

---

## 📘 Dataset Description
**Dataset Name:** Mall Customers Dataset  
**File Used:** `Mall_Customers.csv`  

Each record represents a customer of a shopping mall with the following attributes:
- **CustomerID**: Unique identifier  
- **Genre**: Gender of the customer  
- **Age**: Customer’s age  
- **Annual Income (k$)**: Annual income in thousand dollars  
- **Spending Score (1-100)**: Score assigned by the mall based on spending behavior

---

## ⚙️ Steps Performed

### 1️⃣ Data Loading & Exploration
- Loaded dataset using Pandas  
- Checked data shape, info, and null values  
- Verified numerical and categorical columns  

### 2️⃣ Exploratory Data Analysis (EDA)
- Gender distribution visualization  
- Scatter plots for Age vs Spending Score and Income vs Spending Score  
- Pairplot for correlation overview  
- Detected spending patterns among different genders and income groups  

### 3️⃣ K-Means Clustering
- Selected features: **Annual Income (k$)** and **Spending Score (1-100)**  
- Used **Elbow Method** to find optimal number of clusters (k=5)  
- Applied **K-Means algorithm** for clustering customers into 5 groups  

### 4️⃣ Dimensionality Reduction & Visualization
- Applied **PCA** and **t-SNE** for 2D visualization  
- Plotted clusters with distinct colors to observe clear separation  
- Each cluster represents a unique customer type (e.g., high-income low-spenders, etc.)

---

## 📊 Cluster Analysis & Insights

| Cluster | Description | Customer Behavior | Suggested Strategy |
|----------|--------------|-------------------|--------------------|
| **Cluster 0** | High income, low spending | Affluent but cautious buyers | Offer premium loyalty benefits and personalized deals |
| **Cluster 1** | Medium income, medium spending | Average customers | Regular marketing and membership programs |
| **Cluster 2** | Low income, low spending | Budget-conscious customers | Focus on discounts, value packs |
| **Cluster 3** | High income, high spending | Luxury enthusiasts | Promote high-end products and exclusive experiences |
| **Cluster 4** | Young with moderate income, high spending | Impulsive spenders | Introduce trend-based and influencer-driven promotions |

---

## 📉 Visualizations Included
- Gender Distribution Countplot  
- Scatter plots (Age vs Spending Score, Income vs Spending Score)  
- Elbow Method curve for optimal k  
- PCA & t-SNE based cluster visualization  


