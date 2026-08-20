# GenAI Model Development Plan

## Objective

The objective is to develop a conceptual AI-assisted solution that identifies customers who may be at risk of delinquency and provides proactive, personalized support recommendations.

The solution supports human decision-making rather than automatically approving, rejecting, or penalizing customers.

---

## Proposed Model Logic

A two-stage approach was proposed.

### Stage 1 — Delinquency Risk Assessment

A predictive model would use customer financial and payment-history information to estimate delinquency risk.

Key variables include:

- Missed Payments
- Credit Utilization
- Credit Score
- Debt-to-Income Ratio
- Loan Balance
- Income
- Employment Status
- Account Tenure
- Historical payment behavior

The model would produce a delinquency probability or initial risk category:

- Low Risk
- Medium Risk
- High Risk

### Stage 2 — GenAI Recommendation

The risk assessment and relevant customer information would be provided to a GenAI system.

The GenAI system would generate:

1. Risk summary
2. Key contributing factors
3. Recommended customer-support action
4. Explanation of the recommendation

### Conceptual Workflow

Customer Data → Data Cleaning → Risk Assessment → Risk Profile → GenAI Recommendation → Human Review → Customer Support

---

## GenAI Prompt Framework

The proposed prompt follows a structured approach:

**Role:** Financial-risk support analyst

**Context:** Identify potential delinquency risk and recommend proactive customer support.

**Data:** Missed payments, credit utilization, credit score, DTI, loan balance, income, employment status, account tenure, and risk profile.

**Task:** Explain key risk factors and generate a personalized support recommendation.

**Output:** Risk summary, contributing factors, recommended action, and explanation.

**Constraints:** Do not make automatic approval or rejection decisions. Provide transparent reasoning and recommend human review for consequential actions.

---

## Model Justification

The two-stage approach separates numerical risk assessment from natural-language explanation.

The predictive component is appropriate because delinquency is a measurable historical outcome.

The GenAI component can:

- Explain analytical results in plain language
- Generate personalized recommendations
- Summarize multiple risk factors
- Support customer-service workflows
- Improve consistency of recommendations

EDA findings showed that missed payments, credit utilization, and DTI provided useful risk signals.

However, some variables showed unexpected patterns. Therefore, the model should use multiple variables rather than relying on a single factor.

---

## Accuracy Evaluation

The model should be evaluated using an unseen test dataset.

Key metrics include:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

Accuracy should not be used as the only metric because delinquent and non-delinquent customers may be imbalanced.

GenAI recommendations should also be evaluated for:

- Factual accuracy
- Relevance
- Consistency
- Explainability
- Appropriate use of customer information

---

## Fairness Evaluation

The model should be evaluated across relevant customer groups.

Metrics should include:

- False-positive rates
- False-negative rates
- Precision
- Recall
- Risk-assignment rates

Significant unexplained differences should be investigated.

---

## Responsible AI Safeguards

The proposed system should:

- Monitor for potential bias
- Check for proxy discrimination
- Protect customer information
- Provide explainable recommendations
- Maintain human oversight
- Allow human override
- Maintain appropriate audit trails

The system should operate as a decision-support tool rather than an autonomous financial decision-maker.

---

## Conclusion

The proposed solution combines predictive risk assessment with a GenAI explanation and recommendation layer.

The predictive component identifies potential delinquency risk, while GenAI converts analytical findings into clear and personalized support recommendations.

The system should be evaluated for accuracy, fairness, explainability, consistency, privacy, and responsible use.
