# duplicate-record-check
Duplicate Record Check project using Python and Pandas to identify duplicate records, generate a duplicate report, and create a cleaned dataset for improved data quality.
 Duplicate Record Check

Project Overview

This project focuses on identifying duplicate records, generating a duplicate report, and creating a cleaned dataset to improve data quality.

Objectives

- Identify exact duplicate records.
- Detect repeated Order IDs for further review.
- Generate a duplicate report.
- Remove exact duplicate rows while preserving the first occurrence.
- Create a cleaned dataset for further analysis.

Tools and Technologies

- Python
- Pandas
- CSV
- GitHub

Dataset

The project uses a retail sales sample dataset containing order IDs, dates, products, quantities, prices, sales, and categories.

Project Files

- "retail_sales_with_duplicates.csv" – source sample dataset.
- "duplicate_report.csv" – records flagged for review.
- "cleaned_retail_sales.csv" – cleaned dataset.
- audit_note.txt" – cleaning methodology and results.
- "requirements.txt" – Python dependencies.

Methodology

1. Load the dataset using Pandas.
2. Identify exact duplicate rows.
3. Review repeated Order IDs.
4. Remove exact duplicates while keeping the first occurrence.
5. Export the cleaned dataset and duplicate report.

Results

- Original records: 23
- Exact duplicate rows removed: 2
- Cleaned records: 21

Conclusion

Duplicate detection helps improve data quality and reduces the risk of inaccurate counts and sales analysis. Records with conflicting values should be verified before deletion.

How to Run

Install the required dependencies and run the Python script implementing the duplicate detection and cleaning steps.
