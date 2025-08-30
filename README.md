# 🐧 Penguins Clustering Analysis

This project uses **K-Means clustering** to explore patterns in the **Palmer Penguins dataset**.  
The goal is to group penguins based on physical measurements and other features, providing insights into species clustering without labels.

---

## 📌 Project Overview

- Dataset: Palmer Penguins (features include culmen length/depth, flipper length, body mass, sex, and species)
- Goal: Use unsupervised learning (K-Means) to identify natural clusters
- Approach:
  1. One-hot encode categorical features (`sex`)
  2. Scale numerical features
  3. Determine optimal number of clusters using the elbow method
  4. Fit K-Means and assign cluster labels
  5. Visualize clusters and analyze mean feature values per cluster

---

## 🛠️ Tech Stack

- **Python** – data analysis and modeling  
- **Pandas** – data manipulation  
- **Matplotlib** – visualization  
- **scikit-learn** – K-Means clustering and scaling  

---

## 📈 Key Steps

1. **Data Preprocessing**  
   - Encode categorical columns  
   - Scale numerical features

2. **Determine Optimal Clusters**  
   - Elbow method using inertia plot to select `k`

3. **K-Means Clustering**  
   - Fit K-Means on scaled features  
   - Assign cluster labels to dataset

4. **Visualization & Analysis**  
   - Scatter plot of clusters (culmen length vs. depth)  
   - Group statistics per cluster

---
