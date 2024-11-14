# Task 1: Business Understanding & Hypothesis Framing

## Task Overview

**Objective**: Understand the business problem PowerCo faces with customer churn and outline a data-driven approach to analyze it. This task involves framing the problem within the BCG X 5-step data science methodology and identifying the data and techniques needed to investigate potential factors impacting churn.

## Business Context

### Client: PowerCo
PowerCo is a gas and electricity utility company that serves small and medium-sized enterprises (SMEs). Recently, PowerCo has faced increasing customer churn, with more clients switching to competitors. This project aims to uncover the reasons behind this churn, particularly examining the role of price sensitivity in customers’ decisions to leave or stay.

### Key Business Question
How can PowerCo reduce customer churn and retain SME clients effectively, particularly in a highly competitive market with fluctuating prices?

## BCG X 5-Step Data Science Methodology

This project will follow the BCG X 5-step approach, which includes:
1. **Business Understanding & Problem Framing**: Define the client's issue in a business context and outline data science solutions.
2. **Exploratory Data Analysis & Data Cleaning**: Examine the data, check for quality issues, and preprocess for analysis.
3. **Feature Engineering**: Generate meaningful features, especially related to price sensitivity and customer behavior.
4. **Modeling and Evaluation**: Develop predictive models to assess churn risk and quantify factors impacting retention.
5. **Insights & Recommendations**: Deliver actionable insights to PowerCo for strategic decision-making.

## Hypothesis Framing

To investigate customer churn, we hypothesize that several factors may be influencing PowerCo’s SME customers’ retention, with price sensitivity as a primary driver. Other potential factors include:

1. **Price Sensitivity**: Customers may be leaving due to high or uncompetitive prices.
2. **Energy Source Preferences**: Preferences for clean or renewable energy may impact customer loyalty.
3. **Customer Service Quality**: Quality of service, such as responsiveness to issues, could influence retention.
4. **Business Demographics**: Customer attributes like industry, size, and location may correlate with churn.
5. **Contract Flexibility**: Contract terms, such as cancellation fees, could affect customer decisions.

## Data Requirements

To explore these hypotheses, we propose obtaining the following data from PowerCo:

- **Pricing Data**: Historical price data for electricity and gas, ideally at granular intervals.
- **Churn Data**: Indicators of churn status and reasons, if available.
- **Customer Demographic Data**: Attributes such as industry, business size, and location.
- **Customer Service Data**: Records of service interactions, satisfaction scores, and resolution times.
- **Billing and Payment Data**: Patterns in billing (e.g., late payments) that might indicate dissatisfaction.
- **Energy Preferences**: Information on preferences for renewable energy sources.

## Analytical Approach

### Techniques for Analysis
Once the data is collected, we will use the following techniques:

1. **Exploratory Data Analysis (EDA)**: To identify patterns and trends related to price sensitivity, churn rates, and customer demographics.
2. **Segmentation Analysis**: To group customers by characteristics (e.g., industry or location) and examine differences in churn.
3. **Correlation Analysis**: To quantify relationships between factors like price changes and churn.
4. **Predictive Modeling**: Using classification models (e.g., Logistic Regression, Random Forest) to predict churn risk and assess key factors.
5. **Data Visualization**: Visual tools, such as heatmaps and scatter plots, will illustrate findings and clarify trends in customer behavior.

### Expected Outcomes
Our analysis will yield insights into which factors most strongly influence churn, helping PowerCo tailor retention strategies. If price sensitivity is confirmed as a significant driver, PowerCo can consider strategic pricing adjustments or targeted offers for price-sensitive segments.

## Example Approach Outline

**Email to Associate Director (AD): Proposed Approach for PowerCo Customer Churn Analysis**

---

**Subject:** Proposed Approach for PowerCo Customer Churn Analysis

Dear Associate Director,

Estelle and I have developed an initial plan to address PowerCo’s concerns regarding customer churn, using the BCG X 5-step data science methodology. Our goal is to uncover the primary factors influencing customer retention, with a specific focus on price sensitivity.

### Problem Framing

PowerCo is concerned that their SME customers may be switching providers due to pricing competitiveness and other factors. Our objective is to analyze customer behavior, pricing, and service satisfaction data to pinpoint the drivers of churn and propose actionable retention strategies.

### Key Factors Affecting Customer Retention

We believe the following factors are likely to impact retention decisions:
1. **Price Sensitivity**: Whether PowerCo’s pricing is competitive compared to alternatives.
2. **Energy Source Preferences**: Clean energy as a potential differentiator.
3. **Customer Service Quality**: Responsiveness and issue resolution quality.
4. **Business Demographics**: Including industry, location, and business size.
5. **Contract Flexibility**: Terms of service flexibility, such as contract durations.

### Data Requirements

To evaluate these factors, we will need:
- **Historical Pricing Data**: Details on PowerCo’s pricing over time and ideally competitor data if available.
- **Churn and Retention Data**: Records of customer churn, including associated dates and reasons.
- **Demographic Data**: Attributes such as business industry, size, and geographic location.
- **Customer Service Data**: Logs of customer service interactions, with satisfaction scores.
- **Billing and Payment History**: Any patterns that may indicate dissatisfaction, such as frequent late payments.
- **Energy Source Preferences**: Indications of customer priorities for renewable or clean energy sources.

### Analytical Techniques

To analyze and test our hypotheses, we propose:
1. **Exploratory Data Analysis (EDA)**: Initial inspection of trends and relationships related to churn.
2. **Segmentation Analysis**: Grouping customers by demographic and industry variables to explore churn differences.
3. **Correlation Analysis**: Identifying correlations between key variables, such as pricing and churn rates.
4. **Predictive Modeling**: A model to predict churn risk based on identified factors (e.g., logistic regression).
5. **Data Visualization**: Visual representation of churn trends, price sensitivity, and location-based analysis.

This approach aims to deliver insights PowerCo can use to reduce churn and increase customer satisfaction. Please let us know if additional considerations should be included.

Best regards,  
Alisha  
Junior Data Scientist, BCG X  

---

