# E-Commerce Business Performance Analysis

## Project Overview

This project is an end-to-end E-Commerce Business Analysis project developed using **Python and Microsoft Power BI**.

The main goal of this project was to understand how an e-commerce business is performing across different areas such as sales, revenue, customers, products, sellers, delivery, payments, and customer satisfaction.

I worked with multiple datasets and transformed the raw data into a structured analytical dataset. After cleaning and preparing the data, I performed exploratory data analysis and created an interactive Power BI dashboard to present the business performance in an easy-to-understand way.

The dashboard is designed to help business users quickly understand what is happening in the business and explore different areas using filters and interactive visualizations.

---

## Dashboard Preview

### Executive Overview

<img width="911" height="400" alt="Screenshot 2026-10-01 171131" src="https://github.com/user-attachments/assets/dd980b74-0fd5-4826-ab99-dc7a34cb3989" />


The Executive Overview provides a high-level view of the overall business performance.

Key KPIs include:

- Total Revenue: **15.84M**
- Total Customers: **96K**
- Total Orders: **99K**
- Average Order Value: **159.33**
- Average Delivery Days: **12.01**
- Average Review Score: **4**

The page also includes revenue by customer state, order status, revenue by category, monthly orders, and yearly revenue.

---

## Business Problem

E-commerce businesses generate a large amount of data from orders, customers, products, payments, sellers, reviews, and deliveries.

Looking at these datasets separately makes it difficult to understand the overall business performance.

This project was created to answer important business questions such as:

- How much revenue is the business generating?
- How many customers and orders does the business have?
- How is revenue changing over time?
- Which product categories generate more revenue?
- Which states have more customers?
- What is the average order value?
- How long does it take to deliver orders?
- How many orders are delayed or cancelled?
- How are sellers performing?
- What is the overall customer satisfaction?
- Which categories receive more positive or negative reviews?
- Is there a relationship between delivery performance and customer satisfaction?

---

## Project Objectives

The main objectives of this project were:

- Clean and prepare the raw e-commerce data.
- Combine multiple datasets into a usable analytical dataset.
- Perform exploratory data analysis.
- Create meaningful business KPIs.
- Analyze sales and revenue performance.
- Understand customer and product behavior.
- Analyze delivery and seller performance.
- Analyze customer reviews and satisfaction.
- Build an interactive Power BI dashboard.
- Convert raw data into meaningful business insights.

---

## Dataset

The project uses multiple e-commerce datasets covering different parts of the business.

The datasets include:

- Customers
- Orders
- Order Items
- Products
- Sellers
- Payments
- Reviews
- Geolocation
- Product Category Translation

These datasets were cleaned and combined to create a master dataset that could be used for business analysis.

The final analysis contains information related to:

- Customers
- Orders
- Products
- Categories
- Payments
- Sellers
- Reviews
- Delivery
- Customer locations
- Order status

---

## Tools and Technologies

### Data Analysis

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

### Business Intelligence

- Microsoft Power BI
- Power Query
- DAX
- Data Modeling
- Interactive Visualizations

---

# Project Workflow

```text
Raw E-Commerce Data
        |
        v
Data Cleaning
        |
        v
Data Transformation
        |
        v
Dataset Integration
        |
        v
Feature Engineering
        |
        v
Exploratory Data Analysis
        |
        v
Business KPI Development
        |
        v
Power BI Data Modeling
        |
        v
DAX Measures
        |
        v
Interactive Dashboard
        |
        v
Business Insights
```

---

# Data Cleaning and Preparation

Before building the dashboard, the raw datasets were cleaned and prepared for analysis.

The main data preparation activities included:

- Checking the structure of each dataset.
- Checking missing values.
- Removing or handling inconsistent records.
- Converting date and time columns into appropriate formats.
- Creating year, month, and quarter fields.
- Combining related datasets.
- Translating product category names.
- Preparing customer and seller information.
- Calculating delivery duration.
- Calculating delivery delays.
- Preparing revenue-related fields.
- Creating fields required for business analysis.

---

# Power BI Dashboard

The Power BI report is divided into different pages, with each page focusing on a specific part of the business.

The main dashboard pages are:

1. Executive Overview
2. Sales & Revenue Performance
3. Customer & Product Intelligence
4. Delivery & Seller Performance
5. Customer Experience & Business Improvement

---

# 1. Executive Overview

The Executive Overview provides a high-level view of the overall business performance.

The main KPIs displayed on this page are:

- Total Revenue: **15.84M**
- Total Customers: **96K**
- Total Orders: **99K**
- Average Order Value: **159.33**
- Average Delivery Days: **12.01**
- Average Review Score: **4**

This page also includes:

- Revenue by Customer State
- Total Orders by Order Status
- Total Revenue by Product Category
- Total Orders by Month
- Total Revenue by Year

