# Customer Segmentation using K-Means Clustering

## Overview
This project demonstrates how **K-Means clustering**, an unsupervised machine learning algorithm,
can be used to segment customers based on their similarities.

The objective is to identify natural groupings in the data without using any labeled outputs.

---

## Concepts Covered
- Unsupervised Learning
- Clustering
- K-Means Algorithm
- Elbow Method
- Data Visualization

---

## Dataset
A synthetic customer dataset is generated using `make_blobs` from scikit-learn.
Each data point represents a customer with different characteristics.

---

## Methodology
1. Generate customer data  
2. Visualize the raw data  
3. Apply the Elbow Method to determine the optimal number of clusters  
4. Train the K-Means model  
5. Visualize and interpret the resulting clusters  

---

## Tools & Libraries
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  
- Jupyter Notebook / Google Colab  

---

## Results
The K-Means algorithm successfully segments customers into distinct clusters.
The Elbow Method suggests an optimal value of **K = 4**, which produces clearly separated groups.

---

## Conclusion
This project highlights how unsupervised learning techniques like K-Means can be applied
to discover patterns in data and support business decisions such as customer segmentation
and targeted strategies.
