# DecodeLabs Data Analytics Project 1

## Overview
This project is part of the DecodeLabs Data Analytics Internship.

The objective of this project was to clean and prepare a raw dataset using Microsoft Excel by identifying and resolving various data quality issues.

---

## Dataset
- File Name: Dataset for Data Analytics.xlsx  
- Total Records: 1200 rows  

The dataset contained the following issues:
- Missing values  
- Incorrect date formats  
- Floating point precision errors  
- Data consistency issues  

---

## Data Cleaning Steps

### CR001 — Missing Values
- Column: CouponCode  
- Issue: 309 missing values  
- Action Taken: Replaced missing values with "N/A"  

---

### CR002 — Date Format Standardization
- Issue: Dates were not in a consistent format  
- Action Taken: Converted all dates to YYYY-MM-DD format  

---

### CR003 — Floating Point Precision
- Columns: UnitPrice, TotalPrice  
- Issue: Values contained excessive decimal precision (e.g., 550.1799999)  
- Action Taken: Formatted values to two decimal places  

---

### CR004 — Duplicate Check
- Column: OrderID  
- Result: No duplicate records found  

---

### CR005 — Text Consistency
- Columns Checked:
  - Product  
  - PaymentMethod  
  - OrderStatus  
  - ReferralSource  

- Result: No inconsistencies found (no extra spaces or casing issues)  

---

## Change Log
A separate "Change Log" sheet was created in Excel to document all data cleaning actions.

| Change ID | Issue              | Action Taken              |
|----------|------------------|--------------------------|
| CR001     | Missing values    | Filled with N/A          |
| CR002     | Date format       | Standardized             |
| CR003     | Floating points   | Formatted to 2 decimals  |
| CR004     | Duplicates        | Checked                  |
| CR005     | Text consistency  | Verified                 |

---

## Final Verification
- 0% duplicate OrderIDs  
- 0% incorrect date formats  
- All changes properly documented  

---

## Tools Used
- Microsoft Excel  

---

## Outcome
The dataset was successfully cleaned and is now ready for further analysis and visualization.

---

## Author
Narmeen Fatima
