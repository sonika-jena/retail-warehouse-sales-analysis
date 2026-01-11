# Retail & Warehouse Sales Analysis

## Project Overview
This project analyzes retail and warehouse sales data to understand sales performance across channels, identify top-performing product categories and suppliers, and support data-driven business decisions. The analysis combines exploratory data analysis (EDA) using Python with an interactive Power BI dashboard for visualization.

---

## Business Use Case
The insights from this project can help sales managers, inventory planners, and business analysts:
- Identify the primary revenue-driving sales channels
- Understand product category and supplier concentration
- Analyze the impact of zero and negative sales values (returns and adjustments)
- Support inventory planning and channel strategy decisions

---

## Dataset Summary
- Approximately 30,000 records
- Sales data from selected months in 2020
- Sales channels: Retail, Warehouse, Transfers
- Key attributes include supplier, item type, sales metrics, and time features

---

## Analysis & Methodology
The project follows a structured analytics workflow:
- Data quality assessment including analysis of zero and negative sales values
- Data cleaning while preserving valid business scenarios
- Feature engineering such as total sales, gross sales, adjustments, channel count, and dominant sales channel
- Exploratory data analysis to identify trends and patterns
- Power BI dashboard development for interactive insight exploration

---

## Power BI Dashboard Preview

### Dashboard Overview
![Dashboard Overview](images/dashboard_overview.png)

---

## Dashboard Insights

### Key Performance Indicators
- **Total Gross Sales:** 1.24M
- **Net Sales:** 1.23M
- **Active Suppliers:** 291
- **Active Items:** 16K

### Sales Channel Performance
- Warehouse sales contribute approximately 79% of total revenue.
- Retail and transfer channels play a smaller supporting role.

### Product & Supplier Insights
- Beer is the highest-grossing and dominant product category.
- Sales are concentrated among a small number of major suppliers.
- Most products are sold through a single dominant channel.

### Time-Based Trends
- The dataset covers selected months in 2020.
- Sales vary across the available months, with some months showing higher activity.
- Due to the limited time range, long-term seasonality conclusions cannot be reliably inferred.

---

## Tools & Technologies
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook
- Power BI

---

## Repository Structure
