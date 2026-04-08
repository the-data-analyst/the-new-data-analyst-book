📊 Analytics Learning Dataset – Star Schema Example
This repository contains a fully synthetic sales dataset designed for learning and teaching data analytics, business intelligence, and data modeling concepts.
The dataset was created specifically as a companion to a data analytics book and follows a star schema structure commonly used in real‑world analytical systems. It is suitable for practice with SQL, Excel, Python, Power BI, and Databricks.
All data in this repository is fictional, synthetically generated, and safe for educational and portfolio use.

🏗 Dataset Structure
The dataset is organized as a star schema, with one fact table and multiple dimension tables:
Fact Table

fact_sales.csv
Contains individual sales transactions, including quantities, prices, costs, and revenue.

Dimension Tables

dim_customer.csv – Customer attributes (name, age group, type, gender)
dim_product.csv – Technology products sold by a computer shop
dim_region.csv – Sales regions
dim_date.csv – Calendar dimension for time‑based analysis

Relationships:
fact_sales
 ├─ product_id  → dim_product
 ├─ customer_id → dim_customer
 ├─ region_id   → dim_region
 └─ date_id     → dim_date


🎯 Use Cases
This dataset can be used to practice:

SQL joins and aggregations
KPI calculations (revenue, margin, quantity)
Time‑based analysis (monthly trends, year‑over‑year)
Customer segmentation
Product performance analysis
Power BI data modeling and dashboards
Python (pandas) groupby and visualization
Databricks and large‑scale analytics workflows

It is intentionally kept simple while remaining realistic.

✅ Key Characteristics

✅ Fully synthetic and fictional data
✅ Realistic business structure
✅ Clean and well‑documented CSV files
✅ Referential integrity across tables
✅ Suitable for beginners and intermediate learners
✅ Safe for public sharing and portfolio projects


📚 Intended Audience

Data analytics learners
Career switchers entering data roles
Students and self‑learners
Trainers and educators
Anyone practicing SQL, BI, or analytics tools


ℹ️ License
This dataset is provided for educational and learning purposes.
You are free to use it for:

study
training
demonstrations
portfolio projects
