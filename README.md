# 📊 Apply Filters to SQL Queries – Cybersecurity Data Investigation

This project demonstrates practical use of SQL filtering techniques to investigate potential security issues based on login activity and employee data. It was completed as part of the Google Cybersecurity Certificate program and showcases advanced SQL use for data-driven investigation and reporting.

---

## 📁 Project Overview

As a security analyst at a large organization, I was tasked with investigating login attempts and retrieving relevant employee data for system-wide security updates. Using SQL queries, I filtered large datasets across multiple tables, focusing on:

- Failed logins after business hours  
- Login attempts on specific dates  
- Filtering by geographical login origins  
- Employee-machine mapping through table joins  
- Department-based filtering using logical operators

---

## 🛠️ SQL Concepts Used

- `AND`, `OR`, `NOT` operators  
- `LIKE` pattern matching  
- Date and time filtering  
- Boolean filters (`TRUE`/`FALSE` or `1`/`0`)  
- `INNER JOIN` for combining tables  
- Filtering across multiple fields

---

## 🔍 Tasks Completed

### ✅ Retrieve after-hours failed login attempts  
Filtered for login attempts after 18:00 where success = `0`.

### ✅ Retrieve login attempts on specific dates  
Used the `OR` operator to return results for `2022-05-08` and `2022-05-09`.

### ✅ Retrieve login attempts outside of Mexico  
Applied `NOT` and `LIKE 'MEX%'` to filter out entries from Mexico.

### ✅ Retrieve employees in the Marketing department (East offices)  
Used `AND` with `LIKE 'East%'` to locate relevant employees.

### ✅ Retrieve employees in Finance or Sales  
Filtered for departments using `OR`.

### ✅ Retrieve employees not in Information Technology  
Excluded the 'Information Technology' department using `NOT`.

### ✅ Perform INNER JOIN on employees and login attempts  
Joined both tables on `username` to map login data with employee records.

---

## 📸 Screenshots
All screenshots documenting SQL queries and their outputs are embedded in the full report below.

---

## 📄 Full Report & Documentation

[📄 View Portfolio Report (Google Doc)](https://docs.google.com/document/d/1LFH21h3ShOdgFOS4NpAnLSsDhdzJ6iJWafVn7LnQ2v0/edit?usp=sharing)

---

## 🧠 Summary

This project demonstrates my ability to write advanced SQL queries using filter operators to investigate real-world security concerns. I analyzed login activity, investigated suspicious behavior, and supported security update decisions through structured data analysis.

---

## 🧩 Skills Demonstrated

- SQL querying for security investigations  
- Pattern-based filtering and log analysis  
- Table joins and relational logic  
- Filtering using conditional operators  
- Report writing and documentation of investigative workflows  
