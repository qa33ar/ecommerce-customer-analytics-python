# E-Commerce Customer Analytics with Python

## Project Overview

This project analyzes two years of fictional e-commerce transaction data (2024–2025) using Python in a Jupyter Notebook.

The project was developed to practice a complete data analysis workflow: inspecting raw data, identifying and resolving data-quality issues, integrating multiple related tables, performing exploratory data analysis, and translating the results into business insights and recommendations.

The analysis focuses on sales performance, profitability, products, customers, acquisition channels, discounts, cancellations, and returns.

## Dataset

The project uses six related CSV datasets:

- Customers
- Orders
- Order Items
- Products
- Promotions
- Returns

The datasets contain approximately 50,000 order-item records along with customer, product, promotion, and return information.

The data is fictional and was created specifically for this portfolio project.

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- VS Code

## Analysis Workflow

The project follows these main stages:

1. Data inspection and quality assessment
2. Data cleaning and validation
3. Feature engineering
4. Table integration
5. Exploratory Data Analysis (EDA)
6. Business insights and recommendations

The analysis includes duplicate and missing-value checks, categorical standardization, date validation, referential-integrity checks, calculated financial metrics, merge validation, distribution analysis, time trends, YoY analysis, product and customer performance, and order-status analysis.

## Key Findings

- Net Sales increased by **1.46% in 2025**, while order count and units sold remained almost unchanged. The growth was mainly associated with a **1.52% increase in Average Order Value (AOV)**.
- Gross Profit increased by **2.51%**, faster than Net Sales growth.
- **Electronics generated 47.41% of total Net Sales** and also had the highest category profit margin at approximately **32.31%**.
- **706 completed order lines had negative gross margins.** Of these, **99.6% had discounts of 25% or 30%**, indicating a strong relationship between high discount levels and loss-making transactions.
- November and December showed substantially stronger sales and profit in both years, suggesting a possible year-end seasonal pattern.
- Consumer customers generated the largest share of sales, although AOV was similar across Consumer, Home Office, and Small Business segments.
- Organic Search generated the highest total Net Sales among acquisition channels, while Paid Search had the highest AOV and Sales per Customer.
- Website generated the highest sales-channel revenue, while AOV remained relatively similar across Website, Mobile App, and Marketplace.

## Recommendations

- Review 25–30% discount policies and consider margin checks before applying high discounts.
- Maintain strong availability and performance in Electronics while exploring opportunities to grow other profitable categories.
- Focus on increasing profitable order volume, since 2025 revenue growth was driven primarily by higher order values rather than more orders.
- Prepare inventory and marketing activity for the stronger November–December sales period while using additional years of data to confirm seasonality.
- Evaluate products using both sales volume and profitability rather than sales alone.
- Combine acquisition-channel results with marketing-cost data before making decisions about marketing-budget allocation.

## Repository Contents

```text
ecommerce-customer-analytics-python/
│
├── data/                                      # Six source CSV datasets
├── e-com_portfolio.ipynb                     # Complete Python analysis
├── Ecommerce_Python_Analytics_Project_Brief.pdf
└── README.md
