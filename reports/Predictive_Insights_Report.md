# Predictive Insights & Recommendation Report

## Audience

Head of Collections, Geldium

## 1. Summary of Predictive Insights

Analysis of 500 customer records identified several indicators associated with delinquency.

### Top 3 Risk Factors

#### 1. Missed Payments

Customers with 5 missed payments had the highest observed delinquency rate of 22.1%.

Repeated payment problems therefore represent an important early-warning signal.

The relationship was not consistently linear across all missed-payment levels, so missed payments should be considered alongside other variables.

#### 2. Credit Utilization

High-utilization customers had an observed delinquency rate of 17.4%, compared with 12.0% for low-utilization customers.

This suggests that higher credit utilization can be an important risk indicator.

#### 3. Debt-to-Income Ratio

Delinquent customers had a slightly higher average DTI than non-delinquent customers.

This indicates that higher debt burden may contribute to delinquency risk.

---

## High-Risk Segments

Customers with repeated missed payments and elevated credit utilization should receive increased attention from the collections team.

The initial rule-based segmentation produced:

| Risk Segment | Non-Delinquent | Delinquent | Delinquency Rate |
|---|---:|---:|---:|
| High Risk | 195 | 41 | 17.4% |
| Medium Risk | 31 | 5 | 13.9% |
| Low Risk | 194 | 34 | 14.9% |

The differences between segments are relatively modest.

Therefore, the segmentation should be treated as an initial screening mechanism rather than a validated production predictive model.

---

## 2. SMART Business Recommendation

### Proactive Early-Warning Collections

Geldium should pilot proactive outreach for customers showing repeated missed payments and elevated credit utilization.

### SMART Goal

Within 90 days, pilot a proactive-support program for customers identified with elevated delinquency risk and target a 10% relative reduction in delinquency within the intervention group compared with a comparable control group.

The pilot should focus on supportive interventions such as payment reminders and appropriate repayment-support information.

### Rationale

The analysis identified repeated missed payments and higher credit utilization as useful early-warning indicators.

Early, supportive outreach could help customers address payment difficulties before delinquency becomes more severe.

A controlled pilot would allow Geldium to measure whether the intervention actually improves outcomes.

---

## 3. Ethical and Responsible AI Considerations

### Fairness Risk 1 — Unequal Outcomes

The model may perform differently across customer groups.

#### Mitigation

Compare precision, recall, false-positive rates, and false-negative rates across relevant groups and investigate significant unexplained differences.

### Fairness Risk 2 — Proxy Discrimination

Variables such as employment status, location, or financial characteristics could indirectly act as proxies for sensitive characteristics.

#### Mitigation

Review model features for potential proxy effects and conduct regular fairness testing.

---

## Explainability

The model should be explained to stakeholders in simple language:

> "The model identifies patterns in payment behaviour and financial indicators associated with higher delinquency risk. It does not determine that a customer will become delinquent; it highlights customers who may benefit from earlier support."

GenAI should summarize and explain analytical findings rather than make autonomous financial decisions.

---

## Human Oversight

Human reviewers should:

- Review risk assessments
- Review GenAI recommendations
- Override inappropriate recommendations
- Investigate unusual cases
- Handle consequential financial decisions

---

## 4. Expected Business Impact

### Business Outcomes

- Earlier identification of at-risk customers
- Better prioritization of collections resources
- Reduced manual analysis
- Potential reduction in delinquency
- Scalable risk monitoring

### Customer Outcomes

- Earlier access to support
- More personalized communication
- Fewer unnecessary collection interventions
- More consistent treatment
- Greater transparency and trust

---

## Conclusion

The analysis indicates that missed payments, credit utilization, and DTI are useful delinquency-risk indicators.

Geldium should use these insights to support proactive customer engagement while recognizing that the current rule-based segmentation is not a production-ready predictive model.

A controlled pilot with accuracy, delinquency reduction, and fairness monitoring would provide evidence for whether the AI-assisted approach should be expanded.
