# Customer Churn Analysis – Excel Project

This Excel-based churn analysis simulates the work of a Customer Success or Operations Analyst. It uses logic-driven formulas to flag at-risk customers based on tenure, service engagement, and total charges. It also includes a customer ID lookup tool for fast insights.

---

## Repository Contents

- `Customer Churn Project.xlsx` – Final workbook with data, formulas, and segmentation  
- `/images/` – Screenshots of enriched dataset, churn risk logic, and lookup tool  
- `README.md` – Overview of project purpose, logic, and Excel skills used

---

## Sample Views

**Final Churn Profile Table**

![Final Churn Table](images/final_churn_table.png)

**Lookup Tool Example**

![Lookup Tool](images/lookup_tool.png)

---

## What This Workbook Shows

- Validated Total Charges using `ISNUMBER()` and `IFERROR()`
- Segmented customers by:
  - Tenure Group (New, 1–2 Years, 2–4 Years, 4+ Years)
  - Service Level (Low Service vs. Multi-Service)
  - Risk Flag (High Risk if new & low service)
- Added secondary risk factors:
  - Monthly Charge Tier (High/Medium/Low)
  - Contract Type Risk (e.g., Month-to-Month = Higher Risk)
- Combined all factors into a Final Churn Profile
- Created a lookup tool tab with `XLOOKUP()` for fast customer insights
- Applied `TEXT()` to format date logic (optional)
- Created conditional labels with `IF()`, `AND()`, `OR()`

---

## Insight & Business Value

This workbook mirrors real Excel-based analysis used by Customer Success and Operations teams:

- **Retention Targeting**: Flags new, low-engagement customers with high churn risk
- **CSM Enablement**: Provides a fast, filterable lookup tool for customer profiles
- **Decision Support**: Combines logic into a churn profile to guide renewal strategy

> This type of work is core to how teams using Gainsight or Salesforce prioritize outreach — especially when predictive models aren’t available.

---

## Key Excel Functions Used

- `ISNUMBER()` – Validates numeric values
- `IFERROR()` – Prevents formula breakage
- `COUNTIF()` – Counts subscribed services
- `IF()` + `AND()` – Builds rule-based flags (e.g., High Risk)
- `OR()` – Adds alternate logic conditions
- `XLOOKUP()` – Powers the customer lookup tool
- `TEXT()`, `LEN()`, `TRIM()` – Optional text cleaning and formatting

---

## File Structure

| Sheet Name                      | Description                                         |
|--------------------------------|-----------------------------------------------------|
| `Customer Churn Project Table` | Main dataset with derived columns and risk logic   |
| `Formulas used in Project Table` | English breakdown of logic used                    |
| `Customer Churn Look Up Tool`  | Searchable tab powered by `XLOOKUP()`              |
| `Formulas Used in Look Up Tool`| Supporting logic for the lookup tab                |

---

## Why This Matters

This type of analysis reflects the real work Customer Success Ops Analysts do to:

- Identify at-risk customers using business rules
- Help Customer Success Managers act quickly with filters and flags
- Reduce churn with proactive segmentation and insights

---

## Created By

**Aaron Zeug**  
Aspiring Data Analyst with CX + Ops background  
[GitHub Profile](https://github.com/Gray135) • [LinkedIn](https://www.linkedin.com/in/aaronzeug)
