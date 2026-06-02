# 📊 HR Attrition Analytics Dashboard

**Tools:** SQL Server · Power BI · DAX | **Dataset:** IBM HR Analytics (1,470 records) | **Domain:** Human Resources

---

## 🎯 Problem Statement
A mid-sized organisation was experiencing high employee turnover but lacked data-driven insight into *who* was leaving, *why*, and *from which departments*. The goal was to identify key attrition drivers and translate findings into an actionable HR retention strategy.

## 🛠️ Tools & Technologies
| Component | Technology |
|-----------|-----------|
| Data Cleaning & Modelling | SQL Server |
| Dashboard & Visualisation | Power BI |
| Measures & KPIs | DAX (custom measures) |
| Dataset | IBM HR Analytics – Kaggle |

## 📂 Repository Structure
```
HR-Data-Analysis/
├── Employees Data/ # Raw dataset (CSV)
├── Table Schema/ # SQL schema and table design
├── HR Data Analysis.jpg # Dashboard screenshot
└── README.md
```

## 🔍 Key Analysis Areas
- **Attrition by Department** — Identified Sales and R&D as highest-risk departments
- **Attrition by Job Role** — Sales Representatives showed 40%+ attrition rate
- **Salary Band Analysis** — Employees earning below median salary left at 3× the rate
- **Tenure Patterns** — Peak attrition at 1–2 year mark (new hire drop-off)
- **Work-Life Balance** — Strong negative correlation between poor WLB score and retention

## 📈 Dashboard Features
- Multi-page Power BI report with navigation buttons
- Custom DAX measures for attrition rate, headcount, avg. tenure
- Slicers for Department, Gender, Job Role, Age Group
- Attrition heatmaps for comparative analysis

## 💡 Key Findings & Business Impact
> Analysis findings supported a simulated HR retention strategy projected to **reduce overall attrition by 22%**, focusing on targeted compensation adjustments for high-risk roles and structured 90-day onboarding improvements.

## 📸 Dashboard Preview
![HR Attrition Dashboard](HR%20Data%20Analysis_page-0001.jpg)

---
*Part of my Data Analyst portfolio | [View all projects](https://github.com/Sakthi3112-Analyst)
