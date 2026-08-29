# Task 3 — Data Cleaning

Objective: Took a deliberately messy e-commerce product dataset and systematically transformed it into a clean, analysis-ready dataset, documenting every decision.

Dataset: Shein Men's Clothing dataset (1,889 rows) — product listings with color-count, title, selling proposition, price, discount, and rank information. *(Notebook shared with Task 2 — see DataAnalytics-L1-CustomerSegmentation folder.)*

Cleaning Summary:
- Converted `price` and `discount` from string formats (e.g. "$4.10", "-13%") to proper numeric types.
- Handled missing values column-by-column with documented justification — e.g. missing discount filled with 0 (no promotion applied), missing rank columns filled with "Not Ranked" (product simply unranked).
- Detected outliers in price and discount using the IQR method; retained both since they represent genuine premium pricing and legitimate flash-sale discounts rather than data errors.
- Verified 0 duplicate rows and corrected all column data types.
- Produced a before/after data quality summary and exported the cleaned dataset as a new CSV.

**Tech Stack:** Python, pandas, numpy, Jupyter Notebook (Google Colab)
