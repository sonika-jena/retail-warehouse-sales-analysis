# Exploratory Data Analysis (EDA)

This folder contains the Jupyter Notebook used to perform exploratory data analysis on the retail and warehouse sales dataset. The notebook emphasizes data quality assessment, feature engineering, and business-oriented insights derived from both positive and non-positive sales values.

---

## Notebook Overview

**File:** `retail_warehouse_sales_eda.ipynb`

The notebook follows a structured EDA workflow:

### 1. Business Understanding
- Defines the objective of analyzing retail and warehouse sales performance.
- Focuses on identifying sales drivers, channel dominance, and product behavior.

### 2. Dataset Overview
- Initial inspection of dataset size, structure, and data types.
- Review of sales, supplier, product, and time-related attributes.

### 3. Data Quality & Cleaning
- Identification and analysis of **zero and negative values** in sales-related fields.
- Zero values are treated as valid business scenarios (e.g., no sales activity).
- Negative values are interpreted as potential returns, corrections, or adjustments rather than errors.
- Data is cleaned and prepared without indiscriminate row removal to avoid analytical bias.

### 4. Feature Engineering
- Creation of derived features to enhance analysis:
  - `total_sales`
  - `gross_sales`
  - `adjustments`
  - `channel_count`
  - `dominant_sale_channel`
- These features support channel-level and product-level performance evaluation.

### 5. Exploratory Data Analysis
- Comparison of retail, warehouse, and transfer sales.
- Analysis of product performance by item type.
- Supplier-level sales concentration analysis.
- Examination of sales behavior for products with zero or negative values.
- Time-based analysis using available months from 2020.

### 6. Insights & Interpretation
- Warehouse sales contribute the majority of overall revenue.
- Beer is the highest-grossing product category.
- A small number of suppliers account for a large share of sales.
- Most products are sold through a single dominant channel.
- Zero and negative sales values provide insight into returns, corrections, and inactive products.
- Time-based conclusions are limited due to partial-year data availability.

### 7. Conclusion
- Summarizes analytical findings and their business implications.
- Highlights the importance of accounting for non-positive sales values in realistic sales analysis.
- Demonstrates how the analysis can support inventory planning, supplier evaluation, and channel strategy.

---

## Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Notes
- The analysis intentionally preserves zero and negative sales records to reflect real-world business conditions.
- Time-based insights are cautiously interpreted due to limited temporal coverage.
- The processed dataset generated from this notebook is used for Power BI visualization.

---

## How to Use
Open the notebook in Jupyter Notebook or JupyterLab and execute the cells sequentially to reproduce the analysis and visualizations.
