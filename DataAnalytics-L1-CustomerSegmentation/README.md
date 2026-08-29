# Task 2 — Customer Segmentation Analysis

Objective:Applied K-Means clustering to segment an e-commerce customer base by purchasing behaviour (RFM: Recency, Frequency, Monetary), enabling targeted marketing strategies.

Dataset:UCI Online Retail Dataset — transaction-level e-commerce data with InvoiceNo, CustomerID, InvoiceDate, Quantity, and UnitPrice.

Key Findings:
- Identified 4 distinct customer segments using the Elbow Method: Regular customers (2,103), At-risk/lapsed customers (1,098), a small VIP group (16) driving disproportionate revenue (~₹71,724 avg. spend), and Loyal high-value customers (185).
- The VIP segment, despite being <0.5% of customers, generates extremely high frequency and monetary value — a classic 80/20 revenue concentration pattern.
- Recommended targeted actions per segment: loyalty nurturing, win-back campaigns, white-glove VIP treatment, and upsell/referral incentives respectively.

Tech Stack: Python, pandas, scikit-learn (KMeans, StandardScaler), matplotlib, seaborn, Jupyter Notebook (Google Colab)
