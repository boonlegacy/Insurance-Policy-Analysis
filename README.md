Insurance Policy & Client Data Analysis
📌 Project Overview
This project analyzes insurance policy and client data to uncover patterns in policy preferences, claim behavior, and customer demographics. The goal is to provide actionable insights for marketing strategies, risk assessment, and product optimization.

✅ Objectives
Clean and standardize raw policy and client datasets.

Handle missing values using advanced imputation techniques.

Merge multiple datasets and create a unified analytical view.

Explore relationships between demographics, premiums, and claims.

Identify policy purchase seasonality, policy combinations, and regional claim patterns.

Deliver data-driven recommendations for business decisions.

✅ Tech Stack
Languages: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn

Environment: Jupyter Notebook

Techniques:

Data Cleaning & Transformation

Missing Value Imputation (Predictive Modeling for categorical variables)

Feature Engineering (Policy Duration, Policy Combinations)

Exploratory Data Analysis (EDA)

Data Visualization (Heatmaps, Boxplots, Stacked Bar Charts)

✅ Key Steps
Data Cleaning & Preparation

Handled missing values for numerical and categorical columns.

Standardized inconsistent date formats (converted to dd-mm-yyyy).

Ensured unique policy types for each client through conditional imputation.

Merging Datasets

Combined Policy Info and Client Info datasets using INNER JOIN on Client_ID.

Exploratory Data Analysis

Correlation heatmaps for feature relationships.

Premium distribution by smoker status and age group.

Claim patterns by policy type, gender, and region.

Advanced Analysis

Policy purchase seasonality using stacked bar charts & heatmaps.

Policy combination analysis per client.

BMI and smoking impact on policy preferences.

Insights & Recommendations

Dental and Vision policies show the highest claim frequency and amount.

Life and Health policies preferred by males; Vision by females.

Clients aged 30–39 purchase the most policies.

South region shows highest claim activity.

Recommended bundling Life + Health + Dental and targeted campaigns for age 30–39 and South region.

✅ Visualizations
Policy Preference by Gender & Age

Claim Frequency & Amount by Policy Type

Policy Purchase Seasonality (Heatmap & Stacked Bar Chart)

Top Policy Combinations

BMI vs Policy Type

Premium vs Smoker Status

✅ Business Impact
Helps insurance providers identify profitable segments and high-risk policies.

Supports data-driven marketing (seasonality, regional targeting).

Optimizes product bundling strategies for better customer retention.

📂 Project Files
client_info.csv – Raw client dataset.

policy_info.csv – Raw policy dataset.

insurance_analysis.ipynb – Main analysis notebook with EDA and visualizations.

cleaned_data.csv – Preprocessed merged dataset.
