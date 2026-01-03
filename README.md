<img width="1907" height="1000" alt="image" src="https://github.com/user-attachments/assets/bbba0ce6-417a-47ec-a274-d0fb4e483e1e" />
Link for dashboard : https://public.tableau.com/views/Paisabazaar_Credit_Score_Analysis/Dashboard2?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

# Paisabazaar Credit Score Analysis (EDA + Dashboard)

## Project Overview
This repository presents an end-to-end Exploratory Data Analysis (EDA) workflow focused on credit risk detection and profiling using customer, financial, and behavioral data from Paisabazaar.  
The objective is to uncover actionable risk drivers, analyze fraud-prone patterns, and create a strong analytical foundation for future predictive modeling and credit decision systems.






## Dataset Description
- Dataset Size: 100,000 customer records  
- Columns: 28 features covering demographic, income, credit, and behavioral attributes  

### Key Variables
- Customer Attributes: Age, Occupation, Region  
- Financial Metrics: Annual Income, Outstanding Debt, EMI  
- Credit Indicators: Credit Score, Credit Utilization Ratio, Delay from Due Date  
- Engineered Risk Indicators: Debt-to-Income, EMI-to-Salary, Risk Score  

### Data Cleaning
- Removed duplicate records  
- Performed missing value checks and corrections  
- Applied domain-based outlier capping to maintain financial realism  

## Analysis Workflow

### Univariate Analysis
Analyzed individual feature distributions to understand data spread and skewness.
- Features: Annual Income, Debt-to-Income Ratio, Age  
- Visualizations: Histograms, Boxplots, Countplots  

### Bivariate Analysis
Explored relationships between customer attributes and financial risk indicators.
- Use cases: Income vs Credit Score, Occupation vs Debt  
- Visualizations: Boxplots, Violin plots, Grouped bar charts  

### Multivariate Analysis
Identified high-risk customer segments by combining multiple variables.
- Feature combinations: Age, Income, Region, Credit Score  
- Visualizations: Pairplots, Correlation Heatmaps  

## Feature Engineering
Created domain-driven features to enhance risk profiling:
- Debt_to_Income
- EMI_to_Salary
- Delay_Ratio
- High_Utilization_Flag
- Negative_Balance_Flag
- Risk_Score (composite risk indicator)

## Outlier Handling
- Applied winsorization to major financial metrics  
- Selectively removed rare and extreme ratio-based anomalies  

## Insights and Business Impact
- Developed actionable risk profiles for targeted loan and credit offerings  
- Provided data-backed recommendations for credit policy optimization  
- Identified strategies to reduce loss exposure and benchmark risk behavior  

## Getting Started

### Prerequisites
- Python 3.8 or higher

### Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Future Scope
- Predictive credit risk modeling  
- Fraud detection using supervised machine learning  
- Integration with real-time credit decision systems  

## Author
Ankita Sharma  
Final Year B.Tech (Computer Science)  
Aspiring Data Analyst / Risk Analytics Engineer

