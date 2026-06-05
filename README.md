# customer-retention-analysis-dashboard

## Project Overview

This project is a complete Customer Churn Analysis and Retention Insights Dashboard built using real-world telecom customer data. The goal is to analyze customer behavior, identify churn patterns, and extract actionable business insights that help improve customer retention strategies.

Using a combination of data analysis, visualization, and business intelligence dashboards, this project uncovers why customers leave and which segments are most at risk.

##  Objectives
Analyze customer churn patterns in a telecom dataset
Identify key factors influencing customer retention
Segment customers based on risk of churn
Build visual insights using dashboards for decision-making
Provide actionable recommendations for reducing churn

##  Project Structure
customer-churn-analysis-dashboard/
│
├── data/
│   ├── WA_Fn-UseC_-Telco-Customer-Churn.csv     # Raw dataset
│   └── telco_churn_cleaned.csv                  # Cleaned dataset
│
├── notebooks/
│   └── python code of customer churn.ipynb      # Data analysis & ML workflow
│
├── dashboard/
│   ├── dashboard.pbix                           # Power BI dashboard file
│   ├── dashboard.png                            # Dashboard preview image
│   ├── dashboard.pdf                            # Exported report
│   └── dashboard 1.png                          # Additional dashboard view
│
├── visualization/
│   ├── churn_full_analysis.png                  # Complete analysis overview
│   ├── heatmap.png                              # Correlation heatmap
│   ├── high_risk_customers.png                  # High-risk customer segment
│   ├── monthly_dist_churn.png                   # Monthly churn distribution
│   ├── partner_dependents_churn.png             # Family impact on churn
│   ├── security_support_churn.png               # Support service effect
│   ├── senior_churn.png                         # Senior citizen churn trend
│   └── tenure_group_churn.png                   # Tenure-based churn analysis
│
└── README.md

##  Key Insights from Analysis
Customers with low tenure are significantly more likely to churn
Lack of tech support/security services increases churn probability
Monthly contract users show higher churn compared to yearly plans
Senior citizens have distinct churn behavior patterns
Customers without partners/dependents tend to churn more

##  Methodology
1. Data Cleaning & Preprocessing
Handled missing values
Converted categorical variables
Encoded features for analysis
2. Exploratory Data Analysis (EDA)
Distribution analysis of churn vs non-churn customers
Correlation heatmaps
Group-based segmentation (tenure, contract type, services)
3. Visualization
Matplotlib & Seaborn for statistical plots
Power BI dashboard for interactive business insights
4. Insight Generation
Identified high-risk customer groups
Derived business recommendations for retention strategies

 ## Dashboard Preview

The Power BI dashboard provides interactive insights into:

Customer segmentation
Churn probability patterns
Service usage impact
Revenue risk areas
🛠️ Tools & Technologies
Python (Pandas, NumPy)
Matplotlib & Seaborn
Jupyter Notebook
Power BI
Git & GitHub

## Business Impact

This analysis helps telecom companies:

Reduce customer churn rate
Improve customer retention strategies
Optimize service offerings
Increase long-term revenue stability

##  Future Improvements
Build a machine learning model for churn prediction
Deploy a web-based dashboard (Streamlit/Flask)
Add real-time customer risk scoring system
Integrate automated reporting pipeline

 ## Author

Waqas Khan
Computer Science Student | AI & Data Science Enthusiast
Passionate about solving real-world problems using data

⭐ If you like this project

Feel free to star ⭐ the repository and explore the analysis!
