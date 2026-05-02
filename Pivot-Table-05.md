# Excel Pivot Table Task Using Given Data

# 🎯 Objective

Learn how to create Pivot Tables for:

* Project work analysis
* Team member performance tracking
* Employee attendance analysis

---

# 🟢 Task 1: Project Hours Analysis Using Pivot Table

## 📋 Given Data

| Project Name | Team Member | Hours Worked | Date       |
| ------------ | ----------- | ------------ | ---------- |
| Project A    | John        | 10           | 01-03-2025 |
| Project A    | Sarah       | 8            | 01-03-2025 |
| Project B    | John        | 5            | 01-03-2025 |
| Project A    | Mitchel     | 12           | 02-03-2025 |
| Project B    | Sarah       | 6            | 02-03-2025 |

---

# ✅ Task

Create a Pivot Table showing:

* Project Name
* Team Member
* Sum of Hours Worked

---

# 📌 Steps

1. Select complete data table
2. Go to:

```text id="u3m7kv"
Insert → Pivot Table
```

3. Choose:

* New Worksheet

4. Arrange fields:

| Pivot Area | Field        |
| ---------- | ------------ |
| Rows       | Project Name |
| Rows       | Team Member  |
| Values     | Hours Worked |

---

# 🎯 Expected Pivot Table Output

| Project Name | Team Member | Sum of Hours Worked |
| ------------ | ----------- | ------------------- |
| Project A    | John        | 10                  |
|              | Mitchel     | 12                  |
|              | Sarah       | 8                   |
| Project B    | John        | 5                   |
|              | Sarah       | 6                   |
| Grand Total  |             | 41                  |

---

# 🟢 Task 2: Employee Attendance Analysis

## 📋 Given Data

| Employee Name | Department | Date       | Attendance |
| ------------- | ---------- | ---------- | ---------- |
| John          | Sales      | 01-01-2025 | Present    |
| Sarah         | Marketing  | 01-01-2025 | Absent     |
| John          | Sales      | 02-01-2025 | Absent     |
| Sarah         | Marketing  | 02-01-2025 | Present    |
| John          | Sales      | 03-01-2025 | Present    |
| Sarah         | Marketing  | 03-01-2025 | Present    |
| Michael       | Sales      | 03-01-2025 | Present    |

---

# ✅ Task

Create Pivot Table showing:

* Employee-wise attendance count
* Present and Absent totals

---

# 📌 Arrange Fields

| Pivot Area | Field              |
| ---------- | ------------------ |
| Rows       | Employee Name      |
| Columns    | Attendance         |
| Values     | Attendance (Count) |

---

# 🎯 Expected Pivot Table Output

| Employee Name | Absent | Present | Grand Total |
| ------------- | ------ | ------- | ----------- |
| John          | 1      | 2       | 3           |
| Michael       | 0      | 1       | 1           |
| Sarah         | 1      | 2       | 3           |
| Grand Total   | 2      | 5       | 7           |

---

# 🟢 Task 3: Department-wise Attendance Report

## ✅ Task

Create Pivot Table showing:

* Department-wise Present count

---

## 📌 Arrange Fields

| Pivot Area | Field              |
| ---------- | ------------------ |
| Rows       | Department         |
| Filters    | Attendance         |
| Values     | Attendance (Count) |

---

## 📌 Apply Filter

Select only:

```text id="m5k2vz"
Present
```

---

# 🎯 Sample Output

| Department | Count of Attendance |
| ---------- | ------------------- |
| Marketing  | 2                   |
| Sales      | 3                   |

---

# 🟢 Task 4: Create Pivot Chart

## ✅ Task

Create Pivot Chart for project hours worked.

---

## 📌 Steps

1. Select Pivot Table
2. Go to:

```text id="r8v4xp"
Insert → Pivot Chart
```

3. Choose:

* Column Chart

---

# 🟢 Task 5: Add Slicer

## ✅ Task

Insert slicer for:

* Project Name
* Attendance

---

## 📌 Steps

1. Click Pivot Table
2. Go to:

```text id="f7n3jq"
PivotTable Analyze → Insert Slicer
```

3. Select required fields

---

# 🎯 Learning Outcomes

Students will learn:

* Multi-level Pivot Tables
* Attendance analysis
* Count and Sum calculations
* Pivot Charts
* Interactive filtering using slicers
* Employee/project reporting in Excel
