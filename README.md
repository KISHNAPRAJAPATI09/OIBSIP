# OIBSIP – Data Analytics Level 1 – Task 1

## EDA on Retail Sales Data

### Objective
Perform exploratory data analysis on retail sales data to uncover sales trends, customer behaviour patterns, product performance and actionable business insights.

### Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

### Dataset
The project uses a retail-sales dataset with the schema required by the OASIS task:
`Transaction ID`, `Date`, `Customer ID`, `Gender`, `Age`, `Product Category`, `Quantity`, `Price per Unit`, and `Total Amount`.

A public example with the same schema is documented in the GitHub retail-sales dataset repository used for schema verification.

### Project Structure
```text
OIBSIP/
└── DataAnalytics-L1-EDARetailSales/
    ├── data/
    │   └── retail_sales.csv
    ├── EDA_Retail_Sales.ipynb
    ├── README.md
    └── screenshots/
```

### Analysis Performed
1. Dataset inspection
2. Missing-value and duplicate checks
3. Descriptive statistics
4. Monthly sales trend
5. Quarterly sales trend
6. Age-group analysis
7. Gender analysis
8. Top-10 supported product proxy analysis
9. Revenue by category
10. Correlation heatmap
11. Additional age-group transaction-value analysis
12. Business insights and recommendations

### Important Dataset Limitation
The task dataset contains `Product Category` but no separate `Product Name` field. Therefore, the notebook does not invent product names. The requested top-10 product analysis is represented transparently using `Product Category + Price per Unit` as a product proxy.

### How to Run
1. Install Python 3.
2. Install packages:
   `pip install pandas numpy matplotlib seaborn jupyter`
3. Open the project folder in VS Code.
4. Start Jupyter:
   `jupyter notebook`
5. Open `EDA_Retail_Sales.ipynb`.
6. Run all cells from top to bottom.

### OASIS Submission
Repository name must be exactly:
`OIBSIP`

Task folder:
`OIBSIP/DataAnalytics-L1-EDARetailSales/`

Before submission, add screenshots of the executed notebook and record the required demo video with the first 2 seconds showing your full name, assigned track and task title.
