# LOAN-APPROVAL-ANALYSIS
Perform an Exploratory Data Analysis (EDA) on a dataset related to loan approval.
# Loan Approval Analysis (EDA + Dashboard)

**Goal:** Explore borrower patterns and identify factors that influence loan amounts and approvals.

## Dataset
Columns: Loan_ID, Gender, Married, Dependents, Education, Self_Employed, ApplicantIncome, CoapplicantIncome, LoanAmount, Loan_Amount_Term, Credit_History, Property_Area.

- Rows: ~614 (typical Kaggle version)
- Target (if available): LoanAmount
- **Data source:** [(https://drive.google.com/file/d/1lCRryHkGizmdtDMK3DbVjAeWkZUCdMkz/view)]

## What I did
- Data cleaning: handled missing values (LoanAmount, Credit_History…)
- Univariate, bivariate, multivariate analysis
- Visualizations (Seaborn/Matplotlib)
- Business insights + recommendations
- Power BI dashboard

## Key Insights
- Credit history is the strongest approval driver.
- Married graduates tend to secure higher average loans.
- Self-employed borrowers show higher variance; some groups take larger loans.
- Property area: Urban/Semi-Urban dominate loan disbursals.
- Income vs LoanAmount: only mild correlation; tenure mostly 360 months.

## Folder Structure
