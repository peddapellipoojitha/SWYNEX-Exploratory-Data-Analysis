# SWYNEX – Exploratory Data Analysis (Task 2)

## Overview
EDA of the cleaned supermarket sales dataset from Task 1 using Python, pandas, NumPy and Matplotlib.

## Files
- `Cleaned_Supermarket_Sales.csv` – Task 1 cleaned dataset used as input.
- `eda_analysis.py` – reproducible Python analysis script.
- `EDA_Report.xlsx` – statistical summaries, group analyses, daily trend and business insights.
- `charts/` – five charts.
- `requirements.txt` – dependencies.

## Key results
- Total calculated sales: ₹3,923.00 across 39 records with calculable amounts.
- Mean: ₹100.59; median: ₹80.00; standard deviation: ₹75.70.
- Leading category: Grocery (₹1,145.00).
- Leading city: Hyderabad (₹1,750.00).
- Leading payment method: Upi (₹2,007.00).

## Five business insights
1. Total calculated sales are ₹3,923.00 across 39 records with a calculable amount.
2. Grocery is the leading category at ₹1,145.00 (29.2% of net sales).
3. Hyderabad leads city-wise sales at ₹1,750.00 (44.6% of net sales).
4. Upi is the leading payment method by sales value at ₹2,007.00.
5. Rice 5Kg is the highest-value product at ₹640.00.

## Data quality and limitations
- 2 record(s) have missing calculated sales because Quantity or Unit_Price_INR is missing.
- 1 record(s) have a missing/unresolved date and are excluded from daily trend analysis.
- Negative sales values are retained as exceptions and should be checked as possible returns/refunds.
- The findings describe this small practice dataset only and should not be generalized to all stores or periods.

## Run
```bash
pip install -r requirements.txt
python eda_analysis.py
```
