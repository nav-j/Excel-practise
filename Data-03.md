# 📊 Advanced Excel Task — Scenario Manager & Data Table

Using Microsoft Excel

---

# 🎯 Objective

Create a **Sales Profit Analysis Workbook** using:

* What-If Analysis
* Scenario Manager
* One Variable Data Table
* Two Variable Data Table

This task simulates a real business profit prediction system.

---

# 🏢 Scenario

A company sells laptops online.
Management wants to analyze:

* Profit under different sales conditions
* Effect of changing quantity and price
* Best and worst business situations

You are asked to create a dynamic profit calculator.

---

# 🧾 Step 1 — Create Main Data Table

| A                        | B     |
| ------------------------ | ----- |
| Selling Price per Laptop | 50000 |
| Cost Price per Laptop    | 42000 |
| Units Sold               | 100   |
| Total Revenue            |       |
| Total Cost               |       |
| Profit                   |       |

---

# 🔹 Step 2 — Apply Formulas

## ✅ Formula for Total Revenue

```excel
=B1*B3
```

## ✅ Formula for Total Cost

```excel
=B2*B3
```

## ✅ Formula for Profit

```excel
=B4-B5
```

---

# ✅ Expected Output

| Item          | Value   |
| ------------- | ------- |
| Total Revenue | 5000000 |
| Total Cost    | 4200000 |
| Profit        | 800000  |

---

# 🔥 Task 1 — Scenario Manager

## 🎯 Objective

Create 3 business scenarios:

---

## ✅ Scenario 1 — Best Case

| Setting       | Value |
| ------------- | ----- |
| Selling Price | 55000 |
| Units Sold    | 150   |

---

## ✅ Scenario 2 — Average Case

| Setting       | Value |
| ------------- | ----- |
| Selling Price | 50000 |
| Units Sold    | 100   |

---

## ✅ Scenario 3 — Worst Case

| Setting       | Value |
| ------------- | ----- |
| Selling Price | 45000 |
| Units Sold    | 70    |

---

# ⚙️ Requirement

Use:

```text
Data → What-If Analysis → Scenario Manager
```

Change:

* Selling Price
* Units Sold

Generate:

* Scenario Summary Report

---

# ✅ Expected Profit Results

| Scenario     | Profit  |
| ------------ | ------- |
| Best Case    | 1950000 |
| Average Case | 800000  |
| Worst Case   | 210000  |

---

# 🔥 Task 2 — One Variable Data Table

## 🎯 Objective

Analyze how profit changes when Units Sold changes.

---

## 🧾 Create This Table

| Units Sold | Profit |
| ---------- | ------ |
| 50         |        |
| 75         |        |
| 100        |        |
| 125        |        |
| 150        |        |

---

# ⚙️ Requirement

Use:

```text
Data → What-If Analysis → Data Table
```

Input Cell:

* Units Sold cell

---

# ✅ Expected Output

| Units Sold | Profit  |
| ---------- | ------- |
| 50         | 400000  |
| 75         | 600000  |
| 100        | 800000  |
| 125        | 1000000 |
| 150        | 1200000 |

---

# 🔥 Task 3 — Two Variable Data Table

## 🎯 Objective

Analyze profit based on:

* Different Selling Prices
* Different Units Sold

---

# 🧾 Create This Structure

| Profit | 50 | 100 | 150 |
| ------ | -- | --- | --- |
| 45000  |    |     |     |
| 50000  |    |     |     |
| 55000  |    |     |     |

---

# ⚙️ Requirement

Use:

```text
Data → What-If Analysis → Data Table
```

### Row Input Cell

Units Sold

### Column Input Cell

Selling Price

---

# ✅ Expected Output

| Selling Price | 50 Units | 100 Units | 150 Units |
| ------------- | -------- | --------- | --------- |
| 45000         | 150000   | 300000    | 450000    |
| 50000         | 400000   | 800000    | 1200000   |
| 55000         | 650000   | 1300000   | 1950000   |

---

# 🚀 Bonus Challenge

## 🎯 Add Conditional Formatting

### Rules:

* Profit > 1,000,000 → Green
* Profit < 500,000 → Red

---
# Solution
'
Below is the **complete solved version** of the Excel task, including formulas, Scenario Manager setup, One Variable Data Table, Two Variable Data Table, and Conditional Formatting.

# Sales Profit Analysis Workbook — Solution

## 1. Main Data Table

Enter the following in Excel:

| Cell | Item                     | Value / Formula |
| ---- | ------------------------ | --------------: |
| A1   | Selling Price per Laptop |                 |
| B1   | 50000                    |                 |
| A2   | Cost Price per Laptop    |                 |
| B2   | 42000                    |                 |
| A3   | Units Sold               |                 |
| B3   | 100                      |                 |
| A4   | Total Revenue            |        `=B1*B3` |
| A5   | Total Cost               |        `=B2*B3` |
| A6   | Profit                   |        `=B4-B5` |

