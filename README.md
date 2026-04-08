# Customer Segmentation using K-Means Clustering

## Project Overview

This project focuses on customer segmentation using unsupervised machine learning techniques. By applying K-Means clustering to credit card usage data, the goal is to identify distinct customer groups and derive actionable insights for targeted marketing strategies, risk management, and customer value optimization.

## About the Dataset

The dataset contains behavioral data for approximately 9,000 active credit card customers over a period of six months. Each row represents a customer and includes 18 features capturing their financial activity, such as:

Balance and credit limit
Purchases (one-off and installments)
Cash advance usage
Payment behavior
Transaction frequency

This dataset enables deep analysis of customer spending patterns and financial habits.

## Objectives
- Perform data cleaning and preprocessing
- Apply feature transformation and scaling
- Identify the optimal number of clusters
- Segment customers using K-Means clustering
- Interpret clusters into business-friendly segments
- Provide insights for decision-making

## Customer Segments

| Cluster | Segment Name           | Description                                                                 |
|--------|------------------------|-----------------------------------------------------------------------------|
| 0      | Cash Advance Users     | High reliance on cash withdrawals, low purchases (high risk)               |
| 1      | Installment Spenders   | Active users preferring installment purchases                              |
| 2      | Premium Customers      | High spending, high credit limit, most valuable segment                    |
| 3      | Responsible Users      | Low balance, frequent full payments (low risk)                             |
| 4      | Low Engagement Users   | Infrequent usage, growth opportunity                                       |
| 5      | High Debt Users        | High balance and cash advance usage (very high risk)                       |

## Key Insights
- 🔴 A significant portion of customers rely on cash advances, indicating potential risk
- 💰 Premium customers contribute the highest value but are fewer in number
- 📉 Responsible users are the smallest segment
- 📈 Opportunity exists to convert low engagement users into active customers
- 📊 Visualizations

## Technologies Used
Python
Pandas, NumPy
Scikit-learn
Matplotlib, Seaborn
### How to Run
Clone the repository:
```
git clone https://github.com/your-username/your-repo-name.git
```
