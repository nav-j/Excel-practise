# Advanced Level Excel Pivot Table Tasks

# 🎯 Objective

Practice advanced Pivot Table features such as:

* Multiple value fields
* Calculated fields
* Grouping
* Slicers & Timelines
* Percentage analysis
* Pivot Charts
* Dashboard reporting

---

# 🟢 Advanced Task 1: Multi-Department Sales Dashboard

## 📋 Create Data

| A        | B          | C     | D     | E        |
| -------- | ---------- | ----- | ----- | -------- |
| Employee | Department | Month | Sales | Expenses |
| Raj      | IT         | Jan   | 55000 | 12000    |
| Simran   | HR         | Jan   | 42000 | 8000     |
| Aman     | Sales      | Jan   | 70000 | 15000    |
| Neha     | Marketing  | Feb   | 48000 | 10000    |
| Ravi     | IT         | Feb   | 62000 | 14000    |
| Pooja    | HR         | Feb   | 45000 | 9000     |
| Karan    | Sales      | Mar   | 80000 | 18000    |
| Meena    | Marketing  | Mar   | 52000 | 12000    |

---

# ✅ Tasks

Create a Pivot Table showing:

* Department-wise:

  * Total Sales
  * Total Expenses
  * Profit

---

## 📌 Steps

### 1. Insert Pivot Table

```text id="d2wq5x"
Insert → Pivot Table
```

---

### 2. Drag Fields

| Area   | Field      |
| ------ | ---------- |
| Rows   | Department |
| Values | Sales      |
| Values | Expenses   |

---

### 3. Create Calculated Field

Go to:

```text id="v8m1qa"
PivotTable Analyze → Fields, Items & Sets → Calculated Field
```

Formula:

```excel id="e3a6qp"
=Sales-Expenses
```

Field Name:

```text id="x0pj6f"
Profit
```

---

# 🎯 Sample Output

| Department | Sum of Sales | Sum of Expenses | Profit |
| ---------- | ------------ | --------------- | ------ |
| HR         | 87000        | 17000           | 70000  |
| IT         | 117000       | 26000           | 91000  |
| Marketing  | 100000       | 22000           | 78000  |
| Sales      | 150000       | 33000           | 117000 |

---

# 🟢 Advanced Task 2: Percentage Contribution Analysis

## ✅ Task

Show each department’s sales contribution percentage.

---

## 📌 Steps

1. Right-click Sales values
2. Select:

```text id="h7k3sm"
Show Values As → % of Grand Total
```

---

# 🎯 Sample Output

| Department | Sales % |
| ---------- | ------- |
| HR         | 19%     |
| IT         | 26%     |
| Marketing  | 22%     |
| Sales      | 33%     |

---

# 🟢 Advanced Task 3: Grouping Dates in Pivot Table

## 📋 Create Data

| Date      | Product  | Sales |
| --------- | -------- | ----- |
| 01-Jan-26 | Laptop   | 55000 |
| 15-Jan-26 | Mouse    | 12000 |
| 08-Feb-26 | Keyboard | 18000 |
| 20-Feb-26 | Monitor  | 35000 |
| 12-Mar-26 | Printer  | 25000 |
| 28-Mar-26 | Laptop   | 65000 |

---

## ✅ Task

Create Pivot Table grouped by:

* Months
* Quarters

---

## 📌 Steps

1. Drag Date into Rows
2. Right-click any date →
3. Select:

```text id="n2r5wy"
Group
```

4. Choose:

* Months
* Quarters

---

# 🎯 Sample Output

| Quarter | Month | Sum of Sales |
| ------- | ----- | ------------ |
| Q1      | Jan   | 67000        |
|         | Feb   | 53000        |
|         | Mar   | 90000        |

---

# 🟢 Advanced Task 4: Pivot Table with Slicers & Timeline

## ✅ Task

Create an interactive report using:

* Slicers
* Timeline Filter

---

## 📌 Steps

### Add Slicer

```text id="u8v2mx"
PivotTable Analyze → Insert Slicer
```

Choose:

* Department
* Product

---

### Add Timeline

```text id="z5t7kp"
PivotTable Analyze → Insert Timeline
```

Choose:

* Date

---

# 🎯 Learning

Students can filter reports dynamically by:

* Month
* Quarter
* Department
* Product

---

# 🟢 Advanced Task 5: Top Performing Employees

## ✅ Task

Display only top 5 employees by sales.

---

## 📌 Steps

1. Create Pivot Table:

   * Employee → Rows
   * Sales → Values

2. Apply Filter:

```text id="w1f4jc"
Value Filters → Top 10
```

3. Change:

* Top 10 → Top 5

---

# 🎯 Sample Output

| Employee | Total Sales |
| -------- | ----------- |
| Karan    | 80000       |
| Aman     | 70000       |
| Ravi     | 62000       |
| Raj      | 55000       |
| Meena    | 52000       |

---

# 🟢 Advanced Task 6: Create Pivot Chart Dashboard

## ✅ Task

Create dashboard containing:

* Pivot Table
* Column Chart
* Slicer
* Timeline

---

## 📌 Steps

1. Select Pivot Table
2. Go to:

```text id="j9q6vx"
Insert → Pivot Chart
```

3. Choose:

* Column Chart

4. Arrange:

* Chart
* Slicer
* Timeline

on same worksheet.

---

# 🎯 Final Dashboard Should Show

✔ Department Sales
✔ Profit Analysis
✔ Monthly Trends
✔ Interactive Filters
✔ Top Employees

---

# 🟢 Advanced Task 7: Compare Actual vs Target Sales

## 📋 Create Data

| Employee | Target | Actual Sales |
| -------- | ------ | ------------ |
| Raj      | 50000  | 55000        |
| Aman     | 60000  | 70000        |
| Simran   | 45000  | 42000        |
| Ravi     | 55000  | 62000        |

---

## ✅ Task

Create Pivot Table showing:

* Total Target
* Actual Sales
* Difference

---

## 📌 Create Calculated Field

```excel id="ewh1v0"
='Actual Sales'-Target
```

---

# 🎯 Sample Output

| Employee | Target | Actual | Difference |
| -------- | ------ | ------ | ---------- |
| Raj      | 50000  | 55000  | 5000       |
| Aman     | 60000  | 70000  | 10000      |
| Simran   | 45000  | 42000  | -3000      |

---

# 🎯 Advanced Learning Outcomes

Students will master:

* Calculated Fields
* Value Percentage Analysis
* Date Grouping
* Slicers & Timelines
* Interactive Dashboards
* Top/Bottom Analysis
* Pivot Charts
* Business Reporting Automation

