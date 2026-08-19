# AI-Powered Customer Delinquency & Collections Strategy

### Tata iQ / Geldium GenAI Case Study — Forage Simulation

![GenAI](https://img.shields.io/badge/GenAI-AI%20Analytics-blue)
![Excel](https://img.shields.io/badge/Excel-EDA-green)
![Responsible%20AI](https://img.shields.io/badge/Responsible%20AI-Fairness-orange)
![Forage](https://img.shields.io/badge/Forage-Tata%20iQ-red)

## 📌 Project Overview

This project explores how data analytics, predictive risk assessment, and Generative AI can support proactive customer delinquency management.

The project was completed as a **Tata iQ / Geldium Forage case-study simulation**.

The objective was to identify customer risk factors, develop a conceptual predictive framework, create explainable GenAI recommendations, and design a responsible AI-powered collections system.

> **Note:** This is a conceptual case-study project and does not represent a production system used by Geldium.

---

## 🎯 Business Problem

Geldium needs to identify customers who may be at risk of delinquency and provide timely, personalized support.

The proposed solution aims to:

- Identify early warning signals
- Prioritize customers for proactive support
- Generate explainable recommendations using GenAI
- Improve collections efficiency
- Maintain fairness, transparency, privacy, and human oversight

---

## 📊 Exploratory Data Analysis

The analysis covered **500 customer records**.

### Key Findings

| Metric | Finding |
|---|---:|
| Total Customers | 500 |
| Delinquent Customers | 80 |
| Overall Delinquency Rate | 16.0% |
| Highest Observed Delinquency Rate | 22.1% |
| High Risk Segment Delinquency | 17.4% |

### Top Risk Indicators

1. **Missed Payments**
   - Customers with 5 missed payments had the highest observed delinquency rate of 22.1%.
   - The relationship was not consistently linear across all payment counts.

2. **Credit Utilization**
   - High-utilization customers showed a 17.4% delinquency rate.
   - Low-utilization customers showed a 12.0% delinquency rate.

3. **Debt-to-Income Ratio**
   - Average DTI was slightly higher among delinquent customers than non-delinquent customers.

### Data Quality

The analysis identified and addressed:

- Missing Income values
- Missing Credit Score values
- Missing Loan Balance values
- Employment-status inconsistencies
- Potentially unusual credit-utilization values

Median imputation was used for applicable numeric missing values, while employment-status categories were standardized.

---

## 🤖 GenAI Solution

A two-stage approach was proposed:

```text
Customer Data
      ↓
Data Cleaning & EDA
      ↓
Risk Assessment
      ↓
Risk Profile
      ↓
GenAI Recommendation
      ↓
Human Review
      ↓
Customer Support
      ↓
Outcome Monitoring
      ↓
Learning Loop
The GenAI component generates:
Risk summaries
Key contributing factors
Personalized support recommendations
Plain-language explanations
GenAI is positioned as a decision-support tool, not an autonomous credit decision-maker.
🧠 Predictive Model Framework
The conceptual risk model uses multiple customer attributes:
Missed Payments
Credit Utilization
Credit Score
Debt-to-Income Ratio
Loan Balance
Income
Employment Status
Account Tenure
Historical payment behavior
A simple rule-based risk profile was also explored as an initial screening mechanism.
The analysis showed that the risk groups had relatively modest separation, so the rule-based approach should not be treated as a production-ready predictive model.
💡 Business Recommendation
Proactive Early-Warning Collections
Geldium could pilot proactive outreach for customers showing repeated missed payments and elevated credit utilization.
SMART Goal
Within 90 days, pilot a proactive-support program for customers identified with elevated delinquency risk and target a 10% relative reduction in delinquency within the intervention group compared with a comparable control group.
The pilot should focus on supportive interventions such as reminders and appropriate repayment-support information.
🛡️ Responsible AI
The proposed system includes:
Fairness
Monitor outcomes across relevant customer groups
Compare false-positive and false-negative rates
Investigate unexplained disparities
Explainability
Show key risk factors
Provide plain-language explanations
Allow human review and challenge
Privacy & Compliance
Protect customer information
Apply appropriate access controls
Maintain audit trails
Human Oversight
No autonomous approval/rejection decisions
Escalate uncertain or high-impact cases
Allow human override
📈 Expected Business Impact
Business Outcomes
Earlier identification of at-risk customers
More efficient collections prioritization
Reduced manual analysis
Potential reduction in delinquency
Scalable customer-risk monitoring
Customer Outcomes
Earlier access to support
More personalized communication
Fewer unnecessary interventions
More consistent treatment
Greater transparency and trust
🧰 Tools & Skills
Microsoft Excel
Exploratory Data Analysis
Data Cleaning
Pivot Tables
Predictive Analytics
Generative AI
Prompt Engineering
Responsible AI
Business Analytics
Risk Analysis
Executive Communication
📁 Project Deliverables
The project includes:
EDA Summary
Predictive Model Framework
GenAI Recommendation Framework
Stakeholder Recommendation Report
AI-Powered Collections System Concept
Responsible AI Strategy
🎓 Certification
Completed as part of the Tata iQ / Geldium GenAI Forage Case Study Simulation.
👩‍💻 Author
Chaitanya Siri
Aspiring AI-Powered Data Analyst
