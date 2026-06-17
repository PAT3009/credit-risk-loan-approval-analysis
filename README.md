# Loan Approval & Financial Risk Analysis

**End-to-End Data Analysis Project** | Python + Machine Learning

## 📋 Project Overview

This project analyzes loan application data to identify the key factors influencing loan approval decisions and evaluate borrower financial risk.

The analysis combines Exploratory Data Analysis (EDA), Risk Analysis, Correlation Analysis, and Machine Learning techniques to uncover patterns associated with loan approval outcomes.

**Core Business Question:**
*"Which client profiles are more likely to receive loan approval, and what factors drive lending decisions?"*

---

## 🎯 Business Problem

Financial institutions must balance portfolio growth with credit risk management when evaluating loan applications.

Understanding the characteristics of approved and rejected applicants helps lenders improve decision-making, optimize risk assessment processes, and identify borrower profiles associated with higher approval probabilities.

This project aims to analyze borrower demographics, financial conditions, credit history, and risk indicators to determine the primary factors influencing loan approval outcomes.

---

## 📊 Project Scope

1. **Data Understanding & Preparation**

   * Data quality assessment
   * Missing value and duplicate checks
   * Data type validation
   * Feature selection

2. **Exploratory Data Analysis (EDA)**

   * Loan approval distribution
   * Applicant demographics analysis
   * Financial profile analysis
   * Risk profile analysis

3. **Correlation Analysis**

   * Identify relationships between financial indicators and loan approval
   * Evaluate key variables influencing lending decisions

4. **Predictive Modeling**

   * Logistic Regression model development
   * Model evaluation
   * Feature importance analysis

5. **Business Insights & Recommendations**

   * Identify approval drivers
   * Provide actionable lending recommendations

---

## 📁 Dataset Summary

* **Rows:** 20,000
* **Columns:** 36
* **Target Variable:** LoanApproved
* **Approval Rate:** 23.9%
* **Missing Values:** 0
* **Duplicate Records:** 0

### Key Features

* Age
* AnnualIncome
* CreditScore
* EmploymentStatus
* EducationLevel
* LoanAmount
* DebtToIncomeRatio
* SavingsAccountBalance
* InterestRate
* RiskScore
* NetWorth
* LengthOfCreditHistory
* LoanApproved

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**
* **Jupyter Notebook**

---

## 📂 Project Structure

```text
loan-approval-financial-risk-analysis/
├── README.md
├── loan_approval_financial_risk_analysis.ipynb
├── loan_approval_financial_risk_analysis_report.pdf
├── loan_approval_financial_risk_data.csv
```

---

## 🚀 How to Use

1. Open the notebook **Loan_Approval_Financial_Risk_Analysis.ipynb**
2. Run the notebook sequentially from top to bottom
3. Explore the EDA visualizations and statistical analysis
4. Review Logistic Regression model results
5. Read the project report for detailed findings and recommendations

---

## 💡 Key Insights

* Loan approval rates decline significantly as borrower risk increases.
* Higher-income applicants demonstrate substantially higher approval rates.
* Educational attainment is positively associated with loan approval probability.
* Interest rates and loan amounts are negatively associated with approval outcomes.
* Risk Score exhibits the strongest relationship with loan approval decisions.

### Correlation Analysis

| Variable     | Correlation with Loan Approval |
| ------------ | -----------------------------: |
| AnnualIncome |                          0.598 |
| CreditScore  |                          0.142 |
| Age          |                          0.141 |
| LoanAmount   |                         -0.239 |
| InterestRate |                         -0.302 |
| RiskScore    |                         -0.766 |

---

## 🤖 Predictive Modeling

### Model

* Logistic Regression
* Target Variable: LoanApproved
* RiskScore excluded from the final model to reduce target leakage

### Model Performance

| Metric    |  Score |
| --------- | -----: |
| Accuracy  | 96.75% |
| Precision |    94% |
| Recall    |    93% |
| F1 Score  |    93% |

### Top Drivers of Loan Approval

Positive Drivers:

* Monthly Income
* Net Worth
* Length of Credit History

Negative Drivers:

* Debt-to-Income Ratio
* Interest Rate
* Loan Amount

---

## 💼 Business Recommendations

* Prioritize applicants demonstrating strong repayment capacity and financial stability.
* Strengthen monitoring procedures for high-risk borrower segments.
* Incorporate longer credit history and net worth metrics into lending strategies.
* Review pricing strategies and lending policies for borrowers with elevated debt burdens.
* Utilize data-driven risk assessment approaches to improve portfolio quality.

---

## 📸 Analysis Preview

### Loan Approval Distribution

*<img width="551" height="388" alt="image" src="https://github.com/user-attachments/assets/f89f4000-0ba1-4433-be0c-563d1789eeef" />*

### Risk Group Analysis

*<img width="690" height="543" alt="image" src="https://github.com/user-attachments/assets/8e6f195b-0476-408c-beb7-b49f548d346a" />*

### Correlation Analysis

*<img width="799" height="464" alt="image" src="https://github.com/user-attachments/assets/f01e7c7c-dbb3-4b71-8152-4877700329ed" />*

### Feature Importance

*<img width="1024" height="695" alt="image" src="https://github.com/user-attachments/assets/c4b4ae41-fda8-49a7-b565-51e264f4916f" />*

---

## 📚 References & Acknowledgements

Dataset used for educational and portfolio purposes.

Analysis performed using Python, statistical methods, and machine learning techniques to demonstrate practical data analytics and credit risk assessment workflows.

---

## 👤 Author
**Trieu Phuong Anh**   
GitHub: [@PAT3009](https://github.com/PAT3009)  
LinkedIn: https://www.linkedin.com/in/phuong-anh-trieu-30i9/
Email: phuonganht3009@gmail.com
