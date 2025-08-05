# 🛍️ Customer Segmentation Using K-Means Clustering

## 📌 Task Description

**Task 02:**  
Create a K-means clustering algorithm to group customers of a retail store based on their purchase history.

**Dataset:**  
[Customer Segmentation Dataset on Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

---

## 📂 Project Structure

- **Data Source:** `Mall_Customers.csv`
- **Tools Used:** Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Google Colab
- **Clustering Technique:** K-Means Clustering
- **Feature Scaling:** StandardScaler
- **Evaluation Metric:** Silhouette Score
- **Visualization:** 2D, 3D scatter plots, pie charts, bar charts, heatmaps

---

## 📈 Exploratory Data Analysis

The dataset contains 200 customers with the following attributes:
- Gender
- Age
- Annual Income (k$)
- Spending Score (1–100)

### ✅ Outputs:

- **Age Distribution:**  
  _Image Placeholder_  
  `![Age Distribution](path/to/age_distribution.png)`

- **Gender Distribution:**  
  _Image Placeholder_  
  `![Gender Distribution](path/to/gender_distribution.png)`

- **Annual Income Distribution:**  
  _Image Placeholder_  
  `![Annual Income](path/to/annual_income.png)`

- **Spending Score Distribution:**  
  _Image Placeholder_  
  `![Spending Score](path/to/spending_score.png)`

- **Correlation Heatmap:**  
  _Image Placeholder_  
  `![Heatmap](path/to/correlation_heatmap.png)`

---

## 🤖 Clustering Workflow

### ➤ Features Selected:
- Age  
- Annual Income  
- Spending Score

### ➤ Scaling:
- Standardized using `StandardScaler`

### ➤ Optimal K Determination:
- **Elbow Method**
- **Silhouette Analysis**

### ➤ Clustering Results:
- Optimal clusters found: `K = X`  
- Silhouette Score: `X.XXX`

_Visual Placeholder:_
- `![Elbow Method](path/to/elbow_method.png)`
- `![Silhouette Plot](path/to/silhouette_plot.png)`

---

## 📊 Visualizing Clusters

- **Annual Income vs Spending Score**  
  `![Cluster Plot](path/to/income_vs_spending_cluster.png)`

- **Age vs Spending Score**  
  `![Cluster Plot](path/to/age_vs_spending_cluster.png)`

- **3D Plot (Age, Income, Score)**  
  `![3D Cluster](path/to/3d_cluster.png)`

- **Cluster Size Distribution**  
  `![Size Distribution](path/to/cluster_sizes.png)`

---

## 👥 Customer Personas

| Cluster | Persona                   | Characteristics                                                                 |
|---------|---------------------------|----------------------------------------------------------------------------------|
| 0       | 💰 Budget Conscious        | Low income, low spending                                                        |
| 1       | 🛍️ Trendy Shoppers        | Low income, high spending                                                       |
| 2       | 💎 High Income, Low Spend | High income, conservative spending                                              |
| 3       | 👑 Premium Customers       | High income, high spending                                                      |
| 4       | 🎯 Average Customers       | Mid-range income and spending                                                   |

---

## 📌 Business Recommendations

Each persona is mapped to potential marketing strategies:

### 💰 Budget Conscious
- Target with value deals
- Loyalty programs

### 🛍️ Trendy Shoppers
- Credit options
- Trendy products

### 💎 High Income, Low Spending
- Premium quality and exclusivity
- Emphasize long-term product value

### 👑 Premium Customers
- VIP services
- Luxury promotions

### 🎯 Average Customers
- Balanced promotions
- Focus on satisfaction and retention

---

## 💾 Output Files

- `customer_segments.csv` – Final dataset with assigned cluster labels
- `cluster_summary.csv` – Detailed stats for each cluster

---

## ✅ Conclusion

- Total customers analyzed: **200**
- Optimal clusters: **K = X**
- Age range: **X–Y years**
- Income range: **X–Y k$**
- Spending Score range: **X–Y**

---

## 📌 Next Steps

- Monitor cluster changes over time
- Conduct A/B testing with marketing campaigns
- Gather more data for improved insights

---

## 🏁 Final Output

🎉 **Customer Segmentation Analysis Complete!**

---

> **Note:** Replace `"path/to/image.png"` with the actual path or image links once you upload them (if using GitHub or Jupyter).
