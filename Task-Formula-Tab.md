# Excel Tasks Using Formula Tab Features

## (AND, OR Functions + Define Name + Formula Auditing + Calculation Options)

---

# 🟢 Task 1: Scholarship Eligibility Using AND Function

## 📋 Create Table

| A       | B           | C     | D         |
| ------- | ----------- | ----- | --------- |
| Student | Attendance% | Marks | Eligible? |
| Aman    | 85          | 78    |           |
| Simran  | 65          | 82    |           |
| Ravi    | 90          | 88    |           |
| Neha    | 75          | 45    |           |

---

## ✅ Task

A student is eligible for scholarship only if:

* Attendance ≥ 75
* Marks ≥ 60

### Formula in D2:

```excel id="8i2lf9"
=AND(B2>=75,C2>=60)
```

Drag the formula down.

---

## 🎯 Sample Output

| Student | Attendance% | Marks | Eligible? |
| ------- | ----------- | ----- | --------- |
| Aman    | 85          | 78    | TRUE      |
| Simran  | 65          | 82    | FALSE     |
| Ravi    | 90          | 88    | TRUE      |
| Neha    | 75          | 45    | FALSE     |

---

# 🟢 Task 2: Employee Bonus Using OR Function

## 📋 Create Table

| A        | B     | C      | D      |
| -------- | ----- | ------ | ------ |
| Employee | Sales | Rating | Bonus? |
| Raj      | 60000 | 4      |        |
| Karan    | 35000 | 5      |        |
| Meena    | 25000 | 3      |        |
| Pooja    | 70000 | 2      |        |

---

## ✅ Task

Employee gets bonus if:

* Sales > 50000
  OR
* Rating = 5

### Formula in D2:

```excel id="x5s2f4"
=OR(B2>50000,C2=5)
```

Drag the formula down.

---

## 🎯 Sample Output

| Employee | Sales | Rating | Bonus? |
| -------- | ----- | ------ | ------ |
| Raj      | 60000 | 4      | TRUE   |
| Karan    | 35000 | 5      | TRUE   |
| Meena    | 25000 | 3      | FALSE  |
| Pooja    | 70000 | 2      | TRUE   |

---

# 🟢 Task 3: Define Name Feature

## 📋 Create Table

| A        | B     |
| -------- | ----- |
| Product  | Price |
| Laptop   | 45000 |
| Mouse    | 1200  |
| Keyboard | 2500  |
| Monitor  | 15000 |

---

## ✅ Task

### Steps

1. Select cells **B2:B5**
2. Go to **Formula Tab → Define Name**
3. Give name:

```text
ProductPrice
```

4. In another cell calculate total:

```excel id="xmpc1v"
=SUM(ProductPrice)
```

---

## 🎯 Sample Output

| Formula            | Result |
| ------------------ | ------ |
| =SUM(ProductPrice) | 63700  |

---

# 🟢 Task 4: Formula Auditing (Trace Precedents & Dependents)

## 📋 Create Table

| A        | B        | C       |
| -------- | -------- | ------- |
| Product  | Quantity | Total   |
| Pen      | 10       | =B2*20  |
| Notebook | 5        | =B3*50  |
| Bag      | 2        | =B4*500 |

---

## ✅ Task

Use **Formula Auditing Tools** from Formula Tab:

### Perform:

* Trace Precedents
* Trace Dependents
* Show Formulas

---

## 🎯 What Students Will Observe

* Arrows showing linked cells
* Which cells affect formulas
* Formula visibility instead of values

Example:

| Normal View | Show Formula View |
| ----------- | ----------------- |
| 200         | =B2*20            |

---

# 🟢 Task 5: Calculation Options

## 📋 Create Table

| A       | B       | C      |
| ------- | ------- | ------ |
| Number1 | Number2 | Sum    |
| 10      | 20      | =A2+B2 |

---

## ✅ Task

### Steps

1. Go to:
   **Formula Tab → Calculation Options**

2. Change from:

   * Automatic → Manual

3. Change A2 value from 10 to 50

4. Observe:

   * Formula does not update automatically

5. Press:

```text
F9
```

to recalculate workbook.

---

## 🎯 Sample Observation

| Before F9 | After F9 |
| --------- | -------- |
| 30        | 70       |

---

# 🎯 Learning Outcomes

Students will learn:

* AND logical function
* OR logical function
* Define Name feature
* Formula Auditing tools
* Manual vs Automatic calculations
* Formula dependency tracking in Excel
