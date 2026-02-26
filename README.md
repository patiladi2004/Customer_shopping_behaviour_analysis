Customer Shopping Behavior Analysis

📊 A complete end-to-end data analytics project built using Python, SQL (PostgreSQL), and Power BI to understand customer purchasing patterns and generate business insights.

⭐ Project Overview

This project analyzes 3,900 customer transactions to understand how shoppers behave across different demographics, product categories, seasons, shipping types, and subscription statuses.
The goal is to help businesses make smarter data-driven decisions in marketing, pricing, loyalty programs, and product strategy.

🧰 Tech Stack & Tools Used
Languages

Python (Data Cleaning, EDA, Feature Engineering)

SQL (PostgreSQL) (Business-level Analysis & Insights)

DAX (Power BI) (Dashboard calculations)

Libraries (Python)

pandas

numpy

matplotlib / seaborn (optional)

sqlalchemy

psycopg2

Tools

PostgreSQL – Querying & analytical processing

Power BI – Interactive dashboard creation

Jupyter Notebook / VS Code – Development environment

GitHub – Version control & project documentation

🗂️ Dataset Description

Rows: 3,900

Columns: 18

Includes:

Customer demographics (age, gender, location)

Purchase details (product, category, amount, season)

Behavior indicators (discount applied, shipping type, review rating)

Subscription status and previous purchases

🔍 Key Project Components
1. Data Preprocessing (Python)

Handling missing values

Categorical encoding

Feature engineering (age groups, purchase frequency)

Standardizing column naming

Exporting cleaned data to PostgreSQL

2. SQL Business Analysis

Insights extracted:

Revenue by gender

Most discounted products

Repeat customers vs new customers

High-spending discount users

Top-rated products

Top 3 products by category

Subscriber vs non-subscriber analysis

Revenue by age group

Shipping type impact on purchase amount

3. Power BI Dashboard

Visualized insights through:

Revenue charts

Age-group analysis

Category sales

Subscription trends

Customer segmentation

🎯 Why This Project Was Created

This project was built to:

Understand real-world customer purchasing behavior

Learn end-to-end data analytics workflows

Apply Python + SQL + Power BI together

Generate actionable insights for business decision-making

Strengthen data analytics and BI skills for industry use

📈 Key Insights

Young adults contribute the highest revenue

Express shipping users spend more

Certain products depend heavily on discounts

Loyal customers form the largest segment

Subscribers and non-subscribers behave differently

📦 Project Structure
├── data/                     # raw & cleaned datasets
├── notebooks/                # Python EDA & preprocessing
├── sql/                      # SQL queries used
├── dashboard/                # Power BI files
├── README.md                 # project documentation
└── report/                   # project report
🚀 How to Run the Project

Clone the repository

Install dependencies

Load cleaned data into PostgreSQL

Run SQL queries for insights

Open Power BI dashboard to view results
