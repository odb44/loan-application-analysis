# loan-application-analysis
Loan application data cleaning, exploratory analysis, and business insights.
# Loan Application Analysis

## Project Overview

This project analyzes historical loan application data to understand applicant profiles and loan demand.

The analysis focuses on identifying patterns in applicant demographics, financial characteristics, credit history, requested loan amounts, repayment terms, and property areas that can support more structured loan assessment and loan-product planning.

## Use Case

A lending institution wants to better understand its loan applicants and the types of loans they request.

Using historical loan application data, the analysis examines:

- Applicant demographics and employment characteristics
- Applicant and coapplicant income
- Credit history
- Requested loan amounts and repayment terms
- Education and property area

The goal is to identify meaningful patterns that can support more structured loan assessment and loan-product planning.

## Dataset

The dataset contains **981 loan applications** and **12 variables** covering applicant, financial, credit, loan, and property information.

## Project Process

The project follows this workflow:

**Raw Data → Data Cleaning → Exploratory Data Analysis → Insights → Business Decision**

### Data Cleaning

The dataset was assessed and cleaned for:

- Missing values
- Inconsistent categorical values
- Spelling variations
- Unusual numerical values
- Uncommon loan-term values
- Duplicate records

### Exploratory Data Analysis

The analysis examines:

- Applicant demographics
- Education and employment characteristics
- Income distributions
- Loan amount distributions
- Loan repayment terms
- Credit history
- Relationships between income and loan amount
- Loan amounts across education and property areas
- Relationships between numerical variables

## Key Business Insight

The analysis shows that loan applicants have varied demographic, financial, and credit profiles. Income, coapplicant income, credit history, requested loan amount, and applicant characteristics provide useful information for understanding loan demand and supporting structured applicant review.

## Business Decision

The findings can support a more structured loan assessment process by encouraging the business to consider multiple applicant and loan characteristics together rather than relying on a single variable.

The patterns can also help the business understand common loan amounts and repayment terms when planning loan products.

## Project Files

```text
loan-application-analysis/
│
├── data/
│   ├── raw_data.csv
│   └── cleaned_loan_data.csv
│
├── notebooks/
│   └── Loan_Application_Analysis_Seun.ipynb
│
├── presentation/
│   └── Loan_Application_Data_Analysis_Bamigbele_Oluwaseun.pptx
│
└── README.md
```

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Git & GitHub

## Author

**Oluwaseun Bamigbele**
