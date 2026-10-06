# SWYNEX - Task 2: Exploratory Data Analysis (EDA)

## Project Overview
This repository contains the Exploratory Data Analysis (EDA) completed for Task 2 of the Swynex Technologies Data Analytics Internship. Using the cleaned dataset from Task 1 (124 records), I analyzed summary statistics, identified business trends, and detected data anomalies using Python (Pandas, Matplotlib, Seaborn).

## Summary Statistics
- **Total Records Analyzed:** 124 transactions
- **Average Purchase Amount:** ₹3,406.15 (Median: ₹2,577.04)
- **Customer Age Range:** 18 to 63 years (ignoring single entry typo of 200)
- **Customer Ratings:** Concentrated between 1.0 and 5.0 (with 5 entries at 10.0)

## 5 Key Business Insights & Anomalies
1. **Revenue Outlier Distortion:** A single extreme transaction of ₹99,999.99 in Varanasi artificially skewed the "Other" category and inflated average spending. Median purchase (₹2,577) reflects true customer purchasing power.
2. **Core Revenue Drivers:** After excluding the extreme outlier, Groceries (₹74,389) and Books (₹71,617) generate the highest overall sales volume.
3. **High-Value Product Basket:** Clothing delivers the highest average transaction value (₹3,023.17 per order), making it ideal for upselling strategies.
4. **Geographic Concentration:** 46.8% of customers are located in Varanasi, Kolkata, and Delhi.
5. **Rating Scale Discrepancy:** The rating distribution shows a peak around 3.0, but contains 5 entries logged at 10.0, indicating merged survey scales (5-star vs 10-point NPS) requiring normalization.

## Repository Contents
- `SWYNEX_Task2_Exploratory_Data_Analysis.ipynb`: Complete EDA Jupyter Notebook.
- `cleaned_data.csv`: Cleaned input dataset from Task 1.
