🇧🇷 Brazilian E-Commerce Analytics (SQL & Python)
🎯 Objective
Analyze the Olist E-Commerce dataset (100k+ orders) to identify revenue drivers, logistical bottlenecks, and customer segments using advanced SQL techniques.

🛠️ Tech Stack
SQL (SQLite): Complex Joins, Window Functions (RANK), CTEs, Date Manipulation.

Python (Pandas): ETL process (CSV to DB), Data Validation.

Tools: DBeaver, Jupyter Notebook.

📊 Key Insights & Queries
1. High-Value Customer Segmentation (RFM)

File: RFM.ipynb

Technique: Used CTEs and calculated Recency/Frequency/Monetary metrics.

Insight: Identified VIP customers (Recency < 90 days, Spend > 500 BRL) vs. Churned users (> 300 days inactive).

2. Category Performance Ranking

File: RFM.ipynb

Technique: Window Functions (RANK() OVER PARTITION BY).

Insight: Ranked top 3 products within each category to optimize inventory.

3. Delivery Performance Analysis

File: RFM.ipynb

Technique: Date manipulation (julianday).

Insight: Analyzed average delivery times across months to detect logistical seasonality.

4. Credits
Dataset: Olist E-Commerce Public Dataset [Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
5. Contact
For questions or collaboration, reach out at: [E-Mail](mailto:moujtahida2111@gmail.com)
6. License
This project is licensed under the MIT License.
