# 🛍 Customer Segmentation Using K-Means Clustering

## 📌 Task Description

**Task 02:**  
Create a K-means clustering algorithm to group customers of a retail store based on their purchase history.

**Dataset:**  
[Customer Segmentation Dataset on Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

---

## 📂 Project Structure

- **Data Source:** Mall_Customers.csv  
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

## 🤖 Clustering Workflow

### ➤ Features Selected:
- Age  
- Annual Income  
- Spending Score

### ➤ Scaling:
- Standardized using StandardScaler

### ➤ Optimal K Determination:
- **Elbow Method**  
- **Silhouette Analysis**

### ➤ Clustering Results:
- Optimal clusters found: **K = 5**  
- Silhouette Score: **0.5539**


---

## 📊 Visualizing Clusters

- **Annual Income vs Spending Score**  
  ![Income vs Spending](https://github.com/Vijay1097/Prodigy_ML_02/blob/main/Annual_Income%20vs%20Spending_score.jpg)

- **Age vs Spending Score**  
  ![Age vs Spending](https://github.com/Vijay1097/Prodigy_ML_02/blob/main/Age_vs_Spending_Score.jpg)

- **3D Plot (Age, Income, Score)**  
  ![3D Cluster](https://github.com/Vijay1097/Prodigy_ML_02/blob/main/3D_Plot.jpg)

- **Cluster Size Distribution**  
  ![Cluster Sizes](https://github.com/Vijay1097/Prodigy_ML_02/blob/main/Cluster_Size_Distribution.jpg)

---

## 👥 Customer Personas

| Cluster | Persona                   | Characteristics                                                                 |
|---------|---------------------------|----------------------------------------------------------------------------------|
| 0       | 💰 Budget Conscious        | Low income, low spending                                                        |
| 1       | 🛍 Trendy Shoppers        | Low income, high spending                                                       |
| 2       | 💎 High Income, Low Spend | High income, conservative spending                                              |
| 3       | 👑 Premium Customers       | High income, high spending                                                      |
| 4       | 🎯 Average Customers       | Mid-range income and spending                                                   |

---

## 📌 Business Recommendations

Each persona is mapped to potential marketing strategies:

### 💰 Budget Conscious
- Target with value deals  
- Loyalty programs  

### 🛍 Trendy Shoppers
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
- Optimal clusters: **K = 5**  
- Age range: **18–70 years**  
- Income range: **15k–137k $**  
- Spending Score range: **1–100**

---

## 📌 Next Steps

- Monitor cluster changes over time  
- Conduct A/B testing with marketing campaigns  
- Gather more data for improved insights  

---

## 🏁 Final Output

🎉 *Customer Segmentation Analysis Complete!*

---

> 💡 **Note:** All image links are sourced from the public GitHub repo. If the image URLs change or are updated, ensure the new paths are reflected here.
