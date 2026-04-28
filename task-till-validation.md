# Excel Sales Tracker - README

##  Objective

This project aims to guide users in creating a **basic Excel sheet for Sales Tracking** using essential features from the following Excel tabs:

- **Home Tab** (formatting, cell styles)
- **Insert Tab** (tables, charts)
- **Data Tab** (sorting, filtering)

---

##  Sample Excel Sheet Layout: Sales Tracker

| Date       | Product   | Category    | Units Sold | Price per Unit | Total Sales   |
|------------|-----------|-------------|-------------|----------------|----------------|
| 2025-04-01 | Product A | Electronics | 10          | $100           |                |
| 2025-04-02 | Product B | Furniture   | 5           | $200           |                |
| ...        | ...       | ...         | ...         | ...            | ...            |

Add more products.
---

## Instructions Using Excel Tabs

###  HOME Tab:

1. **Font & Alignment:**
   - Bold the headers.
   - Center-align all columns.

2. **Cell Formatting:**
   - Format **"Price per Unit"** and **"Total Sales"** as **Currency**.

3. **Cell Styles:**
   - Use **“Heading 1”** for the main title.
   - Apply **fill color** or **borders** to differentiate header row.

---

###  INSERT Tab:

1. **Table:**
   - Convert the data range into an **Excel Table** for better management and formatting.

2. **Chart:**
   - Insert a **Line** or **Column Chart** to display **sales trends** over time.

---

###  DATA Tab:

1. **Sort & Filter:**
   - Use **Advanced Filter** to display only rows from the **Furniture** category.
   - Use **Sort** to organize products by **Units Sold** or **Total Sales**.

2. **Data Validation:**
   - Add a **drop-down list** in the **Category** column using **Data Validation** to ensure consistent category entries (e.g., Electronics, Furniture, etc.).


# Excel Sales Tracker – Solution

## Step 1: Enter the Data

Create the following table in Excel:

| Date       | Product   | Category    | Units Sold | Price per Unit | Total Sales |
| ---------- | --------- | ----------- | ---------- | -------------- | ----------- |
| 2025-04-01 | Product A | Electronics | 10         | $100           | $1000       |
| 2025-04-02 | Product B | Furniture   | 5          | $200           | $1000       |
| 2025-04-03 | Product C | Clothing    | 12         | $50            | $600        |
| 2025-04-04 | Product D | Electronics | 8          | $150           | $1200       |
| 2025-04-05 | Product E | Furniture   | 6          | $300           | $1800       |
| 2025-04-06 | Product F | Grocery     | 20         | $20            | $400        |
| 2025-04-07 | Product G | Clothing    | 15         | $40            | $600        |
| 2025-04-08 | Product H | Electronics | 9          | $250           | $2250       |

---

# Step 2: Formula for Total Sales

In cell **F2**, enter the formula:

```excel id="0xzpq"
=D2*E2
```

Drag the formula down for all rows.

---

# HOME Tab Solution

## 1. Font & Alignment

* Select the header row.
* Click **Bold**.
* Apply **Center Alignment** to all columns.

## 2. Currency Formatting

* Select columns **E** and **F**.
* Go to:
  **Home → Number Group → Currency**

## 3. Cell Styles

* Add title: **Sales Tracker Report**
* Apply:
  **Home → Cell Styles → Heading 1**
* Add:

  * Blue fill color to headers
  * White bold font
  * All Borders

---

# INSERT Tab Solution

## 1. Convert Data into Table

* Select the entire dataset.
* Go to:
  **Insert → Table**
* Check:
  ✅ “My table has headers”

### Result:

Excel creates a formatted table with filters automatically enabled.

---

## 2. Insert Chart

### Create Sales Trend Chart

* Select:
  **Date** and **Total Sales** columns.
* Go to:
  **Insert → Column Chart**
  OR
  **Insert → Line Chart**

### Expected Output:

A chart showing sales growth over different dates.

---

# DATA Tab Solution

## 1. Sort Data

### Sort by Units Sold

* Select the table.
* Go to:
  **Data → Sort**
* Choose:

  * Column: **Units Sold**
  * Order: **Largest to Smallest**

---

## 2. Apply Filter

### Filter Furniture Category

* Click filter arrow in **Category** column.
* Select only:
  ✅ Furniture

### Result:

Only Furniture products will display.

---

## 3. Data Validation Drop-down

### Create Category Drop-down

1. Select Category column cells.
2. Go to:
   **Data → Data Validation**
3. Choose:

   * Allow: **List**
4. Enter Source:

```excel id="2yhj0"
Electronics,Furniture,Clothing,Grocery
```

### Result:

Users can select categories from a dropdown list.

