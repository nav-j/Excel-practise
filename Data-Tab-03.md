## Advanced Excel Task — Scenario Manager & Data Table

Create a **Sales Profit Analysis Workbook** using:

* What-If Analysis
* Scenario Manager
* One Variable Data Table
* Two Variable Data Table

This task simulates a real business profit prediction system.

##  Main Data Table

| A                        | B     |
| ------------------------ | ----- |
| Selling Price per Laptop | 50000 |
| Cost Price per Laptop    | 42000 |
| Units Sold               | 100   |
| Total Revenue            |       |
| Total Cost               |       |
| Profit                   |       |

### Scenario

A company sells laptops online.
Management wants to analyze:

* Profit under different sales conditions
* Effect of changing quantity and price
* Best and worst business situations

You are asked to create a dynamic profit calculator.

###  Task 
Create 3 business scenarios:

#### Scenario 1 — Best Case

| Setting       | Value |
| ------------- | ----- |
| Selling Price | 55000 |
| Units Sold    | 150   |

---

#### Scenario 2 — Average Case

| Setting       | Value |
| ------------- | ----- |
| Selling Price | 50000 |
| Units Sold    | 100   |

---

#### Scenario 3 — Worst Case

| Setting       | Value |
| ------------- | ----- |
| Selling Price | 45000 |
| Units Sold    | 70    |


Change:

* Selling Price
* Units Sold

Generate:

* Scenario Summary Report

###  Expected Profit Results

| Scenario     | Profit  |
| ------------ | ------- |
| Best Case    | 1950000 |
| Average Case | 800000  |
| Worst Case   | 210000  |

###  Task

Analyze how profit changes when Units Sold changes using Data Table.

###  Create This Table

| Units Sold | Profit |
| ---------- | ------ |
| 50         |        |
| 75         |        |
| 100        |        |
| 125        |        |
| 150        |        |

### Expected Output

| Units Sold | Profit  |
| ---------- | ------- |
| 50         | 400000  |
| 75         | 600000  |
| 100        | 800000  |
| 125        | 1000000 |
| 150        | 1200000 |

###  Task — Two Variable Data Table

Analyze profit based on:

* Different Selling Prices
* Different Units Sold

### Create This Structure

| Profit | 50 | 100 | 150 |
| ------ | -- | --- | --- |
| 45000  |    |     |     |
| 50000  |    |     |     |
| 55000  |    |     |     |

### Expected Output

| Selling Price | 50 Units | 100 Units | 150 Units |
| ------------- | -------- | --------- | --------- |
| 45000         | 150000   | 300000    | 450000    |
| 50000         | 400000   | 800000    | 1200000   |
| 55000         | 650000   | 1300000   | 1950000   |

### Bonus Challenge

#### Add Conditional Formatting

* Profit > 1,000,000 → Green
* Profit < 500,000 → Red
