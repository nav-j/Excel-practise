# 📊 MS Excel Practical Task – VLOOKUP, HLOOKUP, AND & OR Functions

## Student Information Management System

### Part 1: Create the Student Data Table

Enter the following data in Excel (A1:F11):

| ID  | Name   | Course          | Fee   | Attendance % | Grade |
| --- | ------ | --------------- | ----- | ------------ | ----- |
| 101 | Aman   | Python          | 12000 | 95           | A     |
| 102 | Simran | AI              | 15000 | 88           | B     |
| 103 | Rohit  | Web Development | 10000 | 92           | A     |
| 104 | Priya  | Python          | 12000 | 85           | B     |
| 105 | Karan  | AI              | 15000 | 98           | A     |
| 106 | Neha   | Python          | 12000 | 80           | C     |
| 107 | Arjun  | Web Development | 10000 | 75           | C     |
| 108 | Mehak  | AI              | 15000 | 90           | A     |
| 109 | Rahul  | Python          | 12000 | 99           | A     |
| 110 | Sonia  | Web Development | 10000 | 87           | B     |

---

# Part 2: VLOOKUP Task

### Create Search Section

| Student ID | Student Name |
| ---------- | ------------ |
| 105        | ?            |

Suppose Student ID is entered in cell H2.

Use VLOOKUP to fetch the student's name.

Formula:

```excel
=VLOOKUP(H2,A2:F11,2,FALSE)
```

### Additional Tasks

Find Course:

```excel
=VLOOKUP(H2,A2:F11,3,FALSE)
```

Find Fee:

```excel
=VLOOKUP(H2,A2:F11,4,FALSE)
```

Find Attendance:

```excel
=VLOOKUP(H2,A2:F11,5,FALSE)
```

---

# Part 3: HLOOKUP Task

Create the following table:

|          | Jan   | Feb   | Mar   | Apr   |
| -------- | ----- | ----- | ----- | ----- |
| Sales    | 25000 | 30000 | 28000 | 35000 |
| Expenses | 15000 | 18000 | 17000 | 20000 |

Suppose month name is entered in H15.

### Find Sales

```excel
=HLOOKUP(H15,A15:E17,2,FALSE)
```

### Find Expenses

```excel
=HLOOKUP(H15,A15:E17,3,FALSE)
```

---

# Part 4: AND Function Task

### Eligible for Scholarship

Condition:

* Attendance ≥ 90
* Grade = A

Create a new column "Scholarship Status".

Formula:

```excel
=IF(AND(E2>=90,F2="A"),"Eligible","Not Eligible")
```

---

# Part 5: OR Function Task

### Exam Re-Appear Required

Condition:

* Attendance < 80
* Grade = C

Formula:

```excel
=IF(OR(E2<80,F2="C"),"Re-Appear","Pass")
```

---

# Part 6: Combined AND + OR Task

### Placement Eligibility

Condition:

Student is eligible if:

* Attendance ≥ 85
  AND
* Grade A or Grade B

Formula:

```excel
=IF(AND(E2>=85,OR(F2="A",F2="B")),"Eligible","Not Eligible")
```

---

# Bonus Challenge

Create a Student Search Dashboard where the user enters a Student ID and Excel automatically displays:

* Name
* Course
* Fee
* Attendance
* Grade
* Scholarship Status

using **VLOOKUP** formulas.

### Skills Covered

✅ VLOOKUP
✅ HLOOKUP
✅ IF Function
✅ AND Function
✅ OR Function
✅ Nested AND + OR
✅ Student Search Dashboard

**Assignment Marks: 50**
**Difficulty Level: Intermediate Excel**
