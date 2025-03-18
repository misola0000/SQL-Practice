# SQL-Practice

This repository contains my hands-on SQL practice.

## 📌 Query: OrderDetails Filtering
- The SQL query retrieves all `OrderDetails` records where `Quantity` is greater than 20.
- The results are sorted by `ProductID`.
- The output is stored in [SQLQuery.png](./SQLQuery.png).

---
✅ **Author:** [Your GitHub Username]  
## 📝 SQL Module 18 – Task 2: Hands-on Practice  

### 🔍 Business Question:  
**Show all OrderDetails records where Quantity is over 20, sorted by ProductID.**  

### 📌 SQL Query Used:
```sql
SELECT * FROM OrderDetails WHERE Quantity > 20 ORDER BY ProductID;
