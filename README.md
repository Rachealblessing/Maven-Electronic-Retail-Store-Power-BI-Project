# Maven-Electronic-Retail-Store-Power-BI-Project
A end to end Power BI project on Maven Electronic retail store

Table of Content
---
[project overview](#project-overview)

[Data field](#Data-field)

[Data source](#Data-source)

[Tool used](Tool-used)

[Data Cleaning and preparation](Data-cleaning-and-preparation)

[Exploratory Data Cleaning](Exploratory-Data-Cleaning)

[Data Visualization](Data-Visualization)

[Insight](Insight)

[Recommendation](Recommendation)

### project overview
This project build an end-to-end Power BI solution that ingests raw data, models it, computes key business metrics, and delivers an interactive dashboard for stakeholders to monitor performance, identify trends, and make data-driven decisions.

### Data field

1. Sales Table
2. Customer Table
3. Product Table
4. Stores
5. Exchange Rate

The dataset consists of multiple related tables:

1. Sales: Contains transactional data including orders, delivery dates, quantities,
currency, and links to customers, stores, and products.
2. Customers : Provides customer demographics (gender, age, location) to analyze
customer behavior and segmentation.
3. Products: Includes product details (brand, color, subcategory, category, unit
cost, and unit price) for product performance and profitability analysis.
4. Stores: Provides store-level details (location, size, and open date) to assess
regional and store performance.
5. Exchange Rates (Supporting Table): Provides conversion rates by date and
currency to ensure consistent reporting in USD.

### Data source
This dataset was gotten from kaggle

### Tool used
- Microsoft Power BI
- Github
- Powerpoint

### Data Cleaning and preparation
The dataset was using PowerBI,removing of duplicates, fixing of null by replacing with mode/median, changing of data type, changing of currency sign

### Data Modelling
The dataset which consist of five(5) tables was connected during modelling, the sales table was marked as the fact table, which other mutiple table dimensions were connected to which gives a star schema 
<img width="1306" height="806" alt="data modelling bc" src="https://github.com/user-attachments/assets/371fde89-99ad-4952-9b0e-ddfcae25c425" />

### Time Intelligence function
Date Table Creation
This was used to create our calendar table where we have our month,day, year,quarter. we marked it as our date table
<img width="683" height="880" alt="calendar table" src="https://github.com/user-attachments/assets/e78095c7-aad3-42cb-bae1-3d0961670589" />

### Exploratory Data analysis


  
