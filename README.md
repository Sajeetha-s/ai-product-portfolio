# Banking Fraud Detection – AI Product Requirements Document (PRD)

## 1. Problem Statement
The bank’s compliance team manually reviews thousands of flagged transactions daily for possible money laundering or fraud. Over 90% are false positives, leading to wasted effort and slower response to real threats.

## 2. Goal / Objective
Leverage AI to automatically score and prioritize transactions based on risk likelihood, enabling analysts to focus on high-risk cases and reducing false positives by at least 40%.

## 3. Target Users
- Compliance analysts  
- AML (Anti-Money Laundering) officers  
- Fraud risk management teams

## 4. Data Requirements
- Historical transaction data (amount, time, origin, destination, location, etc.)  
- Labels: “Fraudulent” or “Genuine” (based on past investigations)  
- Customer profiles, device info, and channel metadata

## 5. AI / Model Component
- Supervised ML classification model  
- Algorithms: Random Forest, XGBoost, or Neural Networks  
- Output: Fraud likelihood score (0–1)

## 6. KPIs & Success Metrics
- False positive rate ↓ 40%  
- Analyst productivity ↑ 25%  
- Model precision ≥ 90%  
- Model recall ≥ 85%

## 7. Risks / Ethical Considerations
- Model bias (unintended discrimination across geographies/customers)  
- Data privacy and anonymization before model training  
- Compliance explainability requirements for regulators

## 8. Integration Plan
- Integrate model via API into AML transaction monitoring system  
- Provide real-time scoring dashboard  
- Human-in-the-loop validation for feedback learning

---

### ✅ Expected Outcome
- Faster alert triage  
- Improved detection accuracy  
- Reduction in manual workload

---

Author: Sajeetha  
Role: AI Product Manager 
**Date:** October 2025

