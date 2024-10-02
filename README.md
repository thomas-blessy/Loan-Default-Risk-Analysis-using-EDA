# Loan-Default-Risk-Analysis-using-EDA

This project is based on "EDA: Bank Loan Default Risk Analysis" by Amrita Chatterjee and Padma A, licensed under Apache 2.0 License.  While I have taken inspiration from their work, I have conducted all analyses independently and made modifications where necessary to enhance the project. The original work can be found at (https://www.kaggle.com/code/amritachatterjee09/eda-bank-loan-default-risk-analysis/notebook).

## Project Description
The primary objective of this case study is to identify patterns that indicate whether a client may struggle to pay their installments. This analysis can guide the bank in making informed decisions regarding loan approvals, such as denying loans, reducing loan amounts, or adjusting interest rates for higher-risk applicants. The goal is to ensure that clients who are capable of repaying their loans are not unjustly rejected.
To achieve this, we will focus on understanding the driving factors behind loan defaults through Exploratory Data Analysis (EDA). By identifying strong indicators of default, the bank can improve its portfolio and risk assessment strategies.

## Key Insights
### Factors Indicating Loan Repayment
After thorough analysis, several attributes were identified that suggest a higher likelihood of loan repayment:
- NAME_EDUCATION_TYPE: Clients with academic degrees tend to have lower default rates.
- NAME_INCOME_TYPE: Students and business owners show no defaults.
- REGION_RATING_CLIENT: Clients rated as 1 are considered safer.
- ORGANIZATION_TYPE: Clients from Trade Types 4 and 5 and Industry Type 8 have defaulted less than 3%.
- DAYS_BIRTH: Individuals over the age of 50 exhibit a low probability of defaulting.
- DAYS_EMPLOYED: Clients with over 40 years of experience have a default rate of less than 1%.
- AMT_INCOME_TOTAL: Applicants with an income exceeding 700,000 are less likely to default.
- NAME_CASH_LOAN_PURPOSE: Loans taken for hobbies or garage purchases are mostly repaid.
- CNT_CHILDREN: Borrowers with zero to two children tend to repay their loans consistently.

### Factors Indicating Potential Default
Conversely, certain attributes were found to correlate with a higher likelihood of default:
- CODE_GENDER: Men show a relatively higher default rate.
- NAME_FAMILY_STATUS: Individuals who are single or in civil marriages tend to default more frequently.
- NAME_EDUCATION_TYPE: Those with Lower Secondary or Secondary education levels have higher default rates.
- NAME_INCOME_TYPE: Clients on maternity leave or unemployed exhibit high default rates.
- REGION_RATING_CLIENT: Individuals living in areas rated as 3 experience the highest defaults.
- OCCUPATION_TYPE: Low-skill laborers, drivers, waitstaff, security staff, and cooks show significant default rates.
- ORGANIZATION_TYPE: Organizations in Transport (Type 3), Industry (Type 13), Industry (Type 8), and Restaurants have high percentages of unpaid loans.
- DAYS_BIRTH: Young individuals aged 20-40 are more likely to default.
- DAYS_EMPLOYED: Those with less than five years of employment experience show high default rates.
- CNT_CHILDREN & CNT_FAM_MEMBERS: Clients with nine or more children have a 100% default rate.
- AMT_GOODS_PRICE: Credit amounts exceeding 3 million show increased default rates.

### Risk Mitigation Strategies
Certain attributes indicate risks associated with loan defaults but also present opportunities for strategic lending:
- NAME_HOUSING_TYPE: A significant number of applications come from individuals living in rented apartments or with parents. Offering loans under these conditions could mitigate potential losses.
- AMT_CREDIT: Loans ranging from 300,000 to 600,000 tend to have higher default rates; thus, imposing higher interest rates on this range could be beneficial.
- AMT_INCOME: With 90% of applications having an income below 300,000 and a high probability of defaulting, these clients could be offered loans at elevated interest rates compared to other income categories.
- CNT_CHILDREN & CNT_FAM_MEMBERS: Clients with four to eight children exhibit a very high default rate; therefore, higher interest should be considered for their loans.
- NAME_CASH_LOAN_PURPOSE: Loans taken for repairs show the highest default rates. This category has seen numerous applications rejected by banks or refused by clients due to high-interest rates. Maintaining this approach would be prudent moving forward.

In conclusion, this project provides valuable insights into the factors influencing loan repayment and default risks. By leveraging these findings, banks can make informed decisions that enhance their lending strategies while mitigating potential losses.

