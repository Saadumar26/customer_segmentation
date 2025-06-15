#  Customer Segmentation Using Clustering

##  Project Overview

This project applies **unsupervised machine learning** techniques to perform **customer segmentation** using clustering algorithms. The goal is to group customers into distinct clusters based on purchasing behavior and demographic features, helping businesses develop targeted marketing strategies.

By analyzing customer data, we uncover patterns that help in understanding customer types — such as high spenders, budget-conscious shoppers, or moderate consumers.

---

##  Objectives

- Understand customer behavior through data exploration
- Apply K-Means clustering to segment customers
- Visualize the resulting clusters in 2D and 3D
- Provide actionable insights for business decision-making

---

## 📂 Dataset

- **Name**: Mall Customer Segmentation Data
- **Source**: [UCI / Kaggle / Public Dataset]
- **Features**:
  - `CustomerID`
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1–100)`

> The dataset contains details of customers visiting a mall and their spending behavior.

---

##  Tools & Technologies

- **Python**
  - `pandas`, `numpy` – data manipulation
  - `matplotlib`, `seaborn`, `plotly` – data visualization
  - `scikit-learn` – machine learning (KMeans, Silhouette Score)
- **Jupyter Notebook** – development environment

---

##  Workflow

1. **Data Preprocessing**
   - Handle missing/null values (if any)
   - Encode categorical variables
   - Normalize/scale data for clustering

2. **Exploratory Data Analysis (EDA)**
   - Distribution plots by gender, age, income
   - Pair plots and correlation heatmaps

3. **Clustering (K-Means)**
   - Determine optimal number of clusters using the Elbow Method and Silhouette Score
   - Train KMeans model and predict clusters

4. **Visualization**
   - 2D scatter plot of clusters (e.g., Income vs. Spending)
   - Interactive 3D visualization for deeper insight

---

##  Results & Insights

- **Optimal Clusters**: 5 (based on Elbow and Silhouette methods)
- **Identified Customer Segments**:
  - High Income – High Spending
  - High Income – Low Spending
  - Low Income – High Spending
  - Average Income – Average Spending
  - Young Shoppers

These clusters enable businesses to:
- Focus loyalty programs on high-spending segments
- Offer discounts to low-spending groups to increase retention
- Design personalized marketing strategies

---

---

##  How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/customer-segmentation.git
   cd customer-segmentation
