# FinGrow-Case-Study-Churn-Defaults
📊 This project explores a mock lending dataset (customers, loans, transactions) to understand loan default risks and customer churn patterns.

🔹 Objective

FinGrow Finance Ltd. (mock company) is facing two key challenges:

Loan default rates are increasing 📉

Customer acquisition costs are high, but many customers churn within 12 months ⏳

The goal is to uncover which customer groups are risky vs. profitable and provide insights on where to focus vs. exit.

🔹 Dataset Structure

The dataset consists of 3 core tables:

Customers – demographics, income, region, churn flag

Loans – loan type, amount, interest rate, status (Active, Closed, Defaulted)

Transactions – loan payments, credit card payments, fees, withdrawals

🔹 Analysis (SQL)

Some of the questions explored so far:

What is the overall churn %? How does it vary by region and income group?

What is the default rate by loan type, region, and income group?

Do low-income customers churn at higher rates?

Which segments are profitable vs. loss-making?

Are customers who default more likely to churn?

🔹 Dashboards (Power BI) (coming soon)

Customer Overview – active vs. churned %

Loan Risk – default rates by loan type & region

Profitability – profitable vs. loss-making customers

Churn Trends – churn % across segments

🔹 How to Use

Clone this repo

Load data from data/

Run SQL queries in sql/

Explore Power BI dashboard in powerbi/ (to be added)
