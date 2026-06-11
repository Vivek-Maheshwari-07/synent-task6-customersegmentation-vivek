# Customer Segmentation Using K-Means Clustering

## Overview

Customer segmentation is an important business strategy that helps organizations understand customer behavior and create targeted marketing campaigns. This project uses the K-Means Clustering algorithm to segment mall customers based on their annual income and spending score.

The objective is to identify distinct customer groups and generate business insights that can support better decision-making and customer relationship management.

---

## Dataset Information

**Dataset:** Mall Customer Segmentation Dataset

The dataset contains information about mall customers, including:

- Customer ID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Google Colab

---

## Project Workflow

### 1. Data Loading
- Imported the dataset using Pandas.
- Explored the structure and data types.

### 2. Data Cleaning
- Checked for missing values.
- Checked for duplicate records.
- Verified data quality before analysis.

### 3. Exploratory Data Analysis (EDA)
- Gender Distribution Analysis
- Age Distribution Analysis
- Annual Income Distribution
- Spending Score Distribution
- Income vs Spending Relationship

### 4. Elbow Method
- Applied the Elbow Method to determine the optimal number of clusters.
- Selected **5 clusters** based on the WCSS curve.

### 5. K-Means Clustering
- Applied K-Means Clustering on:
  - Annual Income (k$)
  - Spending Score (1-100)
- Generated customer segments and visualized cluster centroids.

### 6. Cluster Analysis
- Analyzed each cluster based on spending behavior and income level.
- Generated business-oriented customer categories.

---

## Customer Segments Identified

### Premium Customers
- High Income
- High Spending

### Careful Customers
- High Income
- Low Spending

### Impulsive Customers
- Low Income
- High Spending

### Budget Customers
- Low Income
- Low Spending

### Regular Customers
- Moderate Income
- Moderate Spending

---

## Key Insights

- Five distinct customer groups were successfully identified.
- Premium customers represent the most valuable segment for the business.
- High-income customers with low spending provide an opportunity for targeted marketing campaigns.
- Budget customers are likely to respond better to discounts and promotional offers.
- Regular customers form the largest customer base and contribute to stable revenue generation.

---

## Results

The K-Means Clustering algorithm successfully segmented customers into meaningful groups based on their purchasing behavior and income levels.

These insights can help businesses:
- Improve customer targeting
- Design personalized marketing campaigns
- Increase customer engagement
- Enhance profitability

---

## Conclusion

This project demonstrates how unsupervised machine learning techniques can be used to solve real-world business problems.

By applying K-Means Clustering, customer behavior patterns were identified and transformed into actionable business insights. The project highlights the importance of data-driven decision-making in modern marketing strategies.

---

## Author

**Vivek**

Data Science Internship Project – Synent Technologies
