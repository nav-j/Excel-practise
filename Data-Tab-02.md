## Advanced Excel Data Tab Task Set — Microsoft Excel

### Task  — Advanced Custom Sort

Sort employees based on:

1. Department custom order:

   * HR
   * IT
   * Finance
2. Salary from Highest to Lowest

###  Dataset

| Emp ID | Name   | Department | Salary |
| ------ | ------ | ---------- | ------ |
| 101    | Aman   | IT         | 45000  |
| 102    | Neha   | HR         | 30000  |
| 103    | Raj    | IT         | 60000  |
| 104    | Simran | Finance    | 50000  |
| 105    | Karan  | IT         | 70000  |
| 106    | Pooja  | HR         | 35000  |


### Task  — Advanced Filter by Color

Highlight employees with Salary > 50,000 using Cell Color, then filter by color.

### Task  — Data Validation with Error Alert
### 🧾 Dataset

| Student | Marks |
| ------- | ----- |
| Aman    | 85    |
| Neha    | 105   |
| Raj     | 75    |

Allow marks only between 0 and 100.

* Less than 0
* Greater than 100

Excel should show:

```text
Invalid Marks Entered
```

# Task  — Remove Duplicate Orders

## 🧾 Dataset

| Order ID | Customer | Product |
| -------- | -------- | ------- |
| 101      | Aman     | Laptop  |
| 102      | Neha     | Mobile  |
| 101      | Aman     | Laptop  |
| 103      | Raj      | Tablet  |

---

### Requirement

Remove duplicate orders.

---

## ✅ Expected Output

| Order ID | Customer | Product |
| -------- | -------- | ------- |
| 101      | Aman     | Laptop  |
| 102      | Neha     | Mobile  |
| 103      | Raj      | Tablet  |

---

### Task  — Text to Columns with Email IDs

## 🧾 Dataset

| Email                                     |
| ----------------------------------------- |
| [aman@gmail.com](mailto:aman@gmail.com)   |
| [neha@yahoo.com](mailto:neha@yahoo.com)   |
| [raj@outlook.com](mailto:raj@outlook.com) |

---

##  Requirement

Split into:

* Username
* Domain

### Task  — Flash Fill Employee Email IDs

## 🧾 Dataset

| First Name | Last Name |
| ---------- | --------- |
| Aman       | Sharma    |
| Neha       | Verma     |
| Raj        | Kumar     |

---

## Requirement

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

### Task  — Group and Ungroup Data

## 🧾 Dataset

| Month | Sales |
| ----- | ----- |
| Jan   | 25000 |
| Feb   | 30000 |
| Mar   | 28000 |
| Apr   | 35000 |

---

### Requirement

Group monthly data and collapse/expand using:

### Task  — What-If Analysis

Find required Units Sold to achieve:

```text
Total Sales = 1,00,000
```

## 🧾 Dataset

| Price per Unit | Units Sold | Total Sales |
| -------------- | ---------- | ----------- |
| 500            | 50         | 25000       |
