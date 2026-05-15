# Excel Practice Task – Simple Formulas

## Scenario

You are working as an office assistant in a company. Create an Excel sheet to manage employee details and apply simple formulas such as:

* LEFT
* RIGHT
* TRIM
* LEN
* MAX
* MIN
* COUNT
* SUM
* AVERAGE

---

# Step 1: Enter the Following Data

| Emp ID | Employee Name | Department | Salary | Bonus |
| ------ | ------------- | ---------- | ------ | ----- |
| EMP101 | Aman Sharma   | Sales      | 25000  | 3000  |
| EMP102 | Riya Verma    | HR         | 32000  | 2500  |
| EMP103 | Karan Singh   | IT         | 45000  | 5000  |
| EMP104 | Neha Kapoor   | Marketing  | 28000  | 3500  |
| EMP105 | Raj Malhotra  | Finance    | 52000  | 4000  |

---

# Step 2: Perform the Following Tasks

## 1. LEFT Function

Extract the first 3 characters from Employee ID.

### Formula

```excel
=LEFT(A2,3)
```

---

## 2. RIGHT Function

Extract the last 3 digits from Employee ID.

### Formula

```excel
=RIGHT(A2,3)
```

---

## 3. TRIM Function

Remove extra spaces from employee names.

Example:

```excel
=TRIM(B2)
```

---

## 4. LEN Function

Find the total number of characters in Employee Name.

### Formula

```excel
=LEN(B2)
```

---

## 5. SUM Function

Calculate total Salary + Bonus.

### Formula

```excel
=D2+E2
```

---

## 6. AVERAGE Function

Find the average salary of employees.

### Formula

```excel
=AVERAGE(D2:D6)
```

---

## 7. MAX Function

Find the highest salary.

### Formula

```excel
=MAX(D2:D6)
```

---

## 8. MIN Function

Find the lowest salary.

### Formula

```excel
=MIN(D2:D6)
```

---

## 9. COUNT Function

Count how many employees are listed.

### Formula

```excel
=COUNT(D2:D6)
```

---

# Sample Output Table

| Employee Name | LEFT | RIGHT | LEN | Total Salary |
| ------------- | ---- | ----- | --- | ------------ |
| Aman Sharma   | EMP  | 101   | 12  | 28000        |
| Riya Verma    | EMP  | 102   | 10  | 34500        |
| Karan Singh   | EMP  | 103   | 12  | 50000        |
| Neha Kapoor   | EMP  | 104   | 12  | 31500        |
| Raj Malhotra  | EMP  | 105   | 13  | 56000        |

---

# Final Summary Output

| Calculation     | Result |
| --------------- | ------ |
| Average Salary  | 36400  |
| Highest Salary  | 52000  |
| Lowest Salary   | 25000  |
| Total Employees | 5      |
