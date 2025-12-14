# COFFEE-SALES-ANALYSIS

## Project Overview
This project performs an exploratory data analysis (EDA) on coffee sales transaction data using **Python**.  
The objective is to understand sales patterns, payment behavior, and product performance through structured data analysis.

---

## Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Dataset Description
The dataset contains **3,636 transaction records** with the following key fields:
- `date` – transaction date
- `datetime` – timestamp of transaction
- `cash_type` – mode of payment
- `card` – card usage indicator
- `money` – transaction amount
- `coffee_name` – type of coffee sold

---

## Data Cleaning & Validation
The following data quality checks were performed:
- Verified data types using `DataFrame.info()`
- Checked duplicate records (no duplicates found)
- Checked missing values (missing values identified in card column)
- Converted date and datetime columns to proper datetime format

---

##  Exploratory Data Analysis (EDA)
Key analyses performed include:
- Understanding transaction volume
- Coffee-wise sales analysis
- Payment method distribution
- Date and time-based sales exploration
- Revenue analysis using transaction amounts

---

## Key Observations
- Dataset is largely clean with no duplicate records
- Most transactions are concentrated around specific coffee types
- Payment behavior shows dominance of certain payment modes
- Minor missing values exist but do not significantly impact analysis

---

## Business Insights
- Popular coffee items should be prioritized for inventory planning
- High-frequency transaction times can be targeted for promotions
- Payment mode trends can help optimize checkout experience

---