### Result

With:

* Selling Price = ₹50,000
* Cost Price = ₹42,000
* Units Sold = 100

Excel calculates:

**Total Revenue**

```excel
=B1*B3
```

= ₹50,000 × 100
= **₹5,000,000**

**Total Cost**

```excel
=B2*B3
```

= ₹42,000 × 100
= **₹4,200,000**

**Profit**

```excel
=B4-B5
```

= ₹5,000,000 − ₹4,200,000
= **₹800,000**

So your main table becomes:

| Item                     |        Value |
| ------------------------ | -----------: |
| Selling Price per Laptop |      ₹50,000 |
| Cost Price per Laptop    |      ₹42,000 |
| Units Sold               |          100 |
| Total Revenue            |   ₹5,000,000 |
| Total Cost               |   ₹4,200,000 |
| **Profit**               | **₹800,000** |

---

# 2. Scenario Manager

Go to:

**Data → What-If Analysis → Scenario Manager**

Click **Add**.

---

## Scenario 1 — Best Case

Enter:

**Scenario name:**

```text
Best Case
```

**Changing cells:**

```text
B1,B3
```

Then enter:

| Cell | Value |
| ---- | ----: |
| B1   | 55000 |
| B3   |   150 |

Click **OK**.

Profit:

```text
(55,000 - 42,000) × 150
= 13,000 × 150
= ₹1,950,000
```

---

## Scenario 2 — Average Case

Add another scenario.

**Scenario name:**

```text
Average Case
```

Changing cells:

```text
B1,B3
```

Values:

| Cell | Value |
| ---- | ----: |
| B1   | 50000 |
| B3   |   100 |

Profit:

```text
(50,000 - 42,000) × 100
= 8,000 × 100
= ₹800,000
```

---

## Scenario 3 — Worst Case

Add another scenario.

**Scenario name:**

```text
Worst Case
```

Changing cells:

```text
B1,B3
```

Values:

| Cell | Value |
| ---- | ----: |
| B1   | 45000 |
| B3   |    70 |

Profit:

```text
(45,000 - 42,000) × 70
= 3,000 × 70
= ₹210,000
```

---

# 3. Create Scenario Summary Report

In **Scenario Manager**, click:

**Summary → Scenario Summary**

For **Result cells**, select:

```text
B6
```

Then click **OK**.

Excel will automatically create a new worksheet containing the Scenario Summary.

The important results will be:

| Scenario       | Selling Price | Units Sold |         Profit |
| -------------- | ------------: | ---------: | -------------: |
| Current Values |       ₹50,000 |        100 |       ₹800,000 |
| Best Case      |       ₹55,000 |        150 | **₹1,950,000** |
| Average Case   |       ₹50,000 |        100 |   **₹800,000** |
| Worst Case     |       ₹45,000 |         70 |   **₹210,000** |

### Final Scenario Results

| Scenario        |         Profit |
| --------------- | -------------: |
| 🟢 Best Case    | **₹1,950,000** |
| 🟡 Average Case |   **₹800,000** |
| 🔴 Worst Case   |   **₹210,000** |

---

# 4. One Variable Data Table

The purpose here is to see how **Units Sold** affects Profit while keeping:

* Selling Price = ₹50,000
* Cost Price = ₹42,000

Create the following table somewhere else, for example starting at **D1**:

| D          | E      |
| ---------- | ------ |
| Units Sold | Profit |
| 50         |        |
| 75         |        |
| 100        |        |
| 125        |        |
| 150        |        |

### Important Step

In **E1**, enter a reference to the Profit cell:

```excel
=B6
```

So your table should look like:

| D          |     E |
| ---------- | ----: |
| Units Sold | `=B6` |
| 50         |       |
| 75         |       |
| 100        |       |
| 125        |       |
| 150        |       |

Now select:

```text
D1:E6
```

Go to:

**Data → What-If Analysis → Data Table**

Because we are changing **Units Sold**, set:

**Column input cell:**

```text
B3
```

Leave **Row input cell** blank.

Click **OK**.

---

## One Variable Data Table — Expected Result

| Units Sold |         Profit |
| ---------: | -------------: |
|         50 |   **₹400,000** |
|         75 |   **₹600,000** |
|        100 |   **₹800,000** |
|        125 | **₹1,000,000** |
|        150 | **₹1,200,000** |

### Why?

Profit per laptop:

```text
Selling Price - Cost Price
= 50,000 - 42,000
= ₹8,000
```

Therefore:

```text
50 × 8,000 = ₹400,000
75 × 8,000 = ₹600,000
100 × 8,000 = ₹800,000
125 × 8,000 = ₹1,000,000
150 × 8,000 = ₹1,200,000
```

