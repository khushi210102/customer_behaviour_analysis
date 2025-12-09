Customer Shopping Behavior Analysis – Data Analytics Project
Overview

This project demonstrates a complete end-to-end data analytics workflow. It includes loading and analyzing data in Python, performing Exploratory Data Analysis (EDA), cleaning and transforming the dataset, extracting insights using SQL, and building an interactive Power BI dashboard. A final report and presentation (created using Gamma) summarize the findings and business recommendations.
This project showcases practical skills in Python, SQL, Power BI, data visualization, and storytelling—ideal for data analyst and BI analyst roles.

Dataset-
Total Rows: 3,900
Total Columns: 18

Type: Customer shopping behavior

Key Features:
Demographics (age, gender, location, subscription status)

Purchase details (category, purchase amount, quantity, color, size)

Behavioral patterns (discount usage, frequency of purchases, shipping type, review rating)

Missing Values: 37 missing review ratings (handled during cleaning)

Tools & Technologies:

Python: pandas, numpy, matplotlib/seaborn

SQL: MySQL

Power BI: Interactive dashboard creation

Jupyter Notebook / VS Code: Development environment

 Project Steps
 1. Data Loading (Python)

Imported dataset using pandas

Inspected structure using df.info() and df.describe()

Verified data types and basic statistics

2. Exploratory Data Analysis (EDA)

Univariate, bivariate, and multivariate analysis

Visualized patterns using histograms, boxplots, and bar charts

Identified outliers, trends, and missing values

3. Data Cleaning & Preparation:
   
Handled missing values in review ratings using median imputation

Standardized column names (snake_case)

Removed redundant fields (e.g., duplicate promo features)

Engineered new features such as:

purchase_frequency_days

customer_segment

Exported cleaned dataset to SQL database

4. SQL Analysis:
   
Performed business-driven SQL queries, including:

Revenue analysis by gender, category, and subscription status

High-spending discount users

Top-rated products:

Shipping type comparison

Product dependency on discounts

Customer segmentation using purchase history

Product ranking by popularity

5. Power BI Dashboard:

Built an interactive dashboard to visualize:

Revenue by category, gender, season, subscriber status

Purchase trends and frequency patterns

Top products & customer segments

Impact of discounts and shipping types

Overall KPIs (total customers, revenue, average spend)

6. Final Report & Presentation:
   
Summarized key insights and business recommendations

Created a clean, modern presentation in Gamma

Highlighted opportunities to improve customer retention, marketing strategy, and product positioning

Key Results & Insights:

Identified high-value customer segments and top-performing categories

Analyzed how discounts affect revenue and customer behavior

Found product groups highly dependent on promotions

Uncovered patterns linked to shipping preference, seasonal trends, and repeat purchases

Provided actionable recommendations to improve retention and boost revenue
