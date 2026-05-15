# Excel Task – Goal Seek (With Solution)

## Scenario

You are working as a sales manager in a company. The company wants to achieve different profit targets by changing the number of units sold using **Goal Seek**.

---

# Step 1: Enter the Following Data

| Product | Selling Price per Unit | Cost per Unit | Units Sold | Total Profit |
| ------- | ---------------------- | ------------- | ---------- | ------------ |
| Laptop  | 50000                  | 42000         | 20         |              |

---

# Step 2: Apply Formula

In cell **E2**, enter:

```excel id="njlwm0"
=(B2-C2)*D2
```

---

# Current Output

| Product | Selling Price | Cost Price | Units Sold | Total Profit |
| ------- | ------------- | ---------- | ---------- | ------------ |
| Laptop  | 50000         | 42000      | 20         | 160000       |

---

# Main Goal Seek Task

## Target Profit = ₹4,00,000

### Goal Seek Settings

| Option           | Value  |
| ---------------- | ------ |
| Set Cell         | E2     |
| To Value         | 400000 |
| By Changing Cell | D2     |

---

# Solution

## Calculation

Profit per unit:

```excel id="1ct9z9"
=50000-42000
```

Result = ₹8,000

Required units:

```excel id="c9dfoj"
=400000/8000
```

Result = **50 Units**

---

# Final Output After Goal Seek

| Product | Selling Price | Cost Price | Units Sold | Total Profit |
| ------- | ------------- | ---------- | ---------- | ------------ |
| Laptop  | 50000         | 42000      | 50         | 400000       |

---

# Practice Task 1

## Find Units Needed for ₹8,00,000 Profit

### Goal Seek Settings

| Option           | Value  |
| ---------------- | ------ |
| Set Cell         | E2     |
| To Value         | 800000 |
| By Changing Cell | D2     |

---

# Solution

```excel id="b0uqlx"
=800000/8000
```

Result = **100 Units**

---

# Output

| Product | Units Sold | Total Profit |
| ------- | ---------- | ------------ |
| Laptop  | 100        | 800000       |

---

# Practice Task 2

## Change Selling Price to ₹55,000 and Find Units Needed for ₹5,00,000 Profit

---

# Updated Data

| Selling Price | Cost Price |
| ------------- | ---------- |
| 55000         | 42000      |

Profit per unit:

```excel id="lmq2l8"
=55000-42000
```

Result = ₹13,000

---

# Goal Seek Settings

| Option           | Value  |
| ---------------- | ------ |
| Set Cell         | E2     |
| To Value         | 500000 |
| By Changing Cell | D2     |

---

# Solution

```excel id="11cl0j"
=500000/13000
```

Result ≈ **39 Units**

(Excel may show 38.46 or round to 39)

---

# Output

| Product | Units Sold | Total Profit |
| ------- | ---------- | ------------ |
| Laptop  | 39         | 500000       |

---

# Practice Task 3 – Mobile Phone Example

## Data

| Product      | Selling Price | Cost Price | Units Sold | Total Profit |
| ------------ | ------------- | ---------- | ---------- | ------------ |
| Mobile Phone | 30000         | 24000      | 10         |              |

---

# Formula

```excel id="72twgq"
=(B2-C2)*D2
```

---

# Target Profit = ₹3,00,000

### Goal Seek Settings

| Option           | Value  |
| ---------------- | ------ |
| Set Cell         | E2     |
| To Value         | 300000 |
| By Changing Cell | D2     |

---

# Solution

Profit per unit:

```excel id="w4hcgx"
=30000-24000
```

Result = ₹6,000

Required units:

```excel id="7s9jz3"
=300000/6000
```

Result = **50 Units**

---

# Final Output

| Product      | Units Sold | Total Profit |
| ------------ | ---------- | ------------ |
| Mobile Phone | 50         | 300000       |

---

# Learning Outcome

Students will learn:

* How to use Goal Seek
* What-If Analysis in Excel
* Target-based calculations
* Business profit forecasting using Excel
