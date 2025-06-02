# EDA
# Exploratory Data Analysis (EDA) – Superstore Dataset

## Project Overview

This task performed by me **Exploratory Data Analysis (EDA)** on a cleaned version of the Superstore dataset using **Python** in a **Jupyter Notebook**. 
The goal is to discover patterns, trends, and insights that can help improve business decisions.

## Main objectives 

- Analyze sales, profit, discount, and other key features.
- Identify trends and relationships between variables.
- Detect anomalies or outliers.
- Summarize business insights from the data.

## Tools and Libraries Used

- **Jupyter Notebook** (Python)
- **Pandas** – data manipulation
- **Matplotlib** – data visualization
- **Seaborn** – statistical graphics

## Dataset Description

The dataset used is: superstore_Custom_Cleaned.csv
It contains 800 rows of Superstore sales data, including:

Column Name & Description                          

Order Date -  Date when the order was placed       
Ship Date  -  Date when the product was shipped    
Sales      -  Total sales amount                   
Profit     -  Profit gained from the order         
Discount   -  Discount applied                     
Quantity   -  Number of items sold                 
Category   -  Product category                     
Sub-Category - Product sub-category                 
Region     - Sales region                         
State      - Sales state                          

##  EDA Process Followed

1. **Data Loading and Initial Inspection**
   - Used head(), .info(), .describe() to understand data structure

2. **Cleaning (already done before this notebook)**
   - Removed duplicates, blank rows, and fixed spacing issues

3. **Univariate Analysis**
   - Histograms and boxplots for Sales, Profit, Quantity, and Discount

4. **Bivariate and Multivariate Analysis**
   - Scatterplots, heatmaps, and pairplots
   - Checked relationships: Sales vs Profit, Discount vs Profit, etc.

5. **Outlier Detection**
   - Boxplots showed profit outliers in some categories

6. **Trend and Pattern Identification**
   - Detected negative trend between Discount and Profit
   - Found Technology to be most profitable; Furniture had more losses

7. **Summary of Findings**
   - Provided key insights and business suggestions at the end

##  Deliverables

- EDA_Superstore.ipynb – Jupyter Notebook with complete analysis
- EDA_Superstore.pdf – Exported report version for presentation
- superstore_Custom_Cleaned.csv – The dataset used
- README.md – This file

##  Outcome
  Through this Exploratory Data Analysis (EDA) project on the Superstore dataset, I have:

Gained confidence in working with real-world business data
Learned how to use Pandas, Matplotlib, and Seaborn for data exploration
Developed the skill to find patterns, such as which product categories perform well
Understood how to identify trends, like how discounts affect profit
Improved my ability to summarize insights visually and statistically
Learned to communicate findings clearly using graphs and observations
This project helped me data analysis foundation and prepared me for more advanced data projects like dashboard creation, predictive analytics, and business intelligence.
