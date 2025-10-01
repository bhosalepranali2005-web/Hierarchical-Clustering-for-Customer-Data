# Mall Customer Segmentation using Hierarchical Clustering

## 📌 Project Overview
This project applies **Hierarchical Clustering (Ward’s method)** on the *Mall Customers Dataset* to segment customers based on **Annual Income**, **Spending Score**, and **Age**. The aim is to identify meaningful customer groups to support **targeted marketing strategies**.

## ⚙️ Steps in the Project
1. **Import Libraries** – NumPy, Pandas, Matplotlib, Seaborn, SciPy, Scikit-learn, Plotly  
2. **Load Dataset** – `Mall_Customers.csv`  
3. **Data Preprocessing** – Encoding categorical data, checking missing values, summary statistics  
4. **Exploratory Data Analysis (EDA)** – Distribution plots & correlation heatmap  
5. **Feature Selection** – Income & Spending Score used for clustering  
6. **Dendrogram** – To determine optimal number of clusters  
7. **Hierarchical Clustering** – Agglomerative clustering with 5 clusters  
8. **Visualization**  
   - 2D Scatter plot of Income vs Spending  
   - 3D Plotly visualization with Age, Income, Spending  
9. **Clustered Data** – Cluster label added to dataset  

## 📊 Results
- The dendrogram suggested **5 clusters**.  
- Clusters represent distinct customer groups:
  - **Cluster 0**: High spenders with mid-level income  
  - **Cluster 1**: Budget-conscious shoppers  
  - **Cluster 2**: High-income but low-spending group  
  - **Cluster 3**: Young customers with high spending  
  - **Cluster 4**: Older/low-income low spenders  

## 🛠️ Technologies Used
- Python 3  
- Pandas, NumPy  
- Matplotlib, Seaborn, Plotly  
- SciPy, scikit-learn  

## 🚀 How to Run
1. Clone the repository  
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