---

# 5. Two Variable Data Table

Now we want to analyze the effect of **both Selling Price and Units Sold**.

Create this structure, for example starting at **G1**:

| G      |  H |   I |   J |
| ------ | -: | --: | --: |
| Profit | 50 | 100 | 150 |
| 45000  |    |     |     |
| 50000  |    |     |     |
| 55000  |    |     |     |

The top row contains different **Units Sold** values.

The first column contains different **Selling Prices**.

### Very Important

The top-left cell **G1** should contain a reference to the Profit formula:

```excel
=B6
```

So:

| G     |  H |   I |   J |
| ----- | -: | --: | --: |
| `=B6` | 50 | 100 | 150 |
| 45000 |    |     |     |
| 50000 |    |     |     |
| 55000 |    |     |     |

---

## Create the Two Variable Data Table

Select the complete range:

```text
G1:J4
```

Then go to:

**Data → What-If Analysis → Data Table**

Set:

### Row input cell

```text
B3
```

because the top row contains different **Units Sold** values.

### Column input cell

```text
B1
```

because the first column contains different **Selling Prices**.

Click **OK**.

---

# 6. Two Variable Data Table — Final Answer

Excel should produce:

| Selling Price |     50 Units |      100 Units |      150 Units |
| ------------: | -----------: | -------------: | -------------: |
|       ₹45,000 | **₹150,000** |   **₹300,000** |   **₹450,000** |
|       ₹50,000 | **₹400,000** |   **₹800,000** | **₹1,200,000** |
|       ₹55,000 | **₹650,000** | **₹1,300,000** | **₹1,950,000** |

For example:

### ₹45,000 selling price and 50 units

```text
(45,000 - 42,000) × 50
= ₹150,000
```

### ₹50,000 selling price and 100 units

```text
(50,000 - 42,000) × 100
= ₹800,000
```

### ₹55,000 selling price and 150 units

```text
(55,000 - 42,000) × 150
= ₹1,950,000
```

---

# 7. Conditional Formatting

Apply conditional formatting to the **Profit values** in both data tables.

## Rule 1 — Profit Greater Than ₹1,000,000

Select the profit range.

Go to:

**Home → Conditional Formatting → Highlight Cells Rules → Greater Than**

Enter:

```text
1000000
```

Choose a **green fill**.

This will highlight:

* ₹1,200,000
* ₹1,300,000
* ₹1,950,000

---

## Rule 2 — Profit Less Than ₹500,000

Again go to:

**Conditional Formatting → Highlight Cells Rules → Less Than**

Enter:

```text
500000
```

Choose a **red fill**.

This will highlight:

* ₹150,000
* ₹300,000
* ₹400,000
* ₹450,000

### What about exactly ₹500,000?

Nothing happens because the rule is **less than 500,000**, not less than or equal to 500,000.

---

# 8. Final Workbook Structure

A good workbook can contain these sheets:

### Sheet 1 — `Profit Calculator`

```text
Selling Price per Laptop    ₹50,000
Cost Price per Laptop       ₹42,000
Units Sold                  100
Total Revenue               ₹5,000,000
Total Cost                  ₹4,200,000
Profit                      ₹800,000
```

### Sheet 2 — `Scenario Summary`

| Scenario     | Selling Price | Units Sold |         Profit |
| ------------ | ------------: | ---------: | -------------: |
| Best Case    |       ₹55,000 |        150 | **₹1,950,000** |
| Average Case |       ₹50,000 |        100 |   **₹800,000** |
| Worst Case   |       ₹45,000 |         70 |   **₹210,000** |

### Sheet 3 — `One Variable Data Table`

| Units Sold |     Profit |
| ---------: | ---------: |
|         50 |   ₹400,000 |
|         75 |   ₹600,000 |
|        100 |   ₹800,000 |
|        125 | ₹1,000,000 |
|        150 | ₹1,200,000 |

### Sheet 4 — `Two Variable Data Table`

| Selling Price | 50 Units |  100 Units |  150 Units |
| ------------: | -------: | ---------: | ---------: |
|       ₹45,000 | ₹150,000 |   ₹300,000 |   ₹450,000 |
|       ₹50,000 | ₹400,000 |   ₹800,000 | ₹1,200,000 |
|       ₹55,000 | ₹650,000 | ₹1,300,000 | ₹1,950,000 |

## Final Business Analysis

* **Best Case:** ₹1,950,000 profit
* **Average Case:** ₹800,000 profit
* **Worst Case:** ₹210,000 profit
* Increasing **units sold** increases profit when selling price remains above cost.
* Increasing **selling price** also increases profit.
* The highest profit occurs at **₹55,000 selling price and 150 units = ₹1,950,000**.
* The lowest profit occurs at **₹45,000 selling price and 50 units = ₹150,000** in the two-variable analysis.

