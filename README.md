# 🛍️ Customer Segmentation — K-Means Clustering

### SkillCraft Technology | Machine Learning Internship — Task 2

## 📌 Overview
This project implements a **K-Means Clustering** algorithm to segment retail customers based on their purchase history, using:
- Annual Income
- Purchase Frequency
- Average Spend Per Purchase

The dataset is **synthetically generated** to simulate realistic customer behavior across different spending segments.

## 🛠️ Tools & Libraries
- Python
- Google Colab
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## 📊 Workflow
1. Generated a synthetic dataset of 400 customers across varied income/spending patterns
2. Performed exploratory data analysis with pair plots
3. Scaled features using `StandardScaler`
4. Used the **Elbow Method** to determine the optimal number of clusters
5. Trained a **K-Means** model and assigned cluster labels
6. Visualized clusters and profiled each segment
7. Predicted the segment of a new customer

## 📈 Results
- Optimal number of clusters (k): **4**
- Segments identified: Budget Shoppers, Regular Customers, High-Value Occasional Buyers, VIP Customers

## 📊 Elbow Method
![Elbow Method](elbow_method.png)

## 📷 Cluster Visualization
![Customer Clusters](clusters.png)

## 📁 Repository Contents
| File | Description |
|------|-------------|
| `customer_segmentation.ipynb` | Main Colab notebook |
| `customer_segments.csv` | Dataset with assigned cluster labels |
| `pairplot.png` | Feature relationships |
| `elbow_method.png` | Elbow method for optimal k |
| `clusters.png` | Final cluster visualization |

## 🔍 What I Learned
- Importance of feature scaling for distance-based algorithms
- Using the Elbow Method to choose cluster count
- Interpreting unsupervised learning results for business insights
- Profiling customer segments for targeted marketing

## 🔗 About This Internship
This task is part of my **Machine Learning Internship at SkillCraft Technology**.
