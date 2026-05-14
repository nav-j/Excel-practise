# Excel Task – Sales Performance Analysis Using Custom Sort & Scenario Manager

## Objective

Create a professional Excel workbook to analyze employee sales performance using:

* **Custom Sort**
* **Scenario Manager**
* Basic formulas and formatting

---

# Scenario

You are working as a Sales Analyst in a company. The manager wants to:

1. Arrange employee data using **Custom Sort**
2. Compare different sales target situations using **Scenario Manager**
3. Analyze performance under different conditions

---

# Step 1: Create the Following Data Table

| Employee ID | Employee Name | Department  | Region | Monthly Sales | Target Sales | Bonus % |
| ----------- | ------------- | ----------- | ------ | ------------- | ------------ | ------- |
| E101        | Aman          | Electronics | North  | 85000         | 90000        | 5%      |
| E102        | Riya          | Clothing    | South  | 72000         | 70000        | 4%      |
| E103        | Kabir         | Grocery     | East   | 65000         | 75000        | 3%      |
| E104        | Simran        | Electronics | West   | 98000         | 95000        | 6%      |
| E105        | Raj           | Clothing    | North  | 54000         | 60000        | 2%      |
| E106        | Neha          | Grocery     | South  | 89000         | 85000        | 5%      |
| E107        | Arjun         | Electronics | East   | 76000         | 80000        | 4%      |
| E108        | Priya         | Clothing    | West   | 69000         | 70000        | 3%      |

---

# Step 2: Add Formulas

## 1. Performance Status

Create a new column named **Status**

Formula:

```excel
=IF(E2>=F2,"Achieved","Not Achieved")
```

---

## 2. Bonus Amount

Create another column named **Bonus Amount**

Formula:

```excel
=E2*G2
```

---

# Step 3: Apply Custom Sort

Use **Data → Sort → Custom Sort**

Apply the following sorting:

### Level 1

* Sort by: **Department**
* Order:

  * Electronics
  * Clothing
  * Grocery

### Level 2

* Then by: **Region**
* Order:

  * North
  * South
  * East
  * West

### Level 3

* Then by: **Monthly Sales**
* Order: Largest to Smallest

---

# Step 4: Use Scenario Manager

Go to:

```text
Data → What-If Analysis → Scenario Manager
```

Create the following scenarios by changing **Target Sales** values.

---

## Scenario 1: Normal Target

| Employee      | Target Sales    |
| ------------- | --------------- |
| All Employees | Existing Values |

---

## Scenario 2: Increased Target

Increase all Target Sales by **10%**

Example:

| Old Target | New Target |
| ---------- | ---------- |
| 90000      | 99000      |

---

## Scenario 3: Reduced Target

Decrease all Target Sales by **15%**

Example:

| Old Target | New Target |
| ---------- | ---------- |
| 90000      | 76500      |

---

# Step 5: Create Scenario Summary

Generate a **Scenario Summary Report** showing:

* Monthly Sales
* Target Sales
* Status
* Bonus Amount

Compare results under all scenarios.

---

# Additional Formatting Tasks

Apply the following:

* Format table using **Format as Table**
* Apply **Conditional Formatting**

  * Green for “Achieved”
  * Red for “Not Achieved”
* Add:

  * Company title
  * Bold headers
  * Currency formatting

---

# Expected Learning Outcomes

After completing this task, students will learn:

* Multi-level Custom Sorting
* Creating custom sort orders
* Using Scenario Manager
* Comparing multiple business situations
* Using IF formulas
* Professional Excel formatting

---

# Sample Output (After Custom Sort)

| Employee Name | Department  | Region | Monthly Sales | Status       |
| ------------- | ----------- | ------ | ------------- | ------------ |
| Simran        | Electronics | West   | 98000         | Achieved     |
| Aman          | Electronics | North  | 85000         | Not Achieved |
| Arjun         | Electronics | East   | 76000         | Not Achieved |
| Riya          | Clothing    | South  | 72000         | Achieved     |
| Raj           | Clothing    | North  | 54000         | Not Achieved |


## Solution

# Solution – Excel Task Using Custom Sort & Scenario Manager

# Step 1: Final Data Table with Formulas

