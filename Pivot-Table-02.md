#  Task : Product Sales Analysis

##  Create Data

| A        | B           | C     | D     |
| -------- | ----------- | ----- | ----- |
| Product  | Category    | Month | Sales |
| Laptop   | Electronics | Jan   | 55000 |
| Mouse    | Electronics | Jan   | 12000 |
| Chair    | Furniture   | Feb   | 18000 |
| Table    | Furniture   | Feb   | 25000 |
| Keyboard | Electronics | Mar   | 15000 |
| Sofa     | Furniture   | Mar   | 45000 |

---

## ✅ Task

Create Pivot Table to show:

* Category-wise Total Sales

---

## 📌 Drag Fields

| Area   | Field    |
| ------ | -------- |
| Rows   | Category |
| Values | Sales    |

---

# 🎯 Sample Output

| Category    | Sum of Sales |
| ----------- | ------------ |
| Electronics | 82000        |
| Furniture   | 88000        |

---

# 🟢 Task 8: Student Marks Analysis

## 📋 Create Data

| A       | B       | C      | D     |
| ------- | ------- | ------ | ----- |
| Student | Subject | Term   | Marks |
| Aman    | Math    | Term 1 | 85    |
| Simran  | Science | Term 1 | 78    |
| Ravi    | English | Term 1 | 90    |
| Neha    | Math    | Term 2 | 88    |
| Raj     | Science | Term 2 | 72    |
| Pooja   | English | Term 2 | 95    |

---

## ✅ Task

Create Pivot Table to show:

* Subject-wise Average Marks

---

## 📌 Drag Fields

| Area   | Field   |
| ------ | ------- |
| Rows   | Subject |
| Values | Marks   |

### Change Value Field Settings → Average

---

# 🎯 Sample Output

| Subject | Average of Marks |
| ------- | ---------------- |
| English | 92.5             |
| Math    | 86.5             |
| Science | 75               |

---

# 🟢 Task 9: Attendance Report

## 📋 Create Data

| A       | B     | C            |
| ------- | ----- | ------------ |
| Student | Month | Present Days |
| Aman    | Jan   | 24           |
| Simran  | Jan   | 20           |
| Ravi    | Feb   | 22           |
| Neha    | Feb   | 26           |
| Raj     | Mar   | 25           |
| Pooja   | Mar   | 23           |

---

## ✅ Task

Create Pivot Table to show:

* Month-wise Total Attendance

---

## 📌 Drag Fields

| Area   | Field        |
| ------ | ------------ |
| Rows   | Month        |
| Values | Present Days |

---

# 🎯 Sample Output

| Month | Sum of Present Days |
| ----- | ------------------- |
| Jan   | 44                  |
| Feb   | 48                  |
| Mar   | 48                  |

---

# 🟢 Task 10: Company Expense Report

## 📋 Create Data

| A          | B            | C      |
| ---------- | ------------ | ------ |
| Department | Expense Type | Amount |
| IT         | Software     | 25000  |
| HR         | Training     | 12000  |
| Sales      | Travel       | 18000  |
| IT         | Hardware     | 30000  |
| HR         | Recruitment  | 15000  |
| Sales      | Marketing    | 22000  |

---

## ✅ Task

Create Pivot Table to show:

* Department-wise Total Expenses

---

## 📌 Drag Fields

| Area   | Field      |
| ------ | ---------- |
| Rows   | Department |
| Values | Amount     |

---

# 🎯 Sample Output

| Department | Sum of Amount |
| ---------- | ------------- |
| HR         | 27000         |
| IT         | 55000         |
| Sales      | 40000         |

---

# 🟢 Task 11: Use Filters in Pivot Table

## ✅ Task

Using any previous Pivot Table:

Apply filters for:

* Month
* Department
* Category

---

## 📌 Steps

Drag field into:

| Area    | Field |
| ------- | ----- |
| Filters | Month |

---

# 🎯 Learning

Students can view reports for selected months only.

Example:

* Jan Sales
* Feb Attendance
* IT Department Data

---

# 🟢 Task 12: Top 3 Sales Records

## ✅ Task

Find top 3 highest sales using Pivot Table.

---

## 📌 Steps

1. Create Pivot Table with:

   * Employee → Rows
   * Sales → Values

2. Right Click Sales Values →

```text id="7xy5sm"
Filter → Top 10
```

3. Change:

   * Top 10 → Top 3

---

# 🎯 Sample Output

| Employee | Sum of Sales |
| -------- | ------------ |
| Meena    | 40000        |
| Ravi     | 35000        |
| Aman     | 32000        |

---

# 🟢 Task 13: Pivot Table with Slicers

## ✅ Task

Add slicers for easy filtering.

---

## 📌 Steps

1. Select Pivot Table
2. Go to:

```text id="2kq9wx"
PivotTable Analyze → Insert Slicer
```

3. Select:

* Department
* Month
