# Sales Performance and Revenue Analysis

## Project Overview

This project analyses sales pipeline data using Python to evaluate sales outcomes, revenue contribution, product performance, and data quality.

The objective is to convert raw sales data into actionable insights that support business decision-making.

## Business Questions

- What percentage of closed opportunities are won?
- Which products generate the most revenue?
- How does average won deal value differ by product?
- How are opportunities distributed across sales stages?
- Which columns contain missing data?

## Tools and Technologies

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Dataset

The analysis uses five CSV files covering sales pipeline opportunities, products, accounts, sales teams, and a data dictionary.

The main sales pipeline dataset contains 8,800 records.

## Key Findings

- Total opportunities: 8,800
- Won opportunities: 4,238
- Lost opportunities: 2,473
- Win rate among closed opportunities: 63.15%
- Total won revenue: 10,005,534 recorded value units
- Top three products contribute approximately 83.52% of total won revenue.

## Analysis Performed

- Data structure and quality checks
- Missing-value analysis
- Won and lost deal analysis
- Win-rate calculation
- Revenue by product
- Average won deal value by product
- Sales-stage distribution
- Product revenue contribution

## Business Value

The analysis helps identify major revenue contributors, compare product-level sales outcomes, and highlight data-quality issues that may affect reporting.

These insights can support further investigation into sales performance and product-level planning.

## Limitations

The dataset does not specify the currency associated with closing values, so revenue is reported in recorded value units. The analysis identifies patterns and associations but does not establish the causes of sales outcomes or differences in deal value.

## Project Structure

- `data/raw/`: Original CSV files
- `notebooks/`: Jupyter Notebook analysis
- `outputs/figures/`: Exported charts
- `requirements.txt`: Required Python libraries

## How to Run

1. Download or clone the repository.
2. Install the libraries listed in `requirements.txt`.
3. Open `notebooks/01_data_audit.ipynb` in Jupyter Notebook.
4. Run the notebook from top to bottom.

Ensure the CSV files are available in `data/raw/` and that the notebook's relative file paths match the folder structure.

## Author

Business Analytics Student | Aspiring Business Analyst
