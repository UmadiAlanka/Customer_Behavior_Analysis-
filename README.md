# Customer_Behavior_Analysis
📊 Overview
This project provides a comprehensive end-to-end analysis of customer behavior patterns. By combining Python for data processing, PostgreSQL for structured storage, and Power BI for visualization, the project identifies key trends in purchase amounts, subscription statuses, and review ratings to drive data-informed business decisions.

📁 Dataset

Size: 3,900+ Customer Records

Key Features: Customer ID, Purchase Amount, Review Rating, Subscription Status, and Category.

🛠️ Tech Stack
Data Processing: Python (Pandas, NumPy)

Database Management: PostgreSQL 18

Visualization: Power BI

🚀 Steps & Methodology
Exploratory Data Analysis (EDA): Performed in Jupyter Notebooks to identify outliers and missing values.

Data Cleaning: Standardized currency formats and handled null values using Python.

Database Schema: Created a relational schema in PostgreSQL and imported the cleaned dataset for high-performance querying.

SQL Analysis: Executed complex queries to calculate average purchase values and segment customers by rating.

Dashboarding: Connected Power BI to the PostgreSQL server to create real-time visualizations.

📈 Dashboard Results
Customer Count: 3.9K total customers.

Revenue Insight: Average purchase amount identified at $59.76.

Engagement: Average review rating maintained at 3.75/5.

Segmentation: Majority of customers are currently on a non-subscription basis (73%), highlighting an opportunity for loyalty program growth.

🛠️ How to Run
Database Setup: Import the provided customer_behaviour.sql file into your local PostgreSQL instance using pgAdmin.

Python Environment: Install dependencies via pip install pandas sqlalchemy.

Power BI: Open the .pbix file and update the Data Source Settings to point to your local localhost PostgreSQL server.
