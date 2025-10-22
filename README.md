# Supermarket Sales and Profitability Performance Analysis
### 1. Project Summary
This project is a comprehensive data science study conducted to examine the business performance of a supermarket chain using sales data from 2014 to 2017. The project aims to identify the company's growth trends, regional and categorical profitability issues, and measure the critical impact of discount strategies on profitability using both Exploratory Data Analysis (EDA) and Machine Learning (ML) methods.

Main Objectives
Identify sales and profit trends over time.

Identify which product categories and regions are causing losses.

Use machine learning to prove the most important factors affecting profit (Feature Importance).

### 2. Data Set Used
Data Source: Supermarket Sales Data Set (Superstore.csv)

Content: Consists of 21 different columns, including Order ID, Customer ID, Order Date, Product Category, Region, Sales, Quantity, Discount, and Profit.

### 3. Analysis Stages and Methodology
A. Data Preparation and Exploratory Data Analysis (EDA)
Data Cleaning: Date columns (Order Date, Shipment Date) were converted to date-time type.

Time-Based Analysis: Annual and trend-based performance was examined, determining that 2017 was the best year.

Categorical Analysis: The furniture category (especially the Table and Bookshelf subcategories) was found to cause high losses.

Critical Relationship Analysis: The direct relationship between the discount rate and average profit was visualized, proving that discounts of 30% and above led to losses on average.

B. Profit Prediction with Machine Learning (ML)
A supervised learning model was used for profit prediction.

Model: Random Forest Regressor

Features: Sales, Quantity, Discount, Category, Subcategory, Region, Segment, etc.

Performance Metric: Mean Absolute Error (MAE)

## Key Findings and Business Insights
### 4. Technical Details
Development Environment and Libraries
Programming Language: Python

Libraries:

pandas: Data Processing

matplotlib & seaborn: Exploratory Data Analysis and Visualization

scikit-learn: Machine Learning Model (RandomForestRegressor)

Installation and Execution
To run the project in your local environment:

Install the Required Libraries:

Download the Data: Place the Superstore.csv file in the project's root directory.

Run the Code: Run the Python script containing all analysis steps and the ML model.

(Note: If you are running the code in Jupyter Notebook, open the relevant notebook.)

### 5. License
This project is licensed. You can review the license file for usage and distribution details.
