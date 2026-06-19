# SCT_DA_03 - Interactive HR Attrition Dashboard

## 📌 Task Overview

Built an interactive HR Employee Attrition Dashboard using Power BI as part of my Data Analyst Internship at SkillCraft Technology. The dashboard answers: **"Why are employees leaving?"**

---

## 🛠️ Tools Used

* Microsoft Power BI Desktop

---

## 📊 Dataset

* IBM HR Employee Attrition Dataset
* 1,470 rows and 35 columns
* Source: Kaggle / IBM Watson Analytics

---

## ✅ What I Did

* Imported and cleaned HR Attrition dataset in Power Query
* Removed constant columns (EmployeeCount, Over18, StandardHours)
* Created Age Group column using Conditional Column feature
* Built 5 DAX measures (Total Employees, Attrition Rate %, Avg Income, etc.)
* Designed 4 KPI cards for headline metrics
* Created 8 interactive charts across key dimensions
* Added 4 Slicers (Department, Gender, Age Group, JobRole) for filtering
* Built a 2-page interactive report in Power BI

---

## 📈 Dashboard Features

### KPI Cards
| Metric | Value |
|---|---|
| Total Employees | 1,470 |
| Employees Left | 237 |
| Attrition Rate % | 16.12% |
| Average Monthly Income | $6,500 |

### Charts Built
| Chart | Type | Insight |
|---|---|---|
| Attrition Rate % by Department | Bar Chart | Sales has highest attrition (21%) |
| Attrition Rate % by Age Group | Bar Chart | 18-25 age group leaves most (35%) |
| Count of Attrition by OverTime | Bar Chart | OverTime employees leave 3x more |
| Attrition Distribution | Donut Chart | 16% overall attrition rate |
| Attrition Rate % by OverTime | Bar Chart | Yes = 30.5% vs No = 10.4% |
| Attrition Rate % by JobRole | Bar Chart | Sales Rep has highest attrition |
| Attrition Rate % by BusinessTravel | Bar Chart | Frequent travelers leave more |
| Attrition Rate % by JobSatisfaction | Bar Chart | Low satisfaction drives attrition |

### Slicers (Filters)
* Department (Sales / Research & Development / Human Resources)
* Gender (Male / Female)
* Age Group (18-25 / 26-35 / 36-45 / 46-55 / 56+)
* JobRole

---

## 🔍 Key Insights — Why Are Employees Leaving?

* **OverTime is the #1 factor** — Employees working overtime leave at 30.5% vs 10.4% for those who don't
* **Young employees are at highest risk** — 18-25 age group has 34.8% attrition rate
* **Pay gap drives attrition** — Employees who left earned avg $4,787/month vs $6,833 for those who stayed
* **Sales department is most affected** — 20.6% attrition vs 13.8% in R&D
* **Low job satisfaction** — Employees with satisfaction score 1 leave the most
* **Frequent business travel** — Employees who travel frequently have higher attrition

---

## 📁 File Structure

```
SCT_DA_03/
├── SCT_DA_03esh.pbix          ← Power BI dashboard file
├── dashboard_screenshot.png    ← Dashboard preview image
└── README.md                  ← This file
```

---

## 🏢 Internship

* **Company:** SkillCraft Technology
* **Track:** Data Analyst
* **Task:** 03

---
