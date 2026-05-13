# 📊 Advanced Excel Data Tab Task Set — Microsoft Excel

---

# 🔥 Task 1 — Advanced Custom Sort

## 🎯 Objective

Sort employees based on:

1. Department custom order:

   * HR
   * IT
   * Finance
2. Salary from Highest to Lowest

---

## 🧾 Dataset

| Emp ID | Name   | Department | Salary |
| ------ | ------ | ---------- | ------ |
| 101    | Aman   | IT         | 45000  |
| 102    | Neha   | HR         | 30000  |
| 103    | Raj    | IT         | 60000  |
| 104    | Simran | Finance    | 50000  |
| 105    | Karan  | IT         | 70000  |
| 106    | Pooja  | HR         | 35000  |

---

## ✅ Expected Output

| Name   | Department | Salary |
| ------ | ---------- | ------ |
| Pooja  | HR         | 35000  |
| Neha   | HR         | 30000  |
| Karan  | IT         | 70000  |
| Raj    | IT         | 60000  |
| Aman   | IT         | 45000  |
| Simran | Finance    | 50000  |

---

# 🔥 Task 2 — Advanced Filter by Color

## 🎯 Objective

Highlight employees with Salary > 50,000 using Cell Color, then filter by color.

---

## 🧾 Dataset

| Name   | Salary |
| ------ | ------ |
| Aman   | 45000  |
| Raj    | 60000  |
| Simran | 50000  |
| Karan  | 70000  |

---

## ✅ Expected Output After Filter by Color

| Name  | Salary |
| ----- | ------ |
| Raj   | 60000  |
| Karan | 70000  |

---

# 🔥 Task 3 — Data Validation with Error Alert

## 🎯 Objective

Allow marks only between 0 and 100.

---

## 🧾 Dataset

| Student | Marks |
| ------- | ----- |
| Aman    | 85    |
| Neha    | 105   |
| Raj     | 75    |

---

## ✅ Requirement

If user enters:

* Less than 0
* Greater than 100

Excel should show:

```text
Invalid Marks Entered
```

---

# 🔥 Task 4 — Remove Duplicate Orders

## 🧾 Dataset

| Order ID | Customer | Product |
| -------- | -------- | ------- |
| 101      | Aman     | Laptop  |
| 102      | Neha     | Mobile  |
| 101      | Aman     | Laptop  |
| 103      | Raj      | Tablet  |

---

## 🎯 Requirement

Remove duplicate orders.

---

## ✅ Expected Output

| Order ID | Customer | Product |
| -------- | -------- | ------- |
| 101      | Aman     | Laptop  |
| 102      | Neha     | Mobile  |
| 103      | Raj      | Tablet  |

---

# 🔥 Task 5 — Text to Columns with Email IDs

## 🧾 Dataset

| Email                                     |
| ----------------------------------------- |
| [aman@gmail.com](mailto:aman@gmail.com)   |
| [neha@yahoo.com](mailto:neha@yahoo.com)   |
| [raj@outlook.com](mailto:raj@outlook.com) |

---

## 🎯 Requirement

Split into:

* Username
* Domain

---

## ✅ Expected Output

| Username | Domain      |
| -------- | ----------- |
| aman     | gmail.com   |
| neha     | yahoo.com   |
| raj      | outlook.com |

---

# 🔥 Task 6 — Flash Fill Employee Email IDs

## 🧾 Dataset

| First Name | Last Name |
| ---------- | --------- |
| Aman       | Sharma    |
| Neha       | Verma     |
| Raj        | Kumar     |

---

## 🎯 Requirement

Using Flash Fill, generate emails:

```text
aman.sharma@company.com
```

---

## ✅ Expected Output

| Email                                                     |
| --------------------------------------------------------- |
| [aman.sharma@company.com](mailto:aman.sharma@company.com) |
| [neha.verma@company.com](mailto:neha.verma@company.com)   |
| [raj.kumar@company.com](mailto:raj.kumar@company.com)     |

---

# 🔥 Task 7 — Group and Ungroup Data

## 🧾 Dataset

| Month | Sales |
| ----- | ----- |
| Jan   | 25000 |
| Feb   | 30000 |
| Mar   | 28000 |
| Apr   | 35000 |

---

## 🎯 Requirement

Group monthly data and collapse/expand using:

* Data → Group

---

# 🔥 Task 8 — What-If Analysis (Goal Seek)

## 🎯 Objective

Find required Units Sold to achieve:

```text
Total Sales = 1,00,000
```

---

## 🧾 Dataset

| Price per Unit | Units Sold | Total Sales |
| -------------- | ---------- | ----------- |
| 500            | 50         | 25000       |

Formula:

```excel
=Price * Units
```

---

## ✅ Expected Output

Units Sold should become:

```text
200
```

because:

```text
500 × 200 = 100000
```

---

# 💡 Skills Covered

✅ Sort & Custom Sort
✅ Filter by Color
✅ Data Validation
✅ Remove Duplicates
✅ Text to Columns
✅ Flash Fill
✅ Group/Ungroup
✅ Goal Seek (What-If Analysis)
