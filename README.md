# Customer Subscription Retention Analysis
## Overview
This project analyzes a real-world consumer subscription dataset to identify custoemrs most likely to remain active or on-hold. These customer segments are important because they reporesent continueous revenue streams.

The original dataset was messy, with undefined columns, test records, and missing values. This reflects the type of raw, imperfect data analysts often encounter in production. The project demostrates my ability to clean messy data, extract signal from noise, and build predictive models despite limitations.

## Key Steps
1. ### Data Cleaning & Preparation
* Removed test records and irrelevant identifiers (name, address, etc.).
* Standardized values across non-numerical columns.
* Handlded missing values across all columns.
* Explored outliers in reveue distribution to assess their impact on modeling.

2. Exploratory Data Analysis (EDA)
   * Box plots and histograms of total revenue distribution (identified heavy outliers).
   * Initital feature importance exploration with tree-based models.
     
3. Predictive Modeling
   * Objective: Classify customers as "Active/Hold" (likely continuous spenders) vs. others.
   * Models tested: Logistic Regression, Random Forest, Gradient Boosting.
   * Results: Precision ranged from 0.55-0.60. Modest performance due to dataset limitations, but sufficient to highlight signal in certain features.

## Challenges & Learnings
* Messy real-world data: Required careful assumptions and data cleaning before modeling.
* Feature gaps: Limited varibles restricted predictive power, highlighted importance of high-quality data pipelines in analytics engineering.
* Interpretability: Even with moderate accuracy, the project demonstrates how to extract actionable insights for acquiring high potential customers.

## Why This Project Matters
Companies with subscription model live or die by retention. This project shows my ability to:
* Work with messy, incomplete data and still deliver insights.
* Apply predictive modeling in a customer retention context.
* Bridge data science + business thinking to focus on continuous revenue drivers.

  
