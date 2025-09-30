Project Overview:

This repository contains an exploratory data analysis (EDA) workflow for detecting and profiling banking risk using customer, financial, and behavioral data from Paisabazaar. The goal is to extract actionable insights on risk factors and fraud occurrences and provide a robust basis for predictive modeling.

Data Description
Dataset size: 100,000 records, 28 columns (demographic, income, credit, payment, behavioral)

Key Variables: Customer attributes (Age, Occupation, Region), Credit Score, Annual Income, Outstanding Debt, Delay from Due Date, Credit Utilization Ratio, and engineered risk indicators.

Data Cleaning: Duplicate removal, missing value checks, and domain-based capping of outliers.


Analysis Steps:

Univariate Analysis:

Explores distributions of features such as Annual Income, Debt-to-Income Ratio, and Credit Score.

Charts: Histograms, Boxplots, Countplots.

Bivariate Analysis:

Investigates relationships between customer/financial features and fraud rate (e.g., Age vs Fraud_Flag, Occupation vs Fraud_Flag, Credit Utilization vs Credit Score).

Charts: Boxplots, Violin plots, Grouped barplots.

Multivariate Analysis:

Identifies high-risk clusters by combining features (e.g., Age, Income, Region, Credit Score).

Charts: Pairplots, Heatmaps, FacetGrids.

Feature Engineering:

Engineered columns: Debt_to_Income, EMI_to_Salary, Delay_Ratio,High_Utilization_Flag, Negative_Balance_Flag, Risk_Score (composite).

Outlier Handling:

Winsorization for main financial metrics; selective removal for rare/extreme ratio values.

Insights & Business Impact

Actionable risk profiles for loan and credit product targeting.

Recommendations for credit policy based on quantitative and visual evidence.

Strategies for lowering loss amounts and benchmarking against other companies.


Getting Started
Prerequisites
Python 3.x (recommended 3.8+)

pandas, numpy, seaborn, matplotlib, scikit-learn
