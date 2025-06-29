📊 Customer Segmentation & Sales Analysis (RFM + K-Means)
This project applies RFM analysis and K-Means clustering on the Online Retail II dataset (UCI) to segment customers based on purchasing behavior. The goal is to identify meaningful customer groups for targeted marketing and retention strategies.

🔧 Tools & Libraries Used
Python

Pandas – Data cleaning and RFM feature engineering

Scikit-learn – K-Means clustering and scaling

Matplotlib & Seaborn – Data visualization

🛠️ Key Steps
Data Cleaning

Removed null Customer IDs, cancelled transactions, and invalid values

Converted date columns to datetime format

Filtered for completed transactions only

RFM Feature Creation

Calculated Recency, Frequency, and Monetary values for each customer

Created an RFM table for clustering

K-Means Clustering

Scaled RFM values and used the Elbow Method to choose optimal clusters

Applied K-Means to segment customers into 4 groups:

⭐ Super VIPs

🟢 Loyal Customers

🟡 Moderate Regulars

🔴 At-Risk Customers

Visualization & Insights

Plotted cluster distributions and key trends

Provided actionable business recommendations for marketing, product focus, and customer retention

💡 Business Outcomes
Enables targeted campaigns for different customer segments

Supports data-driven decision-making for sales and marketing

Improves customer retention and revenue growth
