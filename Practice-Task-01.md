# 📊 Complete MS Excel Practical Task

## 🎯 Scenario

You are working as an Office Assistant in a training institute. Create a student fee management sheet in MS Excel and perform various calculations, formatting, sorting, filtering, and chart creation tasks.

---

# Part 1: Create the Data Table

Open MS Excel and enter the following data:

| Student ID | Student Name | Course          | Fee   | Paid  | Attendance % |
| ---------- | ------------ | --------------- | ----- | ----- | ------------ |
| 101        | Aman         | Python          | 12000 | 10000 | 95           |
| 102        | Simran       | AI              | 15000 | 12000 | 88           |
| 103        | Rohit        | Web Development | 10000 | 10000 | 92           |
| 104        | Priya        | Python          | 12000 | 8000  | 85           |
| 105        | Karan        | AI              | 15000 | 15000 | 98           |
| 106        | Neha         | Python          | 12000 | 9000  | 80           |
| 107        | Arjun        | Web Development | 10000 | 7000  | 75           |
| 108        | Mehak        | AI              | 15000 | 14000 | 90           |
| 109        | Rahul        | Python          | 12000 | 12000 | 99           |
| 110        | Sonia        | Web Development | 10000 | 9000  | 87           |

---

# Part 2: Formula Tasks

### 1. Calculate Due Fee

Create a new column named **Due Fee**.

Formula:

```excel
=D2-E2
```

---

### 2. Attendance Status

Create a new column named **Status**.

Condition:

* Attendance ≥ 90 → Excellent
* Attendance ≥ 80 → Good
* Attendance < 80 → Poor

Formula:

```excel
=IF(F2>=90,"Excellent",IF(F2>=80,"Good","Poor"))
```

---

### 3. Fee Status

Create another column named **Fee Status**.

Condition:

* Due Fee = 0 → Cleared
* Due Fee > 0 → Pending

Formula:

```excel
=IF(G2=0,"Cleared","Pending")
```

---

# Part 3: Basic Functions

Below the table calculate:

### Total Fee

```excel
=SUM(D2:D11)
```

### Total Paid

```excel
=SUM(E2:E11)
```

### Total Due

```excel
=SUM(G2:G11)
```

### Average Attendance

```excel
=AVERAGE(F2:F11)
```

### Highest Fee

```excel
=MAX(D2:D11)
```

### Lowest Fee

```excel
=MIN(D2:D11)
```

### Total Students

```excel
=COUNT(A2:A11)
```

---

# Part 4: Formatting Tasks

Perform the following:

✅ Convert the data into a Table (Ctrl + T)

✅ Apply a table style

✅ Make headings Bold

✅ Change heading background color

✅ Apply Currency format to Fee, Paid, and Due Fee columns

✅ Center-align all data

✅ Apply All Borders

---

# Part 5: Sorting

### Sort Students by Attendance

Sort Attendance % from Highest to Lowest.

---

# Part 6: Filtering

Apply filters and show:

1. Only Python students
2. Only AI students
3. Students with Pending Fees
4. Students with Excellent Attendance

---

# Part 7: Conditional Formatting

### Highlight Attendance

* Green if Attendance ≥ 90
* Yellow if Attendance 80–89
* Red if Attendance < 80

### Highlight Due Fee

* Red if Due Fee > 0

---

# Part 8: Charts

Create the following charts:

### Chart 1: Course-wise Student Count

Use a Pie Chart.

### Chart 2: Student vs Attendance

Use a Column Chart.

### Chart 3: Student vs Due Fee

Use a Bar Chart.

---

# Part 9: Data Validation

Create a drop-down list for Course:

* Python
* AI
* Web Development

Use:

**Data → Data Validation → List**

---

# Part 10: Advanced Tasks

### Count Python Students

```excel
=COUNTIF(C2:C11,"Python")
```

### Count AI Students

```excel
=COUNTIF(C2:C11,"AI")
```

### Total Fee Collected for Python

```excel
=SUMIF(C2:C11,"Python",E2:E11)
```

### Total Fee Collected for AI

```excel
=SUMIF(C2:C11,"AI",E2:E11)
```

### Students with Attendance Above 90

```excel
=COUNTIF(F2:F11,">90")
```

---

# Bonus Challenge

Create a Dashboard Sheet containing:

* Total Students
* Total Fee
* Total Paid
* Total Due
* Average Attendance
* Pie Chart (Course Distribution)
* Column Chart (Attendance Analysis)

This task covers:

* Data Entry
* Formulas
* Functions
* IF Statements
* COUNTIF
* SUMIF
* Formatting
* Conditional Formatting
* Sorting
* Filtering
* Data Validation
* Charts
* Dashboard Creation

It is suitable for a **full 3–4 hour MS Excel practical assignment** for students.
