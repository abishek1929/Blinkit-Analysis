# BlinkIT Product Segmentation Using K-Means Clustering

## 1. Project Overview

This project focuses on analyzing BlinkIT grocery outlet data and segmenting products based on their sales performance, visibility, and customer ratings using Machine Learning.

K-Means Clustering is used to group similar product-outlet records into three different clusters. This helps identify sales patterns and understand product performance.

## 2. Objectives

- Analyze BlinkIT grocery sales data.
- Understand product visibility and sales performance.
- Identify patterns in product ratings.
- Apply K-Means Clustering to segment product records.
- Interpret the characteristics of each cluster.

## 3. Dataset Description

**Dataset:** BlinkIT Grocery Data.csv

The dataset contains information about grocery products and outlets.

Important columns used in this project:

| Column | Description |
|---|---|
| Item Visibility | Visibility of the product in the outlet |
| Sales | Product sales value |
| Rating | Customer rating of the product |

## 4. Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 5. Project Workflow

1. Import the required Python libraries.
2. Load the BlinkIT dataset.
3. Perform data exploration and analysis.
4. Handle missing values.
5. Select important numerical features.
6. Apply StandardScaler for feature scaling.
7. Implement K-Means Clustering.
8. Divide the data into three clusters.
9. Analyze and interpret the cluster results.

## 6. Machine Learning Algorithm

**K-Means Clustering**

K-Means is an unsupervised machine learning algorithm that groups similar data points into clusters based on their features.

In this project:
- Number of clusters (K): 3
- Random State: 42
- Initialization: K-Means++

## 7. Cluster Results

A total of 8,523 product-outlet records were grouped into three clusters.

| Cluster | Records | Average Sales | Average Rating |
|---|---:|---:|---:|
| Cluster 0 | 3,767 | 86.35 | 4.10 |
| Cluster 1 | 4,081 | 192.09 | 4.11 |
| Cluster 2 | 675 | 137.00 | 2.38 |

### Cluster Interpretation

- **Cluster 0:** Records with lower average sales and good customer ratings.
- **Cluster 1:** Records with higher average sales and good customer ratings.
- **Cluster 2:** Records with moderate average sales but comparatively lower customer ratings.

## 8. Key Findings

- Cluster 1 contains the highest number of records and has the highest average sales.
- Cluster 0 has lower average sales but maintains good customer ratings.
- Cluster 2 has comparatively low customer ratings and may need further investigation.
- Clustering helps identify different product performance patterns.

## 9. Project Files

- `BlinkIT Grocery Data.csv` – Original dataset.
- `BlinkIT_Product_Clusters.csv` – Dataset containing assigned cluster labels.
- `BlinkIT_Segmentation_Analysis.ipynb` – Jupyter Notebook containing the analysis and clustering implementation.
- `README.md` – Project documentation.

## 10. Conclusion

This project demonstrates how K-Means Clustering can be applied to grocery retail data to identify different product performance groups. The results provide useful insights into sales patterns and customer ratings, which can support better inventory management and business decision-making.

## 11. Future Enhancements

- Build an interactive sales and segmentation dashboard.
- Perform outlet-wise and product-category analysis.
- Experiment with different clustering algorithms.
- Develop recommendations for improving low-rated product performance.
