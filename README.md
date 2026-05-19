# Customer Shopping Behavior Analytics

## 📋 Project Overview
This project analyzes customer shopping behavior using Python, SQL Server, and Power BI to uncover purchasing trends, customer segmentation patterns, and sales performance insights.

The workflow covers the complete analytics process, including data cleaning, exploratory data analysis (EDA), SQL-based business analysis, and interactive dashboard creation.

---

## 📊 Dataset
The dataset contains 3,900 customer transaction records with demographic, transactional, and behavioral attributes such as:

- Customer ID
- Age
- Gender
- Item Purchased
- Category
- Purchase Amount (USD)
- Season
- Shipping Type
- Payment Method
- Subscription Status
- Review Rating
- Promo Code Used
- Previous Purchases

---

## 🛠️ Tools & Technologies
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Microsoft SQL Server (T-SQL)
- Power BI Desktop
- Git & GitHub

---

## ⚙️ Project Workflow

### 1. Data Cleaning & Exploration (Python)
- Loaded and explored the raw dataset using Jupyter Notebook.
- Checked for missing values, duplicates, and inconsistent records.
- Performed exploratory analysis to understand customer purchase behavior and feature distributions.

### 2. SQL Business Analysis
The cleaned dataset was imported into SQL Server to answer business-related questions using SQL queries.

Key analyses included:
- Revenue comparison between male and female customers
- Average spending behavior of subscribed vs. non-subscribed customers
- Identification of top-rated and most purchased products
- Customer segmentation into New, Returning, and Loyal groups
- Analysis of discount usage and purchase behavior
- Revenue contribution by age groups
- Purchase comparisons between shipping methods

### 3. Power BI Dashboard
- Built an interactive dashboard to visualize KPIs and customer behavior trends.
- Designed visuals for revenue tracking, category performance, customer segmentation, and subscription analysis.
- Added filters and interactive elements for dynamic exploration.

---

## 📈 Key Insights
- Clothing generated the highest transaction volume among product categories.
- Subscribed customers showed higher average spending compared to non-subscribed customers.
- Repeat buyers were more likely to have active subscriptions.
- Several products maintained high average review ratings while also achieving strong purchase frequency.
- Discount campaigns contributed to increased purchase activity for selected products.

---

## 🖥️ Dashboard Preview

![Customer Behavior Dashboard](Customer%20Behavior%20Dashboard.png)

---

## 🚀 How to Run the Project

### Prerequisites
Install the following tools:
- Python 3.8+
- Jupyter Notebook
- Microsoft SQL Server
- Power BI Desktop

### Steps

1. Clone the repository

```bash
git clone https://github.com/Ali-ops-p/Customer_Behavior_Analyses.git
cd Customer_Behavior_Analyses
```

2. Run the Jupyter Notebook

```bash
jupyter notebook Customer_Shopping_Behavior_Analysis.ipynb
```

3. Import the dataset into SQL Server
- Create a database in SSMS
- Import the cleaned dataset
- Execute the SQL queries

4. Open the Power BI dashboard
- Launch the `.pbix` file in Power BI Desktop

---

## 📂 Project Structure

```text
├── Customer_Shopping_Behavior_Analysis.ipynb
├── Customers Dataset.csv
├── Purchases Analysis sql_queries.sql
├── Customer Behavior Dashboard.png
├── Customer Shopping Dashboard.pbix
└── README.md
```