The purpose of this page is to give management a quick overview of the business and allow users to move from high-level KPIs into geographic, category, and time-based analysis.

---

# 2. Sales & Revenue Performance

<img width="878" height="401" alt="Screenshot 2026-10-01 171149" src="https://github.com/user-attachments/assets/ed01b583-3950-4310-815b-4263201fa931" />

The Sales & Revenue page focuses on the financial and sales performance of the business.

The main KPIs include:

- Total Revenue: **15.84M**
- Total Products: **33K**

The page contains:

### Total Revenue by Month

Shows how revenue changes throughout the year and helps identify higher and lower revenue periods.

### Total Revenue by Quarter

The dashboard shows:

- Q1: **4.10M**
- Q2: **4.83M**
- Q3: **4.04M**
- Q4: **2.87M**

### Revenue vs Freight

Compares product revenue with freight-related values across months.

### Average Order Value by Month

Shows how the average amount spent per order changes throughout the year.

### Payment Performance

Provides an overview of payment-related activity.

---

# 3. Customer & Product Intelligence

<img width="879" height="406" alt="Screenshot 2026-10-01 171203" src="https://github.com/user-attachments/assets/53449efd-b678-4c98-925b-c8f484ebaba3" />


This page focuses on customer behavior and product performance.

The main KPIs are:

- Total Unique Customers: **96K**
- Orders per Customer: **1.03**
- Revenue per Customer: **164.87**
- Repeated Customers: **3K**
- Average Review Score: **4**

The page includes:

- Customer Distribution by State
- Customer Growth Over Time
- Product Price vs Customer Satisfaction
- Unique Customers by Category
- Category-level business metrics

### Customer Growth

The dashboard shows approximately:

- **44K customers in 2017**
- **53K customers in 2018**

### Category Analysis

The dashboard provides customer-level analysis for categories such as:

- Sports & Leisure
- Watches & Gifts
- Telephony
- Toys
- Stationery

This helps understand which product areas attract more customers.

---

# 4. Delivery & Seller Performance

<img width="906" height="404" alt="Screenshot 2026-10-01 171259" src="https://github.com/user-attachments/assets/172358aa-d65a-4aab-822a-bf4dd7c0b695" />


This page focuses on logistics and seller performance.

The main KPIs are:

- Average Delivery Days: **12.01**
- On-Time Delivery: **0.97**

The page includes:

- Average Delivery Days by Month
- Seller Revenue by Quarter
- Seller Revenue by State
- Orders by Status and Month
- Delivery Performance by Category

### Delivery Analysis

The monthly delivery chart shows how delivery time changes throughout the year.

### Seller Analysis

Seller revenue is analyzed by quarter and state to understand geographic seller performance.

### Order Status

Monthly order volume can be analyzed by order status.

### Category Delivery Performance

The table allows delivery performance to be compared across product categories.

---

# 5. Customer Experience & Business Improvement

<img width="911" height="401" alt="Screenshot 2026-10-01 171315" src="https://github.com/user-attachments/assets/90b678a6-04fc-4c1a-baa2-6f9093b394f9" />


The final dashboard page focuses on customer satisfaction and potential areas for business improvement.

The main KPIs are:

- Average Review Score: **4**
- 5-Star Reviews: **63K**
- 1-Star Reviews: **14.617K**
- Average Delivery Days: **12.01**
- Cancelled Orders: **625**
- Delayed Orders: **26K**

The page contains:

- Customer Rating Distribution
- 1-Star Reviews by Category
- 5-Star Reviews by Category
- Customer Satisfaction Trend
- Delivery Speed vs Customer Satisfaction
- Category-level Revenue and Review Performance

This page connects operational metrics with customer experience and allows further investigation into categories, locations, years, and months.

---

# Key Business KPIs

| KPI | Value |
|---|---:|
| Total Revenue | 15.84M |
| Total Customers | 96K |
| Total Orders | 99K |
| Average Order Value | 159.33 |
| Average Delivery Days | 12.01 |
| Average Review Score | 4 |
| Repeated Customers | 3K |
| Revenue per Customer | 164.87 |
| 5-Star Reviews | 63K |
| 1-Star Reviews | 14.617K |
| Cancelled Orders | 625 |
| Delayed Orders | 26K |

---

# Key Business Insights

### Revenue Performance

The business generated approximately **15.84M** in total revenue. The dashboard provides monthly, quarterly, yearly, category-level, and geographic views of revenue.

### Customer Base

The analysis contains approximately **96K unique customers**. Customer growth can be tracked over time and compared across states and product categories.

### Order Performance

The business recorded approximately **99K orders**, allowing order activity to be analyzed by month and order status.

### Product Categories

The dashboard highlights important revenue-generating categories including:

- Health & Beauty
- Watches & Gifts
- Bed Bath Table
- Sports & Leisure
- Computers & Accessories

### Customer Satisfaction