| Employee ID | Employee Name | Department  | Region | Monthly Sales | Target Sales | Bonus % | Status       | Bonus Amount |
| ----------- | ------------- | ----------- | ------ | ------------- | ------------ | ------- | ------------ | ------------ |
| E101        | Aman          | Electronics | North  | 85000         | 90000        | 5%      | Not Achieved | 4250         |
| E102        | Riya          | Clothing    | South  | 72000         | 70000        | 4%      | Achieved     | 2880         |
| E103        | Kabir         | Grocery     | East   | 65000         | 75000        | 3%      | Not Achieved | 1950         |
| E104        | Simran        | Electronics | West   | 98000         | 95000        | 6%      | Achieved     | 5880         |
| E105        | Raj           | Clothing    | North  | 54000         | 60000        | 2%      | Not Achieved | 1080         |
| E106        | Neha          | Grocery     | South  | 89000         | 85000        | 5%      | Achieved     | 4450         |
| E107        | Arjun         | Electronics | East   | 76000         | 80000        | 4%      | Not Achieved | 3040         |
| E108        | Priya         | Clothing    | West   | 69000         | 70000        | 3%      | Not Achieved | 2070         |

---

# Formulas Used

## Status Formula

In cell H2:

```excel id="4oc80t"
=IF(E2>=F2,"Achieved","Not Achieved")
```

Copy down for all rows.

---

## Bonus Amount Formula

In cell I2:

```excel id="qv5u2x"
=E2*G2
```

Copy down for all rows.

---

# Step 2: Custom Sort Solution

Go to:

```text id="n8x5bh"
Data → Sort
```

Apply these levels:

| Sort Level | Column        | Order                          |
| ---------- | ------------- | ------------------------------ |
| Level 1    | Department    | Electronics, Clothing, Grocery |
| Level 2    | Region        | North, South, East, West       |
| Level 3    | Monthly Sales | Largest to Smallest            |

---

# Sample Output After Custom Sort

| Employee Name | Department  | Region | Monthly Sales |
| ------------- | ----------- | ------ | ------------- |
| Aman          | Electronics | North  | 85000         |
| Arjun         | Electronics | East   | 76000         |
| Simran        | Electronics | West   | 98000         |
| Raj           | Clothing    | North  | 54000         |
| Riya          | Clothing    | South  | 72000         |
| Priya         | Clothing    | West   | 69000         |
| Neha          | Grocery     | South  | 89000         |
| Kabir         | Grocery     | East   | 65000         |

---

# Step 3: Scenario Manager Solution

Go to:

```text id="8mh2ng"
Data → What-If Analysis → Scenario Manager
```

---

# Scenario 1 – Normal Target

(Original values)

| Employee | Target Sales |
| -------- | ------------ |
| Aman     | 90000        |
| Riya     | 70000        |
| Kabir    | 75000        |
| Simran   | 95000        |

---

# Scenario 2 – Increased Target (+10%)

## Updated Target Values

| Employee | Old Target | New Target |
| -------- | ---------- | ---------- |
| Aman     | 90000      | 99000      |
| Riya     | 70000      | 77000      |
| Kabir    | 75000      | 82500      |
| Simran   | 95000      | 104500     |

### Sample Output

| Employee | Monthly Sales | New Target | Status       |
| -------- | ------------- | ---------- | ------------ |
| Aman     | 85000         | 99000      | Not Achieved |
| Riya     | 72000         | 77000      | Not Achieved |
| Simran   | 98000         | 104500     | Not Achieved |

---

# Scenario 3 – Reduced Target (-15%)

## Updated Target Values

| Employee | Old Target | New Target |
| -------- | ---------- | ---------- |
| Aman     | 90000      | 76500      |
| Riya     | 70000      | 59500      |
| Kabir    | 75000      | 63750      |
| Simran   | 95000      | 80750      |

---

# Sample Output

| Employee | Monthly Sales | Reduced Target | Status   |
| -------- | ------------- | -------------- | -------- |
| Aman     | 85000         | 76500          | Achieved |
| Riya     | 72000         | 59500          | Achieved |
| Simran   | 98000         | 80750          | Achieved |

---

# Scenario Summary Example

| Employee | Monthly Sales | Normal Target | Increased Target | Reduced Target |
| -------- | ------------- | ------------- | ---------------- | -------------- |
| Aman     | 85000         | Not Achieved  | Not Achieved     | Achieved       |
| Riya     | 72000         | Achieved      | Not Achieved     | Achieved       |
| Kabir    | 65000         | Not Achieved  | Not Achieved     | Achieved       |
| Simran   | 98000         | Achieved      | Not Achieved     | Achieved       |

---

# Formatting Solution

## Apply These Features

### Home Tab

* Bold headers
* Center alignment
* Currency format for sales columns
* Borders and table colors

### Conditional Formatting

* Green fill → “Achieved”
* Red fill → “Not Achieved”

### Insert Tab

* Insert column chart for Monthly Sales

### Page Layout

* Landscape Orientation
* Add page title:

```text id="nhcqcu"
Sales Performance Dashboard
```

---

# Final Learning Outcomes

Students will learn:

* Multi-level custom sorting
* Creating custom sort lists
* Scenario Manager usage
* What-if analysis
* Formula-based reporting
* Business performance analysis
* Professional dashboard formatting

