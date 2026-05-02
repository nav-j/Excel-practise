# Excel Task Using Slicer and Timeline (Insert Tab)

# 🎯 Objective

Learn how to use:

* **Slicer**
* **Timeline**

with Pivot Tables for interactive data filtering in Excel.

---

# 📋 Create the Following Data

| Date       | Employee | Department | Product  | Sales |
| ---------- | -------- | ---------- | -------- | ----- |
| 01-01-2026 | Raj      | IT         | Laptop   | 55000 |
| 05-01-2026 | Aman     | Sales      | Mouse    | 12000 |
| 10-01-2026 | Simran   | HR         | Keyboard | 18000 |
| 15-02-2026 | Ravi     | IT         | Monitor  | 35000 |
| 18-02-2026 | Neha     | Marketing  | Printer  | 25000 |
| 05-03-2026 | Pooja    | HR         | Laptop   | 60000 |
| 10-03-2026 | Karan    | Sales      | Mouse    | 22000 |
| 20-03-2026 | Meena    | Marketing  | Keyboard | 28000 |

---

# 🟢 Task 1: Create Pivot Table

## ✅ Requirements

Create a Pivot Table showing:

* Department-wise Sales

---

## 📌 Steps

1. Select complete data
2. Go to:

```text id="5c7qxm"
Insert → Pivot Table
```

3. Choose:

* New Worksheet

4. Drag fields:

| Area   | Field      |
| ------ | ---------- |
| Rows   | Department |
| Values | Sales      |

---

# 🎯 Sample Output

| Department | Sum of Sales |
| ---------- | ------------ |
| HR         | 78000        |
| IT         | 90000        |
| Marketing  | 53000        |
| Sales      | 34000        |

---

# 🟢 Task 2: Insert Slicer

## ✅ Requirements

Add slicers for:

* Department
* Product

---

## 📌 Steps

1. Click anywhere inside Pivot Table
2. Go to:

```text id="j4k8vn"
Insert → Slicer
```

3. Select:

* Department
* Product

4. Click **OK**

---

# 🎯 Activity

Use slicers to:

* Show only IT department sales
* Show only Laptop sales
* Filter multiple departments together

---

# 🟢 Task 3: Insert Timeline

## ✅ Requirements

Add Timeline filter for Date.

---

## 📌 Steps

1. Click Pivot Table
2. Go to:

```text id="x8m3pw"
Insert → Timeline
```

3. Select:

* Date

4. Click **OK**

---

# 🎯 Activity

Use Timeline to filter data by:

* Month
* Quarter
* Year

Example:

* View only February sales
* View January + March data

---

# 🟢 Task 4: Create Interactive Dashboard

## ✅ Requirements

Arrange:

* Pivot Table
* Slicer
* Timeline

on same worksheet to create a mini dashboard.

---

# 📌 Additional Formatting

Using Home Tab:

* Apply colors to slicers
* Bold Pivot headings
* Add borders
* Format Sales as Currency

---

# 🎯 Final Dashboard Example

Dashboard should allow users to:

✔ Filter by Department
✔ Filter by Product
✔ Filter by Date Range
✔ View instant sales updates

---

# 🟢 Bonus Task

Create a Pivot Chart connected with slicers.

## 📌 Steps

1. Select Pivot Table
2. Go to:

```text id="q2v7mn"
Insert → Pivot Chart
```

3. Choose:

* Column Chart

Now slicers and timeline will control both:

* Pivot Table
* Pivot Chart

---

# 🎯 Learning Outcomes

Students will learn:

* Interactive filtering in Excel
* Using Slicers
* Using Timeline filters
* Creating dashboards
* Dynamic Pivot Reports
* Data visualization techniques
