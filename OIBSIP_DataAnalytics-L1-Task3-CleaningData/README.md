# OIBSIP Data Analytics — Task 3: Cleaning Data

## Objective
Demonstrate professional data-cleaning skills by taking a deliberately messy customer dataset and systematically transforming it into a clean, analysis-ready dataset while documenting every decision.

## Tech Stack
Python, pandas, numpy, Jupyter Notebook.

## Cleaning Steps
1. Data-quality report: shape, nulls, duplicates, dtypes and unique values.
2. Missing values: text → `Unknown`; numeric → median; invalid dates → mode date after datetime conversion.
3. Duplicate rows: identified and removed.
4. Standardisation: normalised gender and city formatting.
5. Outliers: detected using IQR and capped rather than deleting rows.
6. Data types: dates converted to datetime; numeric columns converted to numeric.
7. Before-vs-after summary created.
8. Cleaned dataset exported as CSV.

## Dataset Note
The raw dataset is deliberately generated for this exercise and intentionally contains missing values, duplicates, inconsistent formatting, invalid dates and numeric outliers. The task brief suggests sourcing a public messy dataset; if your evaluator requires that specifically, replace the raw CSV with a suitable Kaggle/UCI dataset and update the notebook mapping.

## Folder Structure
```text
DataAnalytics-L1-CleaningData/
├── data/
│   ├── messy_customer_data.csv
│   ├── cleaned_customer_data.csv
│   └── before_after_summary.csv
├── screenshots/
│   ├── 01_before_after_rows.png
│   ├── 02_missing_values.png
│   └── 03_purchase_amount_distribution.png
├── Cleaning_Data.ipynb
├── README.md
└── project_summary.csv
```
