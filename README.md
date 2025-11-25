# 🛍️ Customer Behavior Analysis — SQL + Python + Power BI

This project analyzes customer shopping behavior using Python for data cleaning, SQL for business insights, and Power BI for dashboard storytelling. It is designed to be a strong portfolio project for data analyst and data science job roles.

## 📁 Dataset

File name:
customer_shopping_behavior_cleaned.csv

Location in repo:
/data/customer_shopping_behavior_cleaned.csv

The dataset is already cleaned and structured for direct analysis in Jupyter Notebook.

It is loaded in the notebook using a relative path:
../data/customer_shopping_behavior_cleaned.csv


## 📊 Business Questions Answered using SQL
1. Which gender generates more revenue?
2. Do customers using discounts spend more than average?
3. Top 5 products by customer rating?
4. Which shipping type results in higher spending?
5. Who spends more: subscribers or non-subscribers?
6. Which products have highest discount adoption?
7. Customer segmentation: new vs returning vs loyal
8. Top 3 products in each category
9. Are repeat buyers more likely to be subscribers?
10. Which age group contributes the highest revenue?

All SQL queries:  
sql/retail_analysis_queries.sql

## 🧼 Python Work (Cleaning)
• Missing value handling  
• Data type correction  
• Age group feature  
• Customer segmentation support  
Notebook:  
python/customer_cleaning.ipynb

## 📈 Power BI Dashboard
Shows:
• Total Revenue & Avg Purchase  
• Subscribers vs Non-Subscribers Revenue  
• Revenue by Category  
• Age Group Insights  
• Best Products by Rating  

## 📊 Power BI Dashboard

Screenshots of the interactive dashboard:

![Dashboard](powerbi/screenshots/dashboard_1.png)

Additional views available in:
`/powerbi/screenshots/`


## 🧰 Tech Stack
| Tool | Purpose |
|------|---------|
| Python | Data Cleaning |
| MySQL | Analytical Queries |
| Power BI | Data Visualization |
| GitHub | Portfolio Hosting |

## 📂 Project Structure
customer-behavior-analysis-sql-python-powerbi/
│
├── sql/
│   └── retail_analysis_queries.sql
│
├── python/
│   └── customer_cleaning.ipynb
│
├── images/
│   └── dashboard.png
│
└── README.md

## 🚀 How to Use
Clone the repo  
Run SQL queries in MySQL  
Open notebook for cleaning  
Open dashboard in Power BI

## 🔮 Future Improvements
• Customer Lifetime Value (CLV)  
• Churn prediction model  
• Real-time sales analysis

## 📩 Contact
Email: YOUR_EMAIL  
LinkedIn: YOUR_LINKEDIN
