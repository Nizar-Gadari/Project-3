## Optimizing Business Performance through Customer, Sales, and Operations Data Analysis

This project is part of my Data Analytics Portfolio (Project 3) and focuses on leveraging customer, sales, and operational data to enhance business performance. Using the Instacart dataset, the project demonstrates end-to-end analytics capabilities including exploratory data analysis [(EDA)](https://github.com/Nizar-Gadari/Project-3/blob/main/EDA%20using%20Power%20BI.pdf), segmentation, predictive modeling, SQL querying, and Power BI dashboarding.
________________________________________
## 🔍 Objective

The goal of this project is to analyze purchasing behavior, segment customers, predict reorder likelihood, and visualize operational insights. This enables data-driven decision-making to optimize marketing strategies, inventory planning, and overall business performance.
________________________________________
## Business Context

The project addresses key business questions:

* What are the main purchasing patterns and customer segments?
* Which products and departments contribute most to sales?
* How can we predict if a customer will place a new order?
* How can operations be optimized to increase reorder rates and customer retention?
________________________________________
## 📑 Dataset

* **Source:** [Instacart Market Basket Analysis](https://www.kaggle.com/datasets/psparks/instacart-market-basket-analysis/data)
* **Content:**

  * Orders (timing, sequence, and reorders)
  * Products (aisle, department)
  * Customer purchase behavior
________________________________________
## 🔍 Project Steps

1. **Data Exploration and Cleaning**

   * Merge multiple order and product tables
   * Handle missing values and duplicates
   * Feature engineering: reorder ratios, order frequency, average basket size
2. **Descriptive Analysis**

   * Order distribution by day, hour, department
   * Top products and customer behavior metrics
   * Identification of underperforming departments
3. **Customer Segmentation**

   * RFM (Recency, Frequency, Monetary) analysis
   * Clustering customers into behavioral segments
4. **Predictive Modeling**

   * Logistic Regression & Decision Tree models
   * Predicting reorder likelihood per user-product pair
   * Model evaluation with accuracy, precision, and recall
5. **SQL Data Handling**

   * Query optimization for large datasets
   * Segmentation and product-level KPIs via SQL
6. **Dashboard Development (Power BI)**

   * KPIs: number of orders, reorder rate, average basket size
   * Visuals: cluster bar charts, donut charts, line charts, and product trends
   * Interactive filters: customer segments, departments, time period
________________________________________
## 🌍 Dashboard

🔗 Click here to open the interactive analysis in Google Colab:
[Google Colab Notebook](https://colab.research.google.com/drive/14xBzfE8medboLO-NO9E-WdThDmNxZw37) 
________________________________________
## 🎛️ Interactive Dashboard

🔗 Click here to open the Power BI dashboard:
[Project 3 Power BI File](https://github.com/Nizar-Gadari/Project-3/raw/refs/heads/main/Project%203.pbix) 
________________________________________
## 🛠️ Tools Used

* 🐍 Python (EDA, feature engineering, ML modeling)
* 🧪 Google Colab
* 🗄️ SQL (DuckDB / SQLite)
* 📊 Power BI

