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
- Python (Pandas, SQLAlchemy)
- Jupyter Notebook
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
- Category Performance: Clothing is the primary revenue and volume driver, consistently generating both the highest overall revenue and the largest transaction volume among all product categories.
- Subscription Behavior: Interestingly, non-subscribed customers exhibited a slightly higher average spending pattern ($59.87) compared to subscribed customers ($59.49).
- Customer Satisfaction: The dataset maintains a healthy overall Average Review Rating of 3.75, indicating stable baseline customer satisfaction across demographics.
- Demographic Drivers: * For the broader customer base, Young Adults lead in both total revenue and transaction volume.
  - Among subscribed male customers, Middle-aged users emerge as the highest revenue-generating segment.
- Purchase Frequency: Customers with active subscriptions demonstrate a more consistent history of high-frequency purchases compared to non-subscribers.
- Product Optimization: High-volume items within the Clothing and Footwear segments successfully maintain strong customer satisfaction, balancing high purchase frequency with above-average review ratings.
- Promotional Impact: The application of discounts and promotional codes shows a direct positive correlation with increased transaction volumes across top product categories.

---

## 🖥️ Dashboard Preview

![Customer Behavior Dashboard](Customer%20Behavior%20Dashboard.png)

---

## 🚀 How to Run the Project

### Prerequisites
Ensure you have the following installed:
- Python 3.8+
- Jupyter Notebook or JupyterLab
- Microsoft SQL Server & SQL Server Management Studio (SSMS)
- Power BI Desktop

### Setup Instructions

1. Clone the repository
Open your terminal or command prompt, clone the repository using the git clone command for Ali-ops-p/Customer_Behavior_Analyses, and navigate into the project folder.

2. Install Python Dependencies
Install the required Python packages by running the standard pip install command for the requirements.txt file to ensure your environment is ready.

3. Run the Data Analysis Notebook
Launch Jupyter in your terminal and open the Customer_Shopping_Behavior_Analysis.ipynb file to view the data cleaning and exploration process.

4. Import the dataset into SQL Server
- Create a database in SSMS
- Import the cleaned dataset
- Execute the SQL queries

5. Open the Power BI dashboard
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
