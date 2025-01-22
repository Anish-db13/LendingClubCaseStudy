# Lending Club Case Study
## Problem Statement

You work for a consumer finance company which specializes in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

- **Risk 1:** If the applicant is likely to repay the loan, then not approving the loan results in a **loss of business** to the company.
- **Risk 2:** If the applicant is not likely to repay the loan (i.e., likely to default), then approving the loan may lead to a **financial loss** for the company.

## Objective

Use **Exploratory Data Analysis (EDA)** to understand how **consumer attributes** and **loan attributes** influence the tendency of default.

## Constraints

When a person applies for a loan, there are two types of decisions that could be made by the company:

- **Loan accepted:** If the company approves the loan, there are 3 possible scenarios:
  - **Fully paid:** Applicant has fully paid the loan (the principal and the interest rate).
  - **Current:** Applicant is in the process of paying the installments; the loan tenure has not yet been completed. These candidates are not labeled as **‘defaulted’**.
  - **Charged-off:** Applicant has not paid the installments on time for a long period of time and has defaulted on the loan.

- **Loan rejected:** The company rejected the loan because the candidate does not meet their requirements. Since the loan was rejected, there is **no transactional history** of those applicants with the company, and thus, this data is **not available** in this dataset.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information

This project aims to analyze factors contributing to loan defaults, identify trends, and provide actionable insights to mitigate financial risks for lenders.

### Background

Loan defaults pose a significant risk to financial institutions, impacting profitability and stability. By analyzing historical loan data, we can uncover patterns and risk factors associated with defaults, helping lenders make informed decisions during the loan approval process.

### Business Problem

The primary objective is to answer critical business questions:
- What are the key factors leading to loan defaults?
- Which applicant profiles are more likely to default?
- How can lenders optimize their risk assessment processes to minimize defaults?

### Dataset

The dataset used in this project contains **39,717 rows** and **111 columns** of historical loan data, including attributes related to:
- **Loan information**: Amount, term, interest rate
- **Applicant demographics**: Income, homeownership status
- **Loan purpose**: Reasons for the loan
- **Credit history**: Bankruptcy records and delinquencies

The dataset underwent extensive cleaning and preprocessing to ensure the quality and reliability of insights.


## Conclusions

- Income ranges between **0-20,000** have a higher likelihood of loan defaults.
- Interest rates greater than **16%** show a significant risk of loan defaults compared to lower-rate categories.
- Applicants who **do not own homes** are more likely to default on loans.
- Loans taken for **small businesses** have a higher probability of defaults.
- High **Debt-to-Income (DTI)** ratios correlate with increased default risk.
- Applicants with **higher bankruptcy records** are more prone to loan defaults.
- **Delaware (DE)** holds the highest number of loan defaults among all states.
- Loan applicants with **Grade G** have the highest default rate, while those with **Grade A** have the lowest.

## Technologies Used

- pandas - version 1.3.3
- numpy - version 1.21.2
- seaborn - version 0.11.2
- matplotlib - version 3.4.3
- scikit-learn - version 0.24.2

<!-- As the libraries' versions keep on changing, it is recommended to mention the version of the library used in this project -->

## Acknowledgements

Give credit here:
- This project was inspired by data analysis techniques learned from the [Lending Club Dataset Analysis].
- References: [Pandas Documentation](https://pandas.pydata.org/), [Seaborn Documentation](https://seaborn.pydata.org/).
- This project was based on [this tutorial](https://www.example.com).

## Contact

Created by [@anishdb13](https://github.com/anishdb13) - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
