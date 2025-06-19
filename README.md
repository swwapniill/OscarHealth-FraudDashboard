# 🩺 Oscar Health – Claims Fraud Detection Dashboard

**Client (Simulated)**: Oscar Health – U.S.-based tech-driven health insurance company  
**Project Type**: Freelance Simulation | Healthcare Analytics  
**Tools Used**: Excel, Power BI Web  
**Timeline**: June 2025  

---

## 📌 Objective

To help Oscar Health’s fraud analytics team identify and analyze high-risk insurance claims using business rule–based flagging and interactive visual dashboards.

---

## 🧠 Problem Statement

Oscar Health wanted to proactively detect potential fraudulent claims by analyzing claim amount patterns, smoker and BMI data, and regional risk trends.  
The goal was to provide an **interactive dashboard** that flags risky claims and breaks down trends by region, age group, and customer segments.

---

## 🛠️ Process & Methodology

### ✅ Step 1: Data Cleaning (Excel)
- Added a new `Risk_Flag` column using logic:
  - High BMI + Smoker + More than 2 children + High charges = **Flag**
- Created additional fields for better segmentation:
  - `Age_Group` (Under 30, 30–50, Over 50)
  - `Charge_Category` (Low, Medium, High)
  - `Smoker_Label` (Smoker / Non-Smoker)

### ✅ Step 2: Dashboarding (Power BI Web)
- Uploaded cleaned dataset to Power BI Web
- Built KPI visuals: Total Claims, Flagged Claims, Avg Charges
- Designed visuals for:
  - Region-wise risk breakdown
  - Charges by age group
  - Charge category distribution
  - Table of high-risk profiles
- Enabled interactive slicers for Region, Smoker Label, and Risk Flag

---

## 📊 Dashboard Preview

![Oscar Health – Fraud Detection Dashboard](OscarHealth_ClaimsDashboard.png)

---

## 🔍 Key Insights
- Flagged ~32% of claims as potentially high-risk based on custom rules
- SouthEast region had the highest concentration of flagged claims
- Smokers with high BMI were most likely to fall into the risky profile
- Avg charges for flagged claims were 27% higher than non-flagged ones

---

## 📁 Files Included
| File | Description |
|------|-------------|
| `oscar_health_claims_cleaned.csv` | Cleaned dataset with added logic fields |
| `OscarHealth_ClaimsDashboard.png` | Final dashboard screenshot |
| `README.md` | Project overview and documentation |

---

## 🧾 Simulated Experience Justification

This project was designed to **simulate freelance data analyst work** for a real U.S.-based company. It mimics the process of solving a domain-specific analytics problem from raw data cleaning to dashboard delivery — matching real-world expectations.

---

## 📬 Contact & Credits

Made with ❤️ by swwapniill  
Feel free to connect on [LinkedIn](https://www.linkedin.com/in/swapnil-more-0b216725a/) or discuss via DM if you're hiring for data analyst roles.
