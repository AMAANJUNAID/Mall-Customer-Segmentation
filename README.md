
# 🛍️ Mall Customer Segmentation with K-Means 📊

This project segments customers into meaningful groups using K-Means clustering, enabling businesses to analyze customer behavior and improve their strategies. 🚀

## Dataset 📁
- **Age**: Customer's age
- **Annual Income (k$)**: Yearly income in thousands of dollars
- **Spending Score (1-100)**: Behavior and loyalty metric
- **Gender**: Categorical feature

## Workflow 🛠️
1. **Preprocessing**: Fill missing values and encode categorical data.
2. **Feature Scaling**: Standardize `Age`, `Annual Income`, and `Spending Score`.
3. **Clustering**:
   - Determine optimal clusters using 🪓 **Elbow Method** (SSE).
   - Validate with 💡 **Silhouette Scores**.
4. **Visualization**:
   - Scatter plots 🖼️, heatmaps 🌡️, and boxplots 📦 for insights.
5. **Output**:
   - Save clustered data in `clustered_customers.csv`. 💾

Dependencies 📦
Python 3.6+
Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn.


## Results 📉
- Optimal clusters: **5** ✅
- Insights available via visuals & stored results.