The average review score is approximately **4**. The dashboard separately analyzes 1-star and 5-star reviews to understand customer feedback in more detail.

### Delivery Performance

Average delivery time is approximately **12.01 days**. The dashboard also tracks delayed and cancelled orders.

### Geographic Analysis

Customer and seller activity is analyzed by state, allowing geographic patterns to be explored.

---

# Business Questions Answered

## Sales & Revenue

- What is the total revenue?
- How does revenue change month by month?
- Which quarter contributes more revenue?
- What is the average order value?
- Which product categories generate more revenue?

## Customer Analysis

- How many unique customers are there?
- Which states have more customers?
- How is the customer base growing?
- How many repeated customers are there?
- What is the revenue per customer?

## Product Analysis

- Which categories have more customers?
- Which categories generate more revenue?
- How does product price relate to customer satisfaction?

## Delivery Analysis

- What is the average delivery time?
- How does delivery time change by month?
- How many orders are delayed?
- How many orders are cancelled?
- How does delivery performance vary across categories?

## Seller Analysis

- Which states generate more seller revenue?
- How does seller revenue change by quarter?
- How does seller performance vary geographically?

## Customer Experience

- What is the average review score?
- How many 5-star reviews are there?
- How many 1-star reviews are there?
- Which categories receive more 1-star reviews?
- Which categories receive more 5-star reviews?
- How does customer satisfaction change over time?
- How does delivery performance compare with customer satisfaction?

---

# Power BI Features Used

The dashboard was developed using:

- Power Query
- Data Transformation
- Data Modeling
- DAX Measures
- KPI Cards
- Slicers
- Bar Charts
- Line Charts
- Area Charts
- Donut Charts
- Funnel Charts
- Maps
- Tables
- Interactive Filters
- Drill-down and interactive analysis

---

# What I Learned From This Project

Working on this project helped me understand how a real-world analytics project moves from raw data to a business intelligence solution.

Through this project, I practiced:

- Data cleaning using Python and Pandas
- Combining multiple datasets
- Exploratory Data Analysis
- Feature engineering
- Business KPI development
- Data visualization
- Power Query
- DAX
- Data modeling
- Dashboard design
- Customer analysis
- Sales analysis
- Product analysis
- Delivery analysis
- Business-oriented storytelling

One of the main things I learned is that a good dashboard is not only about creating charts. The important part is connecting different metrics and presenting the information in a way that helps users understand the business.

---

# Project Outcome

The final outcome of this project is an interactive Power BI dashboard that provides a complete view of E-Commerce business performance.

The dashboard brings together:

**Sales + Customers + Products + Sellers + Payments + Delivery + Reviews**

into one analytical solution.

This project demonstrates my ability to work with raw business data, transform it into useful information, analyze different business dimensions, and present the results through an interactive Business Intelligence dashboard.

---

# Project Structure

```text
E-Commerce-Business-Analysis/
│
├── Dataset/
│   └── Cleaned_Dataset.csv
│
├── Python/
│   ├── Data_Preprocessing.ipynb
│   ├── EDA.ipynb
│   └── Merged_Dataset.ipynb
│
├── PowerBI/
│   └── E-Commerce_Dashboard.pbix
│
├── assets/
│   ├── 01_executive_overview.png
│   ├── 02_sales_revenue.png
│   ├── 03_customer_product.png
│   ├── 04_delivery_seller.png
│   └── 05_customer_experience.png
│
└── README.md
```

---

# Skills Demonstrated

```text
Python
Pandas
NumPy
Matplotlib
Seaborn
Exploratory Data Analysis
Data Cleaning
Feature Engineering
Power BI
Power Query
DAX
Data Modeling
Business Intelligence
Business Analytics
KPI Analysis
Sales Analytics
Customer Analytics
Product Analytics
Delivery Analytics
Data Visualization
Dashboard Development
```

---

# Conclusion

This E-Commerce Business Analysis project gave me practical experience in building an analytics solution from the ground up.

Instead of looking at sales, customers, products, delivery, sellers, and reviews separately, I brought these different areas together to create a complete business performance view.

The final Power BI dashboard makes it easier to explore business performance, identify trends, compare different segments, and investigate areas that may require further attention.

This project represents my practical experience in **Data Analytics, Business Analysis, and Power BI-based Business Intelligence**.

---

## GitHub Repository Description

**End-to-end E-Commerce Business Analysis project using Python and Power BI to analyze sales, revenue, customers, products, sellers, delivery performance, payments, and customer satisfaction through an interactive Business Intelligence dashboard.**

## Suggested Repository Name

`ecommerce-business-analysis-powerbi`

## GitHub Topics

`python` `pandas` `power-bi` `power-query` `dax` `business-analytics` `data-analytics` `data-visualization` `business-intelligence` `customer-analytics` `sales-analytics` `ecommerce` `dashboard` `eda`
