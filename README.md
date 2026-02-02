# SCLM415 – Data Analysis Assignment (Excel)

## 📌 Project Overview
This Excel file supports analysis for the **SCLM415 (Supply Chain & Logistics Management)** course.  
The workbook is designed to transform raw data into meaningful outputs using **conditional aggregation** with `SUMIFS()`—a core Excel function for supply chain reporting and KPI calculation.

---

## 📂 Repository Contents
- `SCLM415_NguyenHoangDuy_2232300272.xlsx` – Main Excel file used for analysis
- `README.md` – Project description and explanation of Excel logic

---

## 📊 Excel File Structure

### Sheet: `Data`
**Purpose:**  
This worksheet contains the full workflow in one place:
- Raw input data
- Helper columns (if any)
- Output tables/metrics calculated using conditional logic

The sheet is structured so that results can be reproduced and traced back to the raw data easily.

---

## 🔧 Key Excel Function Used & Its Purpose

### `SUMIFS()`
**What it does:**  
`SUMIFS()` sums values **only when multiple conditions are met**.  
This is commonly used in supply chain analysis to compute totals by:
- product / item category
- supplier
- warehouse / location
- time period (month/quarter/year)
- status (delivered, pending, etc.)

**Why this matters in SCM:**  
Supply chain datasets are usually large and grouped by multiple dimensions. `SUMIFS()` allows fast KPI reporting without manual filtering.

**Typical use cases in this file:**
- Sum total quantity by item and month
- Sum total cost by supplier and category
- Sum shipment volume by region and time period
- Sum values by status (e.g., completed vs. not completed)

**Example formula pattern:**
SUMIFS(sum_range, criteria_range1, criteria1, criteria_range2, criteria2, ...)

---

## 🔁 How to Use the Excel File
1. Open `SCLM415_NguyenHoangDuy_2232300272.xlsx`.
2. Go to the `Data` sheet.
3. Review the raw dataset columns (e.g., item/supplier/time/location).
4. Check the calculation/output area where `SUMIFS()` is applied.
5. Update criteria (e.g., supplier name, month, item code) to see how totals change dynamically.

---

## 🧠 Key Learning Outcomes
- Use `SUMIFS()` to perform multi-criteria aggregation for supply chain reporting
- Produce accurate totals without manual filtering
- Improve traceability by linking outputs directly to raw data
- Build reu
