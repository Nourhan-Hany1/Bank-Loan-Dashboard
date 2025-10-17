# Bank-Loan-Dashboard (using Power Bi)
## Project Objective
I built an interactive Power BI dashboard of the US bank to analyze loan performance and customer trends in 2021. This dashboard provides a comprehensive analysis of bank loan performance by combining customer demographics and financial data. It enables stakeholders to track loan metrics, assess portfolio quality, and identify patterns in borrower behavior to support data-driven decision-making.

## Dataset used
[financial_loan_data.csv](https://github.com/Nourhan-Hany1/Bank-Loan-Dashboard/blob/main/financial_loan_data.csv)

## 🧱 Data Model & Preparation
The dataset was divided into two core tables:

Customer Data: Included descriptive borrower information such as employment length, home ownership, loan grade, and loan purpose.

Financial Data: Contained loan-specific metrics, including funded amount, received amount, interest rate, and DTI.

Established a 1:1 relationship between both datasets using Customer ID to ensure precise data mapping and integrity.

Performed data transformation and cleaning in Power Query to ensure consistency, remove nulls, and standardize numeric and date fields.

## ⚙️ Data Modeling & Calculations
Developed multiple DAX measures to calculate key performance indicators, including:

Total Loan Applications, Total Funded Amount and Received Amount, Month-to-Date (MTD) and Month-over-Month (MOM) growth, Average Interest Rate and Average DTI, Good vs. Bad Loan Ratios

Implemented a loan classification logic:

Good Loans: Current and Fully Paid

Bad Loans: Charged Off

Incorporated interactive slicers for State, Grade, Purpose, and Good vs. Bad Loans, enabling dynamic analysis and user-driven insights.
