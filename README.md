# Customer Segmentation Using K-Means Clustering

## Overview

Customer Segmentation is a machine learning project that groups customers into distinct categories based on their purchasing behavior and income patterns. The project applies the K-Means Clustering algorithm to identify similarities among customers and create meaningful customer segments.

The primary objective is to demonstrate how unsupervised machine learning techniques can be used to analyze customer characteristics and support data-driven business strategies.

This project was developed using Python in Google Colab and utilizes a sample customer dataset for educational and demonstration purposes.

---

## Problem Statement

Businesses often interact with customers who have different purchasing behaviors and financial backgrounds. Understanding these differences is essential for designing targeted marketing campaigns and improving customer engagement.

This project addresses the problem by automatically grouping customers with similar spending habits and income levels into distinct clusters using machine learning.

---

## Objectives

* Analyze customer-related data.
* Identify similarities among customers.
* Segment customers into meaningful groups.
* Visualize customer clusters effectively.
* Demonstrate the practical application of unsupervised machine learning.

---

## Dataset Information

A sample customer dataset was created and used for demonstration purposes.

### Features Used

* Customer ID
* Age
* Annual Income (k$)
* Spending Score (1–100)

For clustering, the following features were selected:

* Annual Income (k$)
* Spending Score (1–100)

These attributes help identify customer purchasing behavior and spending patterns.

---

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Methodology

### 1. Data Preparation

Customer information was organized into a structured dataset containing demographic and spending-related attributes.

### 2. Feature Selection

Relevant features were selected for segmentation:

* Annual Income
* Spending Score

### 3. Customer Segmentation

The K-Means Clustering algorithm was applied to group customers based on similarities in spending behavior and income levels.

### 4. Cluster Visualization

Scatter plots were used to visualize the generated customer segments and understand the distribution of different customer groups.

---

## Machine Learning Algorithm

### K-Means Clustering

K-Means is an unsupervised machine learning algorithm that partitions data into multiple clusters based on feature similarity.

The algorithm works by:

1. Selecting the number of clusters.
2. Assigning data points to the nearest centroid.
3. Updating cluster centroids.
4. Repeating the process until convergence.

In this project, customers were grouped into **three distinct clusters** based on their income and spending characteristics.

---

## Key Features

* Customer behavior analysis
* Income-based segmentation
* Spending pattern analysis
* K-Means clustering implementation
* Customer cluster visualization
* Unsupervised machine learning workflow

---

## Results

The K-Means model successfully segmented customers into distinct groups based on their spending behavior and annual income.

The generated customer segments can help businesses:

* Understand customer preferences
* Identify high-value customers
* Improve marketing strategies
* Support business decision-making

---

## Applications

### Retail Industry

Customer targeting and personalized marketing.

### E-Commerce Platforms

Recommendation systems and customer profiling.

### Banking and Finance

Customer classification and service optimization.

### Marketing Analytics

Behavior-based campaign planning.

---

## Future Enhancements

* Use larger real-world customer datasets.
* Determine the optimal number of clusters using the Elbow Method.
* Apply advanced clustering techniques.
* Build an interactive customer analytics dashboard.
* Deploy the model as a web application.

---

## Project Structure

```text
Customer-Segmentation-Project/
│
├── Customer_Segmentation_Project.ipynb
├── README.md
└── Visualizations/
```

---

## Learning Outcomes

This project helped strengthen knowledge in:

* Data Analysis
* Data Visualization
* Customer Analytics
* Machine Learning
* Unsupervised Learning
* K-Means Clustering
* Business Intelligence

---

## Author

**Naveena N**
B.Tech Artificial Intelligence and Data Science

---

## License

This project is developed for educational and learning purposes.
