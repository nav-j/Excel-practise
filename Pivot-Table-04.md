# Excel Pivot Table Task Using Given Data

#  Objective

Create a Pivot Table to analyze customer purchase amounts date-wise.

---

#  Given Data

| Customer | Product | Purchase Date | Amount |
| -------- | ------- | ------------- | ------ |
| Alice    | Apple   | 01-04-2025    | 5      |
| Bob      | Banana  | 01-04-2025    | 7      |
| Alice    | Orange  | 02-04-2025    | 8      |
| Charlie  | Apple   | 02-04-2025    | 3      |
| Alice    | Banana  | 03-04-2025    | 6      |

---

# 🟢 Task 1: Create Customer-wise Sales Pivot Table

## ✅ Requirements

Create a Pivot Table showing:

* Customer names in Rows
* Purchase Dates in Columns
* Sum of Amount in Values

---

# 📌 Steps to Perform

### Step 1: Select Data

Select complete table including headings.

---

### Step 2: Insert Pivot Table

Go to:

```text id="9u4kdx"
Insert → Pivot Table
```

Choose:

* New Worksheet

Click **OK**

---

### Step 3: Arrange Pivot Fields

Drag fields as follows:

| Pivot Area | Field         |
| ---------- | ------------- |
| Rows       | Customer      |
| Columns    | Purchase Date |
| Values     | Amount        |

---

# 🎯 Expected Pivot Table Output

| Customer    | 01-04-2025 | 02-04-2025 | 03-04-2025 | Grand Total |
| ----------- | ---------- | ---------- | ---------- | ----------- |
| Alice       | 5          | 8          | 6          | 19          |
| Bob         | 7          | 0          | 0          | 7           |
| Charlie     | 0          | 3          | 0          | 3           |
| Grand Total | 12         | 11         | 6          | 29          |

---

# 🟢 Task 2: Create Product-wise Pivot Table

## ✅ Requirements

Analyze total quantity/product amount sold product-wise.

---

## 📌 Drag Fields

| Pivot Area | Field   |
| ---------- | ------- |
| Rows       | Product |
| Values     | Amount  |

---

# 🎯 Sample Output

| Product | Sum of Amount |
| ------- | ------------- |
| Apple   | 8             |
| Banana  | 13            |
| Orange  | 8             |

---

# 🟢 Task 3: Find Highest Purchasing Customer

## ✅ Requirements

Use Pivot Table filter to identify customer with highest total amount.

---

## 📌 Steps

1. Click Row Labels dropdown
2. Select:

```text id="x4h9pv"
Value Filters → Top 10
```

3. Choose:

* Top 1 item by Sum of Amount

---

# 🎯 Expected Result

| Customer | Total Amount |
| -------- | ------------ |
| Alice    | 19           |

---

# 🟢 Task 4: Create Pivot Chart

## ✅ Requirements

Create a chart showing customer purchase comparison.

---

## 📌 Steps

1. Select Pivot Table
2. Go to:

```text id="b7m2re"
Insert → Pivot Chart
```

3. Choose:

* Column Chart

---

# 🟢 Task 5: Apply Date Filter Using Slicer

## ✅ Requirements

Add slicer for Purchase Date.

---

## 📌 Steps

1. Click Pivot Table
2. Go to:

```text id="m8v3qt"
PivotTable Analyze → Insert Slicer
```

3. Select:

* Purchase Date

---

# 🎯 Learning Outcomes

Students will learn:

* Creating Pivot Tables
* Summarizing data
* Row and Column fields
* Filtering top records
* Pivot Charts
* Slicers for interactive reports
* Sales data analysis in Excel
