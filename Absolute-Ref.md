# Easy Excel Tasks Using Absolute Reference

#  Task 1: Student Bonus Marks

##  Create Table

| A            | B     | C           |
| ------------ | ----- | ----------- |
| Student Name | Marks | Final Marks |
| Aman         | 78    |             |
| Simran       | 65    |             |
| Ravi         | 80    |             |
| Neha         | 72    |             |

### Bonus Marks

| E           | F |
| ----------- | - |
| Bonus Marks | 5 |

---

##  Task

Add bonus marks to each student using **absolute reference**.

### Formula in C2:

```excel id="j7ed0n"
=B2+$F$1
```

Drag the formula down.

---

## Sample Output

| Student Name | Marks | Final Marks |
| ------------ | ----- | ----------- |
| Aman         | 78    | 83          |
| Simran       | 65    | 70          |
| Ravi         | 80    | 85          |
| Neha         | 72    | 77          |


# Task 2: Product Price with Tax

##  Create Table

| A        | B     | C              |
| -------- | ----- | -------------- |
| Product  | Price | Price with Tax |
| Pen      | 20    |                |
| Notebook | 50    |                |
| Bag      | 500   |                |
| Bottle   | 120   |                |

### Tax Rate

| E        | F   |
| -------- | --- |
| Tax Rate | 10% |

---

##  Task

Calculate final price after adding tax using absolute reference.

### Formula in C2:

```excel id="0msiww"
=B2+(B2*$F$1)
```

Drag down the formula.

## Sample Output

| Product  | Price | Price with Tax |
| -------- | ----- | -------------- |
| Pen      | 20    | 22             |
| Notebook | 50    | 55             |
| Bag      | 500   | 550            |
| Bottle   | 120   | 132            |


---

#  Task 3: Salary Increment

##  Create Table

| A        | B      | C          |
| -------- | ------ | ---------- |
| Employee | Salary | New Salary |
| Raj      | 25000  |            |
| Karan    | 30000  |            |
| Meena    | 28000  |            |
| Pooja    | 35000  |            |

### Increment Rate

| E              | F  |
| -------------- | -- |
| Increment Rate | 8% |

---

##  Task

Increase salary using absolute reference.

### Formula in C2:

```excel id="r9lr6v"
=B2+(B2*$F$1)
```

Drag the formula down.

## Sample Output

| Employee | Salary | New Salary |
| -------- | ------ | ---------- |
| Raj      | 25000  | 27000      |
| Karan    | 30000  | 32400      |
| Meena    | 28000  | 30240      |
| Pooja    | 35000  | 37800      |


---

#  Task 4: Shop Discount Calculation

##  Create Table

| A     | B      | C            |
| ----- | ------ | ------------ |
| Item  | Amount | Final Amount |
| Shoes | 2000   |              |
| Watch | 3500   |              |
| Shirt | 1200   |              |
| Jeans | 1800   |              |

### Discount

| E        | F   |
| -------- | --- |
| Discount | 15% |

---

##  Task

Calculate amount after discount.

### Formula in C2:

```excel id="d4u8eq"
=B2-(B2*$F$1)
```

Drag down the formula.

## Sample Output

| Item  | Amount | Final Amount |
| ----- | ------ | ------------ |
| Shoes | 2000   | 1700         |
| Watch | 3500   | 2975         |
| Shirt | 1200   | 1020         |
| Jeans | 1800   | 1530         |


---

#  What Students Will Learn

* Using `$` for absolute reference
* Formula dragging
* Basic calculations in Excel
* Tax, bonus, salary, and discount calculations
