# 📊 DecodeLabs Data Analytics Project 1

## 🧾 Overview
This project is part of the DecodeLabs Data Analytics Internship.

The goal of this project was to clean and prepare a raw dataset using Microsoft Excel by identifying and fixing data quality issues.

---

## 📁 Dataset
- File Name: Dataset for Data Analytics.xlsx
- Total Records: 1200 rows
- The dataset contained issues such as:
  - Missing values
  - Incorrect date formats
  - Floating point precision errors
  - Data consistency checks

---

## 🧹 Data Cleaning Steps

### ✅ CR001 — Missing Values
- Column: CouponCode  
- Issue: 309 missing values  
- Solution: Replaced with "N/A"

---

### ✅ CR002 — Date Format Fix
- Issue: Dates were not in standard format  
- Solution: Converted all dates to `YYYY-MM-DD` format

---

### ✅ CR003 — Floating Point Fix
- Columns: UnitPrice, TotalPrice  
- Issue: Values like 550.1799999  
- Solution: Formatted to 2 decimal places

---

### ✅ CR004 — Duplicate Check
- Column: OrderID  
- Result: No duplicate values found ✅

---

### ✅ CR005 — Text Consistency
- Checked columns:
  - Product
  - PaymentMethod
  - OrderStatus
  - ReferralSource  
- Result: No extra spaces or casing issues ✅

---

## 📋 Change Log
A separate **Change Log sheet** was created in Excel documenting all cleaning steps:

| Change ID | Issue | Action |
|----------|------|--------|
| CR001 | Missing values | Filled with N/A |
| CR002 | Date format | Standardized |
| CR003 | Floating points | Rounded |
| CR004 | Duplicates | Checked |
| CR005 | Text issues | Verified |

---

## ✅ Final Verification
- ✔ 0% duplicate OrderIDs  
- ✔ 0% incorrect date formats  
- ✔ All changes documented  

---

## 🛠 Tools Used
- Microsoft Excel

---

## 🎯 Outcome
A fully cleaned dataset ready for analysis and visualization.

---

## 👤 Author
Narmeen Fatima