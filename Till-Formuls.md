# **Mega Excel Task – Sales Performance Dashboard**

##  Objective

Create a **professional and interactive sales dashboard** using full Excel features.

---

#  **Step 1: Create Data Sheet (Sheet1 – “SalesData”)**

| Salesperson | Region | Product | Units Sold | Price | Target | Total Sales | Achieved Target |
| ----------- | ------ | ------- | ---------- | ----- | ------ | ----------- | --------------- |
| Aman        | North  | Laptop  | 20         | 40000 | 700000 |             |                 |
| Simran      | South  | Mobile  | 35         | 20000 | 600000 |             |                 |
| Rahul       | East   | Tablet  | 25         | 15000 | 500000 |             |                 |
| Priya       | West   | Laptop  | 18         | 40000 | 650000 |             |                 |
| Karan       | North  | Mobile  | 40         | 20000 | 700000 |             |                 |
| Neha        | South  | Tablet  | 22         | 15000 | 550000 |             |                 |

---

#  **Step 2: Apply Formulas (Formula Tab)**

##  Total Sales

```excel id="f1"
=Units Sold * Price
```

(example: `=D2*E2`)

---

##  Achieved Target (Using AND / OR)

👉 Condition:

* If Total Sales ≥ Target → "Achieved"
* OR if Units Sold ≥ 30 → "Good"

```excel id="f2"
=IF(OR(G2>=F2,D2>=30),"Achieved","Not Achieved")
```

---

##  Bonus Formula (Optional)

Use **AVERAGE** to calculate average sales at bottom.

---

#  **Step 3: Home Tab Formatting**

* Convert data into **Table (Ctrl + T)**
* Apply:

  * Bold headers
  * Center alignment
  * Borders
* Conditional Formatting:

  * "Achieved" → Green
  * "Not Achieved" → Red
  * Data Bars on Total Sales
* Use **Format Painter**

---

#  **Step 4: Insert Tab (Use Multiple Tools)**

##  Pivot Table (Sheet2 – “Pivot”)

### Pivot 1: Region-wise Sales

* Rows → Region
* Values → Sum of Total Sales

---

### Pivot 2: Product-wise Units Sold

* Rows → Product
* Values → Sum of Units Sold

---

##  Insert Slicer

* Add slicer for:

  * Region
  * Product
* Connect slicers to pivot tables

---

##  Charts (Insert Tab)

Create:

### 1️ Column Chart

* Region vs Total Sales

### 2️ Pie Chart

* Product contribution

### 3️ Bar Chart

* Salesperson vs Sales

---

##  Other Insert Features

Use:

* **Shapes** → Create dashboard sections
* **Icons** → Add visual indicators
* **Text Box** → Title
* **Header/Footer**

---

#  **Step 5: Dashboard Sheet (Sheet3 – “Dashboard”)**

Design a clean dashboard:

### Include:

✔ Charts
✔ Slicers
✔ Title: **Sales Performance Dashboard**
✔ KPI Section:

* Total Sales
* Average Sales

---

# 🖨️ **Step 6: Page Layout Tab**

* Orientation → Landscape
* Margins → Narrow
* Add:

  * Header → Company Name
  * Footer → Page Number
* Set Print Area (Dashboard only)

---

#  **Final Output Checklist**

✔ Formulas (AND, OR, IF, SUM/AVERAGE)
✔ Conditional Formatting
✔ Pivot Tables
✔ Slicers
✔ 3+ Charts
✔ Dashboard Design
✔ Print-ready formatting
