# Business performance Optimization Project

## Project Overview
This project analyzes sales and profit data from a retail superstore to identify major drivers of profitability. Key insights include regional profit disparities and the strong negative impact of discount levels on overall profit margins. The analysis estimates that reducing discount levels by 10% could improve average profit by approximately $6.39, enabling targeted pricing and marketing strategies to boost profitability.[attached_file:1]

## Data Source
- Dataset: Sample Superstore sales data (9,994 transactions)
- Columns include sales, quantity, discount, profit, region, category, product details, and customer information
- No missing values, cleaned and ready for analysis

## Analysis Methods
- Exploratory Data Analysis (EDA) with pandas, seaborn visualizations for profit by region and category
- Correlation heatmaps to detect relationships between discounts and profits
- Linear Regression model to quantify discount impact on profit
- Scenario simulation for discount reduction impact on profit

## Key Findings
- Western and Eastern regions yield highest profits; Central and Southern perform poorer
- Technology and Office Supplies categories lead in profit margin, Furniture lags behind
- Discounts have a strong inverse correlation with profit (higher discounts reduce profit significantly)
- A 10% uniform discount reduction predicted to improve profit by $6.39 on average

## Business Recommendations
- Tailor discount policies to reduce deep discounts especially in low-profit regions
- Increase marketing focus and pricing strategies on high-margin product categories
- Use these data-driven insights to inform regional and product-level strategic decisions

## How to Run
- Open `Untitled18.html` (Jupyter Notebook HTML export) to see full code and visualizations
- Prerequisites: Python environment with pandas, seaborn, matplotlib, scikit-learn
- Run analysis scripts to replicate visualizations and regression model results

## Author
- NIKITA KHAPARDE
- Data Scientist
