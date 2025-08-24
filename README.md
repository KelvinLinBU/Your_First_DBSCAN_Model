# Your First Unsupervised Learning Model — DBSCAN on Mall Customers

This project is part 2 of my YouTube series on unsupervised learning models.  
In this notebook, we use the DBSCAN clustering algorithm to explore customer segmentation with the [Mall Customers dataset](https://www.kaggle.com/datasets/shwetabh123/mall-customers).  

---

## What You’ll Learn
- How DBSCAN works at a high level (dense regions vs. noise)  
- How to prepare data for clustering (feature selection and scaling)  
- How to choose `eps` with a k-distance plot  
- How to tune `min_samples` and understand its effect  
- How to run DBSCAN in Python with scikit-learn  
- How to visualize clusters and noise points  
- How to generate GIFs showing how results change across `eps` and `min_samples`  

---

## Dataset
The dataset contains demographic and behavioral information for mall customers:  
- CustomerID  
- Gender  
- Age  
- Annual Income (k$)  
- Spending Score (1–100)  

For this project, we focus on Annual Income and Spending Score as the main features to cluster.

---

## Requirements
Install dependencies with:

```bash
pip install -r requirements.txt
