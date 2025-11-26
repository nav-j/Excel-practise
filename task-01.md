
# 🎓 Student Performance Sheet in Excel

This guide explains how to create a Student Performance Sheet in Excel to calculate **Total**, **Average**, and **Percentage** based on student scores.

---

## 🧱 Step 1: Set Up the Sheet Layout

### ➤ Headers (Row 1)
| Cell | Content        |
|------|----------------|
| A1   | Student Name   |
| B1   | Subject 1      |
| C1   | Subject 2      |
| D1   | Subject 3      |
| E1   | Subject 4      |
| F1   | Total          |
| G1   | Average        |
| H1   | Percentage     |

### ➤ Student Data Example
| Student Name | Subject 1 | Subject 2 | Subject 3 | Subject 4 |
|--------------|-----------|-----------|-----------|-----------|
| John         | 85        | 90        | 78        | 88        |

Add as many rows as needed for additional students.

---

## ➕ Step 2: Insert Formulas

### ✅ Total
In cell **F2**, enter:

```
=SUM(B2:E2)
```

Then drag the formula down to apply it for all students.

### ✅ Average
In cell **G2**, enter:

```
=AVERAGE(B2:E2)
```

Drag the formula down to apply it for all students.

### ✅ Percentage
In cell **H2**, enter:

```
=F2/400*100
```

(Assuming each subject is out of 100)

Drag the formula down to apply it for all students.

---

## 🎨 Step 3: Format the Data

- **Total and Average Columns**: Format as numbers (no decimals if needed).
- **Percentage Column**: Format as a percentage (e.g., 85%).
- **Headers**: Bold and Center-align cells A1 to H1.
- **Borders**: Add borders to the full range (e.g., A1:H100) for visibility.

---

## 📊 Example Sheet Layout

| Student Name | Subject 1 | Subject 2 | Subject 3 | Subject 4 | Total | Average | Percentage |
|--------------|-----------|-----------|-----------|-----------|-------|---------|------------|
| John         | 85        | 90        | 78        | 88        | 341   | 85.25   | 85.25%     |
| Jane         | 92        | 81        | 84        | 77        | 334   | 83.5    | 83.5%      |
| Mike         | 78        | 85        | 80        | 90        | 333   | 83.25   | 83.25%     |

---

## ✨ Step 4: Final Touches

- Adjust column widths for clarity.
- Apply conditional formatting to highlight:
  - Low scores (e.g., < 50)
  - High performers (e.g., > 90%)

> ✅ This sheet will automatically update results as scores are changed.

