Fashion-Trend-Analysis
Welcome to the Fashion Trend Analysis project repository! This project explores a fashion product dataset containing 31,582 product records to understand product categories, brands, product types, pricing, discounts, gender-based preferences, and price segments. It uses Python for data exploration, analysis, and visualization. This README file provides essential information to get started with the project.
Getting Started
- Dataset: Use the Fashion_Trends.csv dataset containing fashion product details such as brand, category, product name, gender, original price, discounted price, discount percentage, and price segments.
- Data Exploration: Load the dataset into a Pandas DataFrame and inspect its structure, missing values, data types, and numerical summaries.
- Analysis: Explore brands, categories, product types, discount tiers, gender-based preferences, and price segments through grouping and visualizations.
Features
- Data Preparation: Check missing values and inspect column data types to understand the quality and structure of the dataset.
- Exploratory Data Analysis (EDA): Analyze categorical and numerical features using frequency distributions and descriptive statistics.
- Brand & Category Analysis: Identify leading brands and the most common fashion categories, including their distribution across price segments.
- Product Type Analysis: Compare popular product types across genders and categories.
- Discount Analysis: Examine discount tiers, average discounts by product type, category-level discount patterns, and the relationship between original and discounted prices.
- Gender-Based Preferences: Compare product counts and average discount percentages across gender groups.
- Price Segment Analysis: Study product distribution across Budget, Mid, Premium, and Luxury segments and compare brand representation.
Analysis Breakdown
- Data Preparation & EDA: The notebook checks missing values and data types, explores categorical features, and summarizes numerical columns. The dataset contains 31,582 products, with an average original price of ₹1,418 and an average discounted price of ₹930. The average discount is 32.98%.
- Brand & Category Analysis: Topwear has the highest product count (7,110), followed by Westernwear (6,641) and Footwear (6,030). The Mid-price segment contains the most products (18,237).
- Product Type Analysis: Women's products account for 17,207 records, compared with 14,375 men's products. Straight Kurta (2,113) and Fit Shirt (2,087) are the leading product types reported in the notebook.
- Discount Analysis: Around 15,194 products (48.11%) have discounts above 40%, while 8,107 products (25.67%) have no discount. Original and discounted prices have a positive correlation of 0.82.
- Gender-Based Preferences: Men's products have an average discount of 33.32%, while women's products have an average discount of 32.69%.
- Price Segment Analysis: The Mid-price segment (₹500–₹1,499) has the highest product count at 18,237 (57.74%), while the Luxury segment has 501 products (1.59%). Performax has the highest product count among brands, with 3,029 products.
Usage
You can access, view, and edit this project using Python. This repository contains a Jupyter Notebook, so open Fashion_trend_analysis.ipynb using Jupyter Notebook, JupyterLab, or Google Colab.

Install the required Python libraries (pandas, seaborn, and matplotlib) before running the notebook.

The notebook loads the dataset from ../Datasets/Fashion_Trends.csv. Keep the CSV file in the expected Datasets folder relative to the notebook, or update the file path in the dataset-loading cell to match your folder structure.

To install the required libraries, run:
pip install pandas seaborn matplotlib


Description
This project is a Python-based fashion data analysis project. It uses Pandas for data handling and analysis, and Seaborn and Matplotlib for data visualization. The analysis focuses on understanding fashion product distribution, brand and category trends, discount patterns, gender-based product representation, and pricing segments.
Contributing
We welcome contributions from the community. If you find any issues or have suggestions for improvement, please open an issue or create a pull request.
