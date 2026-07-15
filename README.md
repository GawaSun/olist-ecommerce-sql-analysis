# Olist Brazilian E-Commerce — SQL Analysis

Analysis of consumer behavior on a Brazilian e-commerce marketplace using SQL (DuckDB) and Python.
Working across 99,000+ orders, 3,000+ sellers, and 70+ product categories, this project investigates
what customers buy, what drives satisfaction, how retention breaks down, and what separates
high-performing sellers from the rest.

**Dataset:** [Olist Brazilian E-Commerce (Kaggle)](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
**Tools:** DuckDB, Python, Pandas, Google Colab
**Notebook:** [SQL_OlistBrazilian.ipynb](notebook/SQL_OlistBrazilian.ipynb)

## Key Findings
1. Health & beauty and bed & bath dominate by order volume; watches & gifts leads by average transaction value
2. Price does not predict satisfaction — review scores are flat across all price tiers
3. Delivery timing is the strongest satisfaction driver — late orders score 2.57 vs 4.29 for early ones
4. 97% of customers never return after their first order — acquisition vastly outpaces retention
5. High-revenue sellers follow two distinct strategies — revenue rank alone is a poor proxy for seller quality

## Structure
1. Setup
2. Data Exploration
3. Data Cleaning
4. Analysis
   - What customers actually buy
   - Does price affect satisfaction?
   - Does delivery speed affect satisfaction?
   - Repeat purchase behavior
   - What traits do top revenue sellers share?
