# 💰 Smart Loan Decision Intelligence Dashboard (Excel)

An end-to-end loan approval analytics dashboard built on ~50,000 customer records — designed to help a lending team understand approval rates, risk segments, and the factors driving loan decisions.

## 📌 Project Overview
This project analyzes a large loan-applicant dataset to answer a core business question: **who gets approved, who gets rejected, and why?** It covers the full analyst workflow — raw data, data cleaning, KPI calculations, pivot-based analysis, and a final interactive dashboard.

## 🎯 Objective
- Calculate core loan KPIs: total applications, approvals, and rejections
- Segment applicants by risk category (High Risk vs Low Risk) and approval outcome
- Analyze approval rates by occupation status (Employed, Self-Employed, Student)
- Break down loan amounts by intent (Debt Consolidation, Education, Business, etc.)

## 🗂️ Dataset
~50,000 customer records with fields including:
`customer_id`, `age`, `occupation_status`, `years_employed`, `annual_income`, `credit_score`, `credit_history_years`, `savings_assets`, `current_debt`, `defaults_on_file`, `delinquencies_last_2yrs`, `derogatory_marks`, `loan_amount`, `loan_intent`

## 🛠️ Tools & Techniques
- **Microsoft Excel** — data cleaning, advanced formulas
- **Pivot Tables** — multi-dimensional analysis (risk vs. approval, occupation vs. approval, loan intent vs. amount)
- **KPI Calculation Sheet** — structured summary metrics feeding the dashboard

## 📊 Workbook Structure
| Sheet | Purpose |
|---|---|
| `Raw data` | Original unprocessed applicant data |
| `Clean data` | Cleaned dataset used for analysis |
| `CALCULATION` | KPI summary (total applications, approvals, rejections) |
| `ADVANCE` | Customer-level lookup / advanced calculations |
| `PIVOT_ANALYSIS` | Pivot tables — approval by occupation, risk category, loan intent |
| `DASHBOARD` | Final interactive dashboard view |

## 🔍 Key Insights
- Roughly **55% of applications were approved** out of ~50,000 total applications
- High-risk applicants made up the majority of rejections, validating the risk-scoring logic
- Employed and Self-Employed applicants had the highest approval volumes
- Debt Consolidation and Education were the leading loan intents by total loan amount

## 🚀 How to Use
1. Download `Smart_Loan_Decision_Intelligence_Dashboard.xlsx`
2. Open in Excel
3. Go to the `DASHBOARD` sheet for the executive summary view
4. Explore `PIVOT_ANALYSIS` to see the underlying breakdowns

## 📷 Preview
*(Add a screenshot of your Dashboard sheet here — see the "Add screenshots" step in the setup guide)*

---
**Author:** Anjali | Data Analytics Student
