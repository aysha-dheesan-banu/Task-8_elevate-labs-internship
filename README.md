# K-Means Clustering - Mall Customer Segmentation

This project performs unsupervised learning using **K-Means Clustering** on the Mall Customers dataset to segment customers based on their annual income and spending score.

## 🔍 Objective
Perform clustering to identify distinct groups of customers to help understand spending patterns.

## 🧰 Tools & Libraries
- Python
- Pandas
- Matplotlib
- Scikit-learn

## 📁 Dataset
- **File**: `Mall_Customers.csv`
- **Features Used**:
  - Annual Income (k$)
  - Spending Score (1-100)

## 🧪 Steps Followed
1. Load and explore the dataset.
2. Select relevant numerical features.
3. Standardize the features using `StandardScaler`.
4. Use the **Elbow Method** to determine the optimal number of clusters (`k`).
5. Apply **K-Means Clustering**.
6. Visualize the resulting clusters and centroids.
7. Evaluate clustering quality using the **Silhouette Score**.

## 📈 Result
- **Optimal number of clusters**: 5
- **Silhouette Score**: ~0.55
- Clear visual separation of customer segments based on spending behavior.

## 📌 How to Run
```bash
pip install pandas matplotlib scikit-learn
python kmeans_clustering.py
