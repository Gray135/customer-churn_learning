# CS-Churn

# Customer Churn Analysis – Excel Project

This Excel-based churn analysis simulates the work of a Customer Success or Operations Analyst. It uses logic-driven formulas to flag at-risk customers based on tenure, service engagement, and total charges. It also includes a customer ID lookup tool for fast insights.

---

## What This Workbook Shows

- **Validated TotalCharges** using ISNUMBER() and IFERROR()
- **Segmented customers** by:
  - Tenure Group (New, 1–2 Years, 2–4 Years, 4+ Years)
  - Service Level (Low Service vs. Multi-Service)
  - Risk Flag (High Risk if new & low service)
- **Created a lookup tool tab** with XLOOKUP for fast customer insights

---

## Key Excel Functions Used

- `ISNUMBER()` – checks for clean numeric values
- `IFERROR()` – avoids formula breaks
- `COUNTIF()` – counts how many services a customer has
- `IF()` + `AND()` – creates conditional flags (e.g., high-risk logic)
- `XLOOKUP()` – searches customer info on demand
- `TEXT()`, `LEN()`, `TRIM()` – optional cleaning and formatting tools

---

## File Structure

| Sheet Name | Description |
|------------|-------------|
| `Customer Churn Project Table` | Full dataset with risk, tenure, and service logic |
| `Formulas used in Project Table` | Plain-English explanations of formulas used |
| `Customer Churn Look Up Tool` | Searchable tool using XLOOKUP for any customer ID |
| `Formulas Used in Look Up Tool` | Supporting logic for lookup tab |

---

## Why This Matters

This workbook simulates how Customer Operations Analysts use Excel to:
- Identify at-risk customers
- Prioritize retention efforts
- Build simple tools that support Customer Success Managers

---

## Created By
**Aaron Zeug**  
Aspiring Data Analyst with CX + Ops background  
[GitHub Profile](https://github.com/Gray135) | [LinkedIn](https://www.linkedin.com/in/aaronzeug)
