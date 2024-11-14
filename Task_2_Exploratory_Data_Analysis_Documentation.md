# Task 2: Exploratory Data Analysis (EDA) - PowerCo Churn Analysis

---

## 1. Introduction

### Objective
The goal of this analysis is to investigate factors influencing customer churn at PowerCo, with a specific focus on **price sensitivity**. Through this exploratory data analysis, we aim to determine whether price sensitivity is the most influential factor in customer churn and explore its impact in comparison to other factors.

### Data Provided
- **Historical Customer Data**: Includes data on customer usage, sign-up date, forecasted usage, etc.
- **Historical Pricing Data**: Contains information on variable and fixed pricing.
- **Churn Indicator**: Specifies whether each customer has churned.

---

## 2. Understanding Price Sensitivity and Elasticity of Demand

### Price Sensitivity
Price sensitivity is defined as the degree to which customer demand changes when there is a change in the price of a product or service. For PowerCo, the "demand" pertains to **energy consumption** by customers.

### Price Elasticity of Demand
Price elasticity of demand measures how consumption levels shift in response to price changes, which helps quantify price sensitivity. 

---

## 3. Exploratory Data Analysis Approach

The following steps outline our approach for this EDA:

### Step 1: Data Types
Identify the data types of each column in the datasets to better understand the structure and ensure data types align with expected analysis.

### Step 2: Descriptive Statistics
Calculate summary statistics (mean, median, standard deviation, range, etc.) for each column. This will give insight into the central tendency and variability within the data.

### Step 3: Data Distributions
Analyze the distributions of key columns to uncover patterns, skews, or outliers that could impact customer churn or provide insight into demand variability.

### Step 4: Visualizing Relationships with Churn
Visualize churn rate against various customer and pricing features (e.g., sales channel, contract type, number of products, tenure, offer origin) to identify trends and potential drivers of churn.

---

## 4. Analysis Plan

### Goal
To evaluate the influence of price sensitivity on customer churn, comparing its impact to other factors.

### Framework
Using a framework that:
1. **Examines customer attributes** (such as contract type, products, tenure).
2. **Assesses price fluctuations** based on price data, noting columns with high variance or unique values.
3. **Investigates relationships with churn** using visualizations.

---

## 5. Next Steps

### Data Cleaning
Address any missing values, potential outliers, and data inconsistencies to ensure the data quality before deeper analysis.

### Feature Engineering
Identify new features based on patterns from this EDA (e.g., changes in usage over time, contract duration, variability in pricing) to enhance the prediction models.

### Visualization
Create distribution plots, boxplots, and bar charts to visually represent key findings from the analysis. This helps interpret the data more intuitively and supports the decision-making process.

---

## Submission

Upon completing the analysis, please submit the Python notebook file (`Task_2_EDA.ipynb`) containing your work.

