#  Excel Task: Employee Bonus Eligibility Checker (With Solution)

##  Task Description

This task helps you practice using the `AND` and `OR` logical functions in Excel to check bonus eligibility of employees based on their performance and experience.

---

##  Given Data

| Employee Name | Performance Rating (out of 5) | Years of Experience | Eligible (AND) | Eligible (OR) |
|---------------|-------------------------------|----------------------|----------------|---------------|
| Meena         | 4.5                           | 6                    |                |               |
| Ravi          | 3.0                           | 8                    |                |               |
| Sonia         | 4.2                           | 3                    |                |               |
| Ajay          | 2.5                           | 2                    |                |               |

---

##  Eligibility Criteria

1. **Eligible (AND)**:
   - Performance Rating ≥ 4
   - Years of Experience ≥ 5  
   ✅ Use `AND` to check if **both** conditions are satisfied.

2. **Eligible (OR)**:
   - Performance Rating ≥ 4 **OR**
   - Years of Experience ≥ 5  
   ✅ Use `OR` to check if **either** condition is satisfied.

---

## ✅ Solution Steps

1. In **cell D2**, enter the formula using `AND`:
   ```excel
   =AND(B2>=4, C2>=5)
   ```

2. In **cell E2**, enter the formula using `OR`:

   ```excel
   =OR(B2>=4, C2>=5)
   ```

3. Drag the formulas in **D2** and **E2** down to row 5.

---

## ✅ Final Output Example

| Employee Name | Performance Rating | Years of Experience | Eligible (AND) | Eligible (OR) |
| ------------- | ------------------ | ------------------- | -------------- | ------------- |
| Meena         | 4.5                | 6                   | TRUE           | TRUE          |
| Ravi          | 3.0                | 8                   | FALSE          | TRUE          |
| Sonia         | 4.2                | 3                   | FALSE          | TRUE          |
| Ajay          | 2.5                | 2                   | FALSE          | FALSE         |

---

##  Learning Recap

* ✅ `AND` checks if **all** given conditions are met.
* ✅ `OR` checks if **any** given condition is met.
* ✅ Logical functions are useful for rules, validations, and eligibility logic in Excel.

---

> 💼 Bonus Tip: You can use `IF(AND(...), "Yes", "No")` to return custom labels instead of TRUE/FALSE.
