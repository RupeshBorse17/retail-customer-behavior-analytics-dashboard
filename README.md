# 🛍️ Retail Customer Behavior Analytics Dashboard

> End-to-End Data Analytics Project using **Python, PostgreSQL, SQL, and Power BI** to analyze customer purchasing behavior and generate business insights for data-driven decision making.

---

## 📌 Project Overview

Retail companies generate thousands of customer transactions every day. Analyzing this data manually is difficult and time-consuming.

This project demonstrates a complete **Data Analytics workflow**, beginning with raw customer purchase data and ending with an interactive **Power BI dashboard** that helps businesses understand customer behavior and improve strategic decision-making.

The project includes:

- Data Cleaning using Python
- PostgreSQL Database
- Business Analysis using SQL
- Interactive Dashboard using Power BI

---

## 🎯 Business Problem

A retail company wants to answer questions such as:

- Which product category generates the highest revenue?
- Which age group spends the most?
- How do subscription customers behave?
- Which shipping methods are preferred?
- Which customers spend above average?
- Which products receive the highest ratings?

The goal is to transform raw customer data into meaningful business insights.

---

# 🛠 Technology Stack

| Technology | Purpose |
|------------|---------|
| Python | Data Cleaning & Feature Engineering |
| Pandas | Data Manipulation |
| PostgreSQL | Database Storage |
| SQL | Business Analysis |
| Power BI | Interactive Dashboard |
| Git & GitHub | Version Control |

---

# 📂 Project Structure

```
Retail-Customer-Behavior-Analytics
│
├── Dataset
│     customer_purchase_pattern.csv
│
├── Python
│     customer_analysis.ipynb
│
├── SQL
│     business_queries.sql
│
├── PowerBI
│     Customer_Behaviour_Dashboard.pbix
│
├── Images
│     dashboard.png
│
├── Report
│     Project_Report.pdf
│
├── README.md
│
└── requirements.txt
```

---

# 📊 Dataset

The dataset contains approximately **3900 customer purchase records**.

### Features

- Customer ID
- Age
- Gender
- Item Purchased
- Category
- Purchase Amount
- Review Rating
- Subscription Status
- Shipping Type
- Payment Method
- Purchase Frequency
- Discount Applied
- Promo Code Used
- Location
- Season

---

# 🧹 Data Preprocessing

Performed the following preprocessing steps:

- Checked missing values
- Renamed columns into snake_case
- Created Age Groups
- Converted purchase frequency into numeric days
- Validated data quality
- Imported cleaned data into PostgreSQL

---

# 🗄 PostgreSQL Database

Database Name

```
customer_behavior
```

Table

```
customer
```

Data was imported into PostgreSQL using **SQLAlchemy**.

---

# 📈 SQL Business Analysis

Performed multiple business analysis queries including:

✅ Revenue by Gender

✅ Revenue by Category

✅ Top 5 Highest Rated Products

✅ High Value Customers

✅ Average Purchase Amount by Shipping Type

✅ Subscription Analysis

✅ Customer Segmentation

✅ Top Spending Customers

✅ Window Functions

✅ Aggregate Functions

---

# 📊 Power BI Dashboard

The interactive dashboard contains:

## KPI Cards

- Average Purchase Amount
- Average Review Rating
- Number of Customers

---

## Interactive Filters

- Subscription Status
- Gender
- Category
- Shipping Type

---

## Dashboard Visualizations

- Revenue by Category
- Sales by Category
- Revenue by Age Group
- Sales by Age Group
- Subscription Distribution

The dashboard is completely **interactive**, allowing users to filter data dynamically based on customer attributes.

---

# 📷 Dashboard Preview

> Add screenshots here

### Dashboard

![Dashboard](Images/dashboard.png)

---

# 📌 Business Insights

The dashboard helps businesses answer questions such as:

- Which category contributes the highest revenue?
- Which customers spend the most?
- Which shipping methods are preferred?
- Which age groups generate maximum sales?
- Which products receive better customer ratings?
- How do subscription customers compare with non-subscription customers?

---

# 💼 Business Impact

This solution enables businesses to:

- Improve customer segmentation
- Monitor revenue trends
- Increase marketing effectiveness
- Understand customer purchasing behavior
- Make data-driven business decisions
- Improve overall business performance

---

# 🚀 Future Enhancements

Future improvements include:

- AI-generated business summaries using Gemini API
- Predictive sales forecasting
- Customer churn prediction
- Power BI Service deployment
- Automated data refresh
- Real-time dashboards

---

# ▶️ How to Run

### Clone Repository

---

### Install Dependencies

```bash
pip install pandas numpy sqlalchemy psycopg2
```

---

### Import Dataset

Run the Jupyter Notebook to clean the dataset.

---

### Load into PostgreSQL

Use SQLAlchemy to import the cleaned data.

---

### Open Power BI

Open

```
Customer_Behaviour_Dashboard.pbix
```

to explore the dashboard.

---

# 📚 Skills Demonstrated

- Data Cleaning
- Data Analysis
- SQL
- PostgreSQL
- Power BI
- Dashboard Design
- Data Visualization
- Business Intelligence
- Analytical Thinking
- Problem Solving

---

