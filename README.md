# Retail Data ELT Lab

A hands-on Data Engineering project completed as part of the Saras AI Institute coursework. This project demonstrates an Extract, Load, Transform (ELT) workflow using Python, Pandas, SQLite, and SQL.

## Project Overview

The project focuses on processing retail datasets, identifying data-quality issues, transforming raw data using SQL staging views, and performing business analysis.

## Technologies Used

- Python
- Pandas
- SQLite
- SQL
- Google Colab
- GitHub

## Dataset

The project uses four retail CSV datasets:

- `customers.csv` – Customer information.
- `products.csv` – Product details and prices.
- `orders_raw.csv` – Raw order records.
- `orders_clean.csv` – Clean reference dataset for reconciliation.

## Work Performed

1. Loaded and explored retail CSV datasets using Pandas.
2. Created a SQLite database and loaded raw data into tables.
3. Inspected database schemas and identified table grain.
4. Created SQL staging views and applied data transformations.
5. Performed data-quality checks for missing values, duplicate records, invalid dates, and non-positive quantities.
6. Used SQL joins and aggregations to analyze retail performance.
7. Compared raw data with the clean reference dataset.
8. Prepared a final findings summary.

## Key Findings

| Metric | Result |
|---|---:|
| Raw order records | 5,100 |
| Clean reference records | 5,000 |
| Extra exact duplicate rows | 100 |
| Missing customer IDs in raw data | 173 |
| Non-positive quantities in raw data | 53 |
| Invalid dates in raw data | 58 |
| Total recorded units | 14,947 |
| Calculated sales value | 1,113,264.53 |

*Note: Sales figures are preliminary and calculated from raw staging data, so duplicate records may affect the totals.*

## Repository Structure

```text
saras-ai-retail-elt-lab/
│
├── Retail_ELT_UtkarshPal.ipynb
├── retail_lab.db
└── README.md
```

## How to Run

1. Open the Jupyter Notebook in Google Colab.
2. Upload the required four CSV datasets.
3. Run the notebook cells from top to bottom.
4. Review the SQL queries, outputs, and findings.
5. Use the generated SQLite database for further analysis.

## Learning Outcomes

- Understanding the ELT workflow.
- Working with Pandas and SQLite.
- Writing SQL queries for data transformation.
- Performing data-quality checks.
- Analyzing retail business data.
- Reconciling raw and cleaned datasets.

## Author

**Utkarsh Pal**

B.Tech – Computer Science Engineering (AI)

Chitkara University

## Acknowledgement

Completed as part of the Data Engineering coursework at Saras AI Institute.
