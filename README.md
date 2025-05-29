# ABZ - Loan Default Dashboard
## Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning and Preparation ](#data-cleaning-and-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Cleaning and Preparation ](#data-cleaning-and-preparation)
- [Results and Findings](#results-and-findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [Collaborators](#collaborators)
- [References](#references)
  
### Project Overview
This data analysis project aims to provide insights into the underlying factors causing an increase in Loan defaults by customers at ABZ Limited. By analysing various aspects of the data, we seek to identify trends, make data-driven recommendations, and gain a deeper understanding of the ABZ customers' Loan Behaviour.

<img width="704" alt="Loan_Dashboard_1" src="https://github.com/user-attachments/assets/addc468e-0eb8-4711-8ef4-2d708ad36245" />

<img width="675" alt="Loan_Dashboard_2" src="https://github.com/user-attachments/assets/7f165c82-09dd-47ee-ae5b-ad5af64773d4" />

### Data Sources
Loan Data: The primary dataset used for this analysis is the "loan_info.csv" file, which contains detailed information about each customer's loan details provided by the company.

### Tools
-  Excel - Data Analysis
-  Power BI - Creating reports
  
### Data Cleaning and Preparation
In the initial data preparation phase, we performed the following tasks:
-  Data loading and inspection.
-  Handling missing values.
-  Data cleaning and formatting.
  
### Exploratory Data Analysis
EDA involved exploring the loan data to answer key questions, such as:
-  What is the overall Loan Trend?
-  What is the effect of loan grade on loan performance?
-  What is the total number of clients in the company?
-  What is the total number of defaulters in the company?
-  What is the total outstanding loan balance?

### Results and Findings
The analysis results are summarised as follows:
1. Default Rate (13.95%)
   Nearly 14% of clients have defaulted—a red flag for credit risk.
   Indicates the need for stricter risk assessment and borrower profiling.
2. Most Defaults Occur in Lower Loan Grades
3. Defaults Are Linked to High and Medium DTI
   Borrowers with high or medium debt-to-income (DTI) ratios are typically responsible for the majority of the defaulted loan balance.
   This shows a strong correlation between DTI and default risk.
4. Average Interest Rate for Defaulters is 14%
   This suggests that risk-based pricing is in use, but may not be effective enough.
   High interest rates might be increasing the repayment burden for already risky clients.
5. Large Total Loan Amount vs. Smaller Outstanding Balance
   The total loan amount issued is 581M, but only 35.98M is still outstanding, suggesting many loans have been fully repaid or written off due to defaults.
   
### Recommendations
Based on the analysis, we recommend the following actions:
1. Tighten Lending Criteria for Risky Loan Grades
2. Enforce Stricter DTI Thresholds.
   Set a maximum allowable Debt-to-Income (DTI) ratio (e.g., below 35%) for new loans.
   Use DTI as a core eligibility metric and reject or flag applicants in the High DTI category.
3. Review and Redesign Risk-Based Interest Rates
   Offer graduated or performance-based rate reductions for timely repayments.
4. Introduce Early Warning and Intervention Systems
   Use data to flag off borrowers showing signs of financial distress (e.g., high DTI + rising balance).
   Offer loan restructuring, grace periods, or financial counselling to prevent default escalation.
5. Improve Post-Disbursement Monitoring
   Establish a real-time dashboard to track at-risk loans by grade, DTI, and payment behaviour.
   Automate alerts for missed payments or changes in borrower risk profiles.
6. Incentivise Repayment for At-Risk Groups
   Provide incentives, interest rate discounts, credit score improvements, or rewards for borrowers in risk-prone categories (Grades C–E) who maintain consistent repayment.
   
### Limitations
    We had to replace null values in the Annual income column with the average values of entries with values.
    We also remove all duplicate entries in order to get an unbiased result.
    
### Collaborators
-  [@efoosag](https://www.linkedin.com/in/efoosag)
-  [@Mercysmart](https://www.linkedin.com/in/mercy-mercysmart-338628218/)
   
### References
-  [Stack Overflow](https://stack.com)

