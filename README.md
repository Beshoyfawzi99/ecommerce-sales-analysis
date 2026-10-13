# E-Commerce Sales Analysis

## Project Overview
This project explores e-commerce sales data to identify revenue trends, top-performing products, and customer purchasing patterns.

The goal is to transform raw sales data into meaningful insights that can support business decision-making.

## Objectives
- Analyze sales and revenue trends over time.
- Identify top-performing products by revenue.
- Analyze customer purchasing patterns.
- Compare sales performance across countries.
- Create visualizations to communicate key findings.

## Tools & Technologies
- Python
- Pandas
- Matplotlib
- Google Colab
- Jupyter Notebook

## Dataset
- **Source:** [UCI Online Retail Dataset](https://archive.ics.uci.edu/dataset/352/online+retail)
- **Original records:** 541,909
- **Period:** December 2010 – December 2011

## Project Workflow
1. Data collection and exploration.
2. Data cleaning and preparation.
3. Exploratory Data Analysis (EDA).
4. Data visualization.
5. Interpretation of sales trends and customer behavior.

## Repository Structure
- `E_Commerce_Sales_Analysis.ipynb` — notebook containing the data cleaning, analysis, and visualizations.
- `README.md` — project documentation.

## Key Findings
- **Total retained sales revenue:** £10,666,684.54.
- **Largest market:** The United Kingdom, accounting for approximately 84.6% of retained sales revenue.
- **Monthly performance:** November 2011 had the highest monthly revenue among the months analyzed.
- Additional analysis explores top-performing products, customers, monthly sales quantities, and order counts.

## Data Cleaning
- Removed rows with missing product descriptions.
- Excluded cancelled invoices.
- Excluded transactions with non-positive quantities or unit prices.
- Calculated revenue as `Quantity × UnitPrice`.

The cleaned dataset contains 530,104 rows.

## Limitations
- December 2011 is incomplete, with records available only through December 9.
- Revenue represents the sum of retained positive-quantity, positive-price sales lines. It should not be interpreted as fully reconciled net revenue.
- Customer analysis excludes records without a customer ID.

## Author
**Beshoy emad Fawzi**

Computer Science | Data Science & Analytics
