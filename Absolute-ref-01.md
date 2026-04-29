# Excel Task: Absolute Reference Formula Practice

##  Objective

Learn how to use **Absolute Reference (`$`)** in Excel formulas to calculate discounted prices and tax amounts correctly.

---

#  Task: Product Billing Sheet

Create the following table in Excel:

| A            | B     | C        | D           | E            |
| ------------ | ----- | -------- | ----------- | ------------ |
| Product Name | Price | Quantity | Total Price | Final Amount |
| Laptop       | 45000 | 2        |             |              |
| Mouse        | 800   | 5        |             |              |
| Keyboard     | 1500  | 3        |             |              |
| Monitor      | 12000 | 2        |             |              |
| Printer      | 9000  | 1        |             |              |

---

##  Additional Information

Below the table enter:

| G        | H   |
| -------- | --- |
| GST Rate | 18% |
| Discount | 10% |

---

# Tasks to Perform

### 1. Calculate Total Price

In column **D**, calculate:

```excel
=Price * Quantity
```

Example formula in **D2**:

```excel
=B2*C2
```

Drag the formula down.

---

### 2. Calculate Final Amount using Absolute Reference

Final Amount Formula:

```excel
Total Price + GST - Discount
```

Use **absolute reference** for GST and Discount cells.

Example formula in **E2**:

```excel
=D2+(D2*$H$1)-(D2*$H$2)
```

Drag the formula down.

---

#  Expected Output Sample

| Product Name | Total Price | Final Amount |
| ------------ | ----------- | ------------ |
| Laptop       | 90000       | 97200        |
| Mouse        | 4000        | 4320         |
| Keyboard     | 4500        | 4860         |

---

#  Learning Outcome

After completing this task, students will learn:

* Difference between relative and absolute reference
* Use of `$` symbol in formulas
* Formula dragging without changing fixed cells
* Basic billing calculations in Excel
