# 📊 Monthly Budget Tracker in Excel

Follow this step-by-step guide to create a simple and functional **Monthly Budget Tracker** using Microsoft Excel.

---

## ✅ Step 1: Set Up the Sheet

1. Open Excel and create a new blank workbook.
2. In cell `A1`, type: **Monthly Budget Tracker**
3. Select `A1:D1`, then:
   - Click **Merge & Center**
   - Set the font size to **14**
   - Make the text **bold**
4. In cells `A2:D2`, type the following headers:
   - `A2`: **Date**
   - `B2`: **Description**
   - `C2`: **Category**
   - `D2`: **Amount**
5. Highlight the header row (`A2:D2`) and:
   - Click **Bold**
   - Add a **Fill Color** (light blue)
   - Apply **borders**

---

## ✅ Step 2: Enter Sample Data

Use the following sample data:

| Date       | Description | Category | Amount |
|------------|-------------|----------|--------|
| 01-04-2025 | Groceries   | Food     | 150    |
| 03-04-2025 | Rent        | Housing  | 1200   |
| 05-04-2025 | Utilities   | Bills    | 200    |
| 07-04-2025 | Dining Out  | Food     | 75     |

1. Enter the data into the sheet starting from cell `A3`.
2. Add new columns: **Discount applicable** and **Discounted value**
3. Apply a 10% discount for items with an amount greater than 100:
   - Use a formula to calculate the discounted value.

---

## ✅ Step 3: Insert a Table

1. Select your data and insert a table.
2. Ensure **"My table has headers"** is checked.
3. Rename the table to `BudgetTable`.

---

## ✅ Step 4: Add a Pie Chart

1. Insert a **2D Pie Chart** using the **Category** and **Amount** columns.
2. Resize and place the chart beside your table.
3. Add a chart title: **"Spending Distribution"**

---

## ✅ Step 5: Page Layout Settings

1. Go to the **Page Layout** tab and:
   - Set **Orientation** to **Landscape**
   - Choose **Narrow Margins**
   - Set **Print Area** (select the table and chart)
   - Add a **Header**: "Monthly Budget Tracker"

---

## ✅ Step 6: Add Formulas

1. Calculate the average expense:
   - Use `=AVERAGE(D3:D6)` in an empty cell, e.g., `D8`
2. Add a new column beside **Amount** and use a formula to show:
   - `"Over Budget"` if `Amount > 200`, otherwise `"OK"`

---

## ✅ Step 7: Use Data Validation

1. In the **Category** column:
   - Apply **Data Validation** as a drop-down list
   - Enter allowed values: `Food,Housing,Bills,Entertainment,Transport`

---

## ✅ Step 8: Protect and Review

1. Protect the sheet but **allow editing** only in necessary cells.
2. Add a **comment** to cell `D3`:  
   _“Enter expense amount here”_
3. Run a **Spelling Check**

---

## ✅ Step 9: Final Touches

1. **Freeze Top Row** to keep headers visible while scrolling.
2. Set **Zoom** level to **120%**
3. Uncheck **Gridlines** for a cleaner look.

---

📁 You now have a clean, organized, and functional **Monthly Budget Tracker** in Excel. Great for keeping track of your personal finances!
