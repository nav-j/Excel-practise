# 📊 Excel Task Using Data Tab in Microsoft Excel

## 🎯 Objective

Practice important tools from the **Data Tab** including:

* Sort
* Filter
* Data Validation
* Remove Duplicates
* Text to Columns
* Flash Fill
* Consolidate

---

# 🧾 Step 1: Create the Dataset

| Emp ID | Full Name    | Department | City    | Salary | Joining Date |
| ------ | ------------ | ---------- | ------- | ------ | ------------ |
| 101    | Aman Sharma  | IT         | Delhi   | 45000  | 12-01-2022   |
| 102    | Neha Verma   | HR         | Mumbai  | 30000  | 05-03-2023   |
| 103    | Raj Malhotra | IT         | Delhi   | 60000  | 10-07-2020   |
| 104    | Simran Kaur  | Finance    | Chennai | 50000  | 22-11-2021   |
| 105    | Karan Singh  | IT         | Mumbai  | 70000  | 15-09-2019   |
| 106    | Pooja Mehta  | HR         | Delhi   | 35000  | 18-02-2022   |
| 107    | Ravi Kumar   | Finance    | Pune    | 40000  | 30-06-2021   |
| 108    | Aman Sharma  | IT         | Delhi   | 45000  | 12-01-2022   |

---

# 🔹 Task 1 — Sort Data

### 🎯 Requirement

Sort the table:

1. By **Department (A–Z)**
2. Then by **Salary (Largest to Smallest)**

### ✅ Expected Result (Top Rows)

| Full Name   | Department | Salary |
| ----------- | ---------- | ------ |
| Simran Kaur | Finance    | 50000  |
| Ravi Kumar  | Finance    | 40000  |
| Neha Verma  | HR         | 30000  |
| Pooja Mehta | HR         | 35000  |
| Karan Singh | IT         | 70000  |

---

# 🔹 Task 2 — Apply Filter

### 🎯 Requirement

Show employees:

* From Delhi
* Salary greater than 40,000

### ✅ Expected Output

| Full Name    | City  | Salary |
| ------------ | ----- | ------ |
| Aman Sharma  | Delhi | 45000  |
| Raj Malhotra | Delhi | 60000  |
| Aman Sharma  | Delhi | 45000  |

---

# 🔹 Task 3 — Remove Duplicates

### 🎯 Requirement

Remove duplicate employee records.

### ✅ Duplicate Record

Aman Sharma appears twice with same details.

### ✅ Expected Output

Only one Aman Sharma record remains.

---

# 🔹 Task 4 — Data Validation

### 🎯 Requirement

Create a dropdown list for Department column with:

* IT
* HR
* Finance
* Marketing

### ✅ Steps

1. Select Department cells
2. Data → Data Validation
3. Choose **List**
4. Enter:

```text
IT,HR,Finance,Marketing
```

---

# 🔹 Task 5 — Text to Columns

### 🎯 Requirement

Split “Full Name” into:

* First Name
* Last Name

### ✅ Expected Output

| First Name | Last Name |
| ---------- | --------- |
| Aman       | Sharma    |
| Neha       | Verma     |
| Raj        | Malhotra  |

---

# 🔹 Task 6 — Flash Fill

### 🎯 Requirement

Create Employee IDs like:

```text
IT-101
HR-102
```

Using:

* Department initials
* Existing Emp ID

### ✅ Expected Output

| Employee Code |
| ------------- |
| IT-101        |
| HR-102        |
| IT-103        |

---

# 🔹 Task 7 — Consolidate Data

## Sheet 1 — Delhi Sales

| Product | Sales |
| ------- | ----- |
| Laptop  | 50000 |
| Mobile  | 30000 |

## Sheet 2 — Mumbai Sales

| Product | Sales |
| ------- | ----- |
| Laptop  | 40000 |
| Mobile  | 25000 |

---

### 🎯 Requirement

Use **Data → Consolidate** to combine sales.

### ✅ Expected Output

| Product | Total Sales |
| ------- | ----------- |
| Laptop  | 90000       |
| Mobile  | 55000       |

---

# 🚀 Advanced Challenge

### 🎯 Create Custom Sort:

Sort employees by:

1. IT
2. HR
3. Finance

(not alphabetical order)

---

# 💡 Learning Outcomes

After completing this task, students will learn:

* Multi-level sorting
* Filtering with conditions
* Duplicate handling
* Dropdown validation
* Data cleaning
* Flash Fill automation
* Data consolidation techniques
