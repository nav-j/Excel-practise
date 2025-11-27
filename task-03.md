
# Excel Task: Student Pass/Fail Status

---

## Task Description

You are given a list of students and their marks in an exam.  
Use the `IF` function to determine whether each student has **Passed** or **Failed**.

 A student passes if their marks are **greater than or equal to 40**.

---

## Data Setup

| A             | B     | C        |
|---------------|-------|----------|
| Student Name  | Marks | Result   |
| Riya          | 72    |          |
| Arjun         | 35    |          |
| Simran        | 88    |          |
| Kabir         | 29    |          |
| Anjali        | 47    |          |

---

## Instructions

1. In **cell C2**, write an `IF` formula to check if the marks in cell B2 are greater than or equal to 40.
2. If the condition is true, the result should be **"Pass"**.
3. If the condition is false, the result should be **"Fail"**.
4. Drag the formula from C2 to C6 to apply it to the rest of the students.

---

## Expected Formula in C2

```excel
=IF(B2>=40, "Pass", "Fail")
````

---
