
# ➕ Excel Task: Product Cost Calculator (With Solution)

## 🔧 Task Description

This Excel task helps you practice using **arithmetic operators** (`+`, `-`, `*`, `/`) to calculate the cost, discount, and final price of products based on price, quantity, and discount percentage.

---

## 📁 Given Data

| Product Name | Unit Price | Quantity | Discount (%) | Total Cost | Discount Amount | Final Price |
|--------------|------------|----------|--------------|------------|------------------|-------------|
| Pen          | 10         | 20       | 5            |            |                  |             |
| Notebook     | 50         | 5        | 10           |            |                  |             |
| Eraser       | 5          | 10       | 0            |            |                  |             |
| Marker       | 30         | 3        | 15           |            |                  |             |

---

## ✅ Solution Steps

1. **Total Cost** = `Unit Price × Quantity`  
   Formula in **E2**:  
   ```excel
   =B2*C2
2. **Discount Amount** = `Total Cost × (Discount ÷ 100)`
   Formula in **F2**:

   ```excel
   =E2*(D2/100)
   ```

3. **Final Price** = `Total Cost − Discount Amount`
   Formula in **G2**:

   ```excel
   =E2-F2
   ```

📌 **Drag the formulas** from row 2 down to fill rows 3 to 5.

---

## ✅ Final Output Example

| Product Name | Unit Price | Quantity | Discount (%) | Total Cost | Discount Amount | Final Price |
| ------------ | ---------- | -------- | ------------ | ---------- | --------------- | ----------- |
| Pen          | 10         | 20       | 5            | 200        | 10              | 190         |
| Notebook     | 50         | 5        | 10           | 250        | 25              | 225         |
| Eraser       | 5          | 10       | 0            | 50         | 0               | 50          |
| Marker       | 30         | 3        | 15           | 90         | 13.5            | 76.5        |

---

## 🧠 Learning Recap

* ✅ Used `*` to multiply price and quantity.
* ✅ Used `/` and `*` to calculate percentage discounts.
* ✅ Used `-` to subtract discount from total.
* ✅ Understood the order of operations in Excel formulas.

---

> 🔍 Try changing the quantity or discount values and see how final prices update automatically!

```

---
