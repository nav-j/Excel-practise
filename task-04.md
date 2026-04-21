
# 📊 Excel Task: Sales Commission Calculation

## 🔧 Task Description

This is a simple and practical Excel task designed to help you understand the difference between **absolute** and **relative** cell references in Excel.

You are given a table of sales data for a team of sales representatives. Your goal is to calculate the **commission earned** by each representative using the correct referencing techniques.

---

## 📁 Given Data

| Rep Name | Total Sales | Commission Rate | Commission Earned |
|----------|-------------|------------------|-------------------|
| Alice    | 5000        |                  |                   |
| Bob      | 3000        |                  |                   |
| Clara    | 7000        |                  |                   |
| Dan      | 4000        |                  |                   |

✅ **Commission Rate** is **10%**, which should be entered in **cell C1**.

---

## 📌 Task Instructions

1. **Enter** the commission rate `10%` in **cell C1**.
2. In **cell D2**, calculate the commission earned by Alice using the formula:  
   ```excel
   =B2*$C$1
* `B2` is a **relative reference** (it changes as you copy the formula down).
* `$C$1` is an **absolute reference** (it stays fixed for all rows).

3. **Copy or drag the formula** from **D2 to D5** to calculate the commission for the other sales reps.

---

## 🧠 Expected Learning Outcome

* ✅ Understand how **relative references** adjust when formulas are copied to other cells.
* ✅ Learn that **absolute references** (using the `$` symbol) keep a reference fixed no matter where the formula is moved or copied.

---

> 💡 Tip: Use `F4` in Excel while editing a cell reference to quickly toggle between relative and absolute reference
