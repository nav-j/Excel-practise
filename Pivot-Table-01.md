# Excel Tasks Using Pivot Table

# 🎯 Objective

Learn how to create and use **Pivot Tables** in Excel for data analysis, summaries, and reports.

---

# 🟢 Task 1: Sales Summary by Department

## 📋 Create the Following Data

| A        | B          | C     | D     |
| -------- | ---------- | ----- | ----- |
| Employee | Department | Month | Sales |
| Raj      | IT         | Jan   | 25000 |
| Simran   | HR         | Jan   | 18000 |
| Aman     | Sales      | Jan   | 32000 |
| Neha     | IT         | Feb   | 27000 |
| Ravi     | Sales      | Feb   | 35000 |
| Pooja    | HR         | Feb   | 22000 |
| Karan    | IT         | Mar   | 30000 |
| Meena    | Sales      | Mar   | 40000 |

---

# ✅ Task

Create a Pivot Table to show:

* Total Sales by Department

---

## 📌 Steps

1. Select complete data table
2. Go to:

```text id="s4yx0f"
Insert → Pivot Table
```

3. Choose:

   * New Worksheet
4. Drag:

   * Department → Rows
   * Sales → Values

---

# 🎯 Sample Output

| Department | Sum of Sales |
| ---------- | ------------ |
| HR         | 40000        |
| IT         | 82000        |
| Sales      | 107000       |

---

# 🟢 Task 2: Monthly Sales Report

## ✅ Task

Create Pivot Table to show:

* Month-wise Sales Total

---

## 📌 Drag Fields

| Area   | Field |
| ------ | ----- |
| Rows   | Month |
| Values | Sales |

---

# 🎯 Sample Output

| Month | Sum of Sales |
| ----- | ------------ |
| Jan   | 75000        |
| Feb   | 84000        |
| Mar   | 70000        |

---

# 🟢 Task 3: Employee Wise Sales Analysis

## ✅ Task

Create Pivot Table showing:

* Employee Name
* Total Sales

---

## 📌 Drag Fields

| Area   | Field    |
| ------ | -------- |
| Rows   | Employee |
| Values | Sales    |

---

# 🎯 Sample Output

| Employee | Sum of Sales |
| -------- | ------------ |
| Raj      | 25000        |
| Simran   | 18000        |
| Aman     | 32000        |
| Neha     | 27000        |

---

# 🟢 Task 4: Department and Month Wise Sales

## ✅ Task

Create a Pivot Table showing:

* Department-wise monthly sales report

---

## 📌 Drag Fields

| Area    | Field      |
| ------- | ---------- |
| Rows    | Department |
| Columns | Month      |
| Values  | Sales      |

---

# 🎯 Sample Output

| Department | Jan   | Feb   | Mar   | Grand Total |
| ---------- | ----- | ----- | ----- | ----------- |
| HR         | 18000 | 22000 | 0     | 40000       |
| IT         | 25000 | 27000 | 30000 | 82000       |
| Sales      | 32000 | 35000 | 40000 | 107000      |

---

# 🟢 Task 5: Count Employees Using Pivot Table

## ✅ Task

Find how many employees are in each department.

---

## 📌 Drag Fields

| Area   | Field            |
| ------ | ---------------- |
| Rows   | Department       |
| Values | Employee (Count) |

---

# 🎯 Sample Output

| Department | Count of Employee |
| ---------- | ----------------- |
| HR         | 2                 |
| IT         | 3                 |
| Sales      | 3                 |

---

# 🟢 Task 6: Create Pivot Chart

## ✅ Task

Create a chart from Pivot Table.

---

## 📌 Steps

1. Select Pivot Table
2. Go to:

```text id="wn2cb7"
Insert → Pivot Chart
```

3. Choose:

   * Column Chart

---

# 🎯 Learning Outcomes

Students will learn:

* Creating Pivot Tables
* Data summarization
* Grouping and analyzing records
* Pivot Charts
* Row, Column, and Value fields
* Professional reporting in Excel
