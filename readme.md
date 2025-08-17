# E-Commerce Customer Analysis: EDA, Segmentation, and Lookalike Modeling

## Overview
This project analyzes e-commerce data to uncover insights into customer behavior, product performance, and transaction trends. It includes exploratory data analysis (EDA), customer segmentation using KMeans clustering, and a lookalike model for targeted marketing. The goal is to provide actionable insights for improving customer retention, boosting revenue, and enabling data-driven decision-making.

## Objectives
1. **Analyze Customer Behavior**: Identify spending patterns and regional trends.
2. **Evaluate Product Performance**: Determine top-performing products and categories.
3. **Discover Trends**: Analyze sales and transaction patterns over time.
4. **Develop Models**:
   - **Customer Segmentation**: Group customers into meaningful clusters using KMeans.
   - **Lookalike Model**: Recommend similar customers for targeted marketing using cosine similarity.

## Data Sources
The project uses three datasets:
- **Customers.csv**: 200 rows, 4 columns (CustomerID, CustomerName, Region, SignupDate).
- **Products.csv**: 100 rows, 4 columns (ProductID, ProductName, Category, Price).
- **Transactions.csv**: 1000 rows, 7 columns (TransactionID, CustomerID, ProductID, TransactionDate, Quantity, TotalValue, Price).

*Note*: Due to privacy, raw data is not shared. Sample data or instructions to generate synthetic data are in the `data/` folder (to be added).

## Key Findings
- **EDA**: Identified top products (e.g., 'Product A' contributes significantly to revenue), regional performance (Region X generates 50% of revenue), and trends like Q4 signup peaks.
- **Clustering**: Optimal 3 clusters identified with a Davies-Bouldin Index of 0.7686 and Silhouette Score of 0.4148. Cluster sizes: {2: 91, 1: 70, 0: 38}.
- **Lookalike Model**: Generated recommendations for similar customers using cosine similarity, saved in `reports/lookalike.csv`.

