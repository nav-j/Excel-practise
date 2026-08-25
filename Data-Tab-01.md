# Excel Task – Sales Performance Analysis Using Custom Sort & Scenario Manager

## Objective

Create a professional Excel workbook to analyze employee sales performance using:

* **Custom Sort**
* **Scenario Manager**
* Basic formulas and formatting

---

# Scenario

You are working as a Sales Analyst in a company. The manager wants to:

1. Arrange employee data using **Custom Sort**
2. Compare different sales target situations using **Scenario Manager**
3. Analyze performance under different conditions

---

# Step 1: Create the Following Data Table

| Employee ID | Employee Name | Department  | Region | Monthly Sales | Target Sales | Bonus % |
| ----------- | ------------- | ----------- | ------ | ------------- | ------------ | ------- |
| E101        | Aman          | Electronics | North  | 85000         | 90000        | 5%      |
| E102        | Riya          | Clothing    | South  | 72000         | 70000        | 4%      |
| E103        | Kabir         | Grocery     | East   | 65000         | 75000        | 3%      |
| E104        | Simran        | Electronics | West   | 98000         | 95000        | 6%      |
| E105        | Raj           | Clothing    | North  | 54000         | 60000        | 2%      |
| E106        | Neha          | Grocery     | South  | 89000         | 85000        | 5%      |
| E107        | Arjun         | Electronics | East   | 76000         | 80000        | 4%      |
| E108        | Priya         | Clothing    | West   | 69000         | 70000        | 3%      |

---

# Step 2: Add Formulas

## 1. Performance Status

Create a new column named **Status** "Achieved","Not Achieved"

## 2. Bonus Amount

Create another column named **Bonus Amount** and calculate bonus amount.

---

# Step 3:  Sort

* Sort by: **Department**
* Order:

  * Electronics
  * Clothing
  * Grocery

### Level 2

*  by: **Region**
* Order:

  * North
  * South
  * East
  * West

### Level 3

*  by: **Monthly Sales**
* Order: Largest to Smallest

---

# Step 4: Use Scenario Manager

Create the following scenarios by changing **Target Sales** values.

---

## Scenario 1: Normal Target

| Employee      | Target Sales    |
| ------------- | --------------- |
| All Employees | Existing Values |

---

## Scenario 2: Increased Target

Increase all Target Sales by **10%**

Example:

| Old Target | New Target |
| ---------- | ---------- |
| 90000      | 99000      |

---

## Scenario 3: Reduced Target

Decrease all Target Sales by **15%**

Example:

| Old Target | New Target |
| ---------- | ---------- |
| 90000      | 76500      |

---

# Step 5: Create Scenario Summary

Generate a **Scenario Summary Report** showing:

* Monthly Sales
* Target Sales
* Status
* Bonus Amount

Compare results under all scenarios.

---

# Additional Formatting Tasks

Apply the following:

* Format table using **Format as Table**
* Apply **Conditional Formatting**

  * Green for “Achieved”
  * Red for “Not Achieved”
* Add:

  * Company title
  * Bold headers
  * Currency formatting

---
# Sample Output (After Custom Sort)

| Employee Name | Department  | Region | Monthly Sales | Status       |
| ------------- | ----------- | ------ | ------------- | ------------ |
| Simran        | Electronics | West   | 98000         | Achieved     |
| Aman          | Electronics | North  | 85000         | Not Achieved |
| Arjun         | Electronics | East   | 76000         | Not Achieved |
| Riya          | Clothing    | South  | 72000         | Achieved     |
| Raj           | Clothing    | North  | 54000         | Not Achieved |
