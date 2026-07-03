# Customer Segmentation Using Unsupervised Learning

## Project Overview

This project uses unsupervised machine learning to segment customers based on their purchasing behavior. The workflow includes data preprocessing, feature engineering, dimensionality reduction using PCA, K-Means clustering, and business interpretation of customer segments.

---

## Objectives

* Preprocess and clean customer transaction data.
* Engineer RFM and behavioral features.
* Reduce dimensionality using PCA.
* Determine the optimal number of clusters.
* Segment customers using K-Means.
* Generate business insights from customer groups.

---

## Dataset

* **Dataset:** `Product-Sales-Region.xlsx`
* **Rows:** 1,500
* **Columns:** 19

The dataset includes customer, product, sales, payment, and transaction information.

---

## Workflow

1. Data Cleaning & Preprocessing
2. Feature Engineering (RFM + Behavioral Features)
3. Feature Scaling using StandardScaler
4. PCA for Dimensionality Reduction
5. Optimal Cluster Selection (Elbow & Silhouette Methods)
6. Customer Segmentation using K-Means
7. Business Interpretation of Customer Segments

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn
* Kneed
* Jupyter Notebook

---
## Project Structure

```text
Project 3/
│
├── Ds_Project3_Customer_Segmentation.ipynb
└── Readme.md
```
---
## Visualizations

* PCA Scree Plot
* PCA Loading Heatmap
* Elbow Plot
* Silhouette Score Plot
* Customer Cluster Visualization
* Cluster Profiles
* Payment Method Distribution

---

## Results

The project successfully grouped customers into distinct segments based on purchasing behavior. These insights can support personalized marketing, customer retention, loyalty programs, and business decision-making.

---

## Future Improvements

* Deploy the segmentation pipeline using Streamlit.
* Compare K-Means with other clustering algorithms.
* Update the model periodically as customer behavior changes.

---

## Author

**Kirshna Parshad**

Completed as part of a Data Science Internship to demonstrate practical skills in customer segmentation, dimensionality reduction, and unsupervised machine learning.
