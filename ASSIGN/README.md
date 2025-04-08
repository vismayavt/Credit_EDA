# Credit-EDA

## Project Overview
This case study aims to identify patterns that indicate whether a client has difficulty paying their installments. The insights derived from this analysis can be used to take actions such as:
- Denying the loan
- Reducing the loan amount
- Lending to risky applicants at a higher interest rate

The goal is to ensure that consumers capable of repaying the loan are not rejected, while accurately identifying applicants who may struggle to repay their loans.

## Data Sources
The dataset consists of three key files:

1. **application_data.csv**: Contains information about the client at the time of application. This data is used to determine if the client has payment difficulties.
2. **previous_application.csv**: Includes data on the client’s previous loan applications, such as whether the previous application was approved, cancelled, refused, or marked as unused.
3. **columns_description.csv**: A data dictionary that describes the meaning of the variables.

## Tools
- **Python Notebook** for data analysis and exploration

## Data Cleaning/Preparation
The initial data preparation phase involves the following tasks:
- **Data Loading and Inspection**: Loading and checking the data for issues.
- **Handling Missing Values**: Identifying and addressing any missing values in the data.
- **Data Cleaning and Formatting**: Standardizing and cleaning the data to ensure accuracy.

## Exploratory Data Analysis (EDA)
EDA is used to analyze the patterns present in the data, such as outliers and data imbalance. The analysis helps to understand how different consumer and loan attributes influence the likelihood of loan defaults.

Key Points:
- **Client with Payment Difficulties**: A client is considered to have payment difficulties if they have missed payments for more than X days on at least one of the first Y installments of the loan.
- **Other Cases**: All cases where the payment is made on time.

### Loan Decision Types:
- **Approved**
- **Cancelled**
- **Refused**
- **Unused Offer**

## Data Analysis
The analysis conducted follows a structured and clear flow:
- **Univariate Analysis**: Analyzing individual variables.
- **Segmented Univariate Analysis**: Breaking down univariate analysis by different segments.
- **Bivariate Analysis**: Exploring relationships between two variables.

## Presentation and Recommendations
The presentation of results has a clear structure, is concise, and explains the most important findings in simple language. The recommendations derived from the analysis are actionable and aligned with the business needs.

### Key Recommendations:
1. **Groups with Higher Unsuccessful Payment Rates**:
   - Clients with 'Secondary/Secondary Special' education qualification.
   - Clients who are 'Young', especially with 'Low' income.
   - Clients whose loans were 'Refused' or 'Cancelled'.

2. **Groups with Higher Successful Payment Rates**:
   - Clients with 'Approved Consumer' loans.
   - Loans for 'Tourism' goods have the highest success payment rate.
   - The 'Senior Citizen' age group has the highest success payment rate.

## Conclusion
The analysis reveals key insights that can help banks refine their lending strategies and minimize the risk of defaults, ensuring that they focus their efforts on the right applicants.

