# Excel Practice Task – Till Formula Tab

This is a simple **Excel Task** designed for **beginners** to practice Excel tools and features.  
It covers actions from the following tabs:

- **Home**
- **Insert**
- **Page Layout**
- **Formulas**

You will work with a small dataset to build a **Monthly Sales Report** and perform formatting, visualization, layout setup, and calculations.

---

## Scenario: Monthly Sales Report

Create an Excel spreadsheet to manage and analyze monthly sales data of 5 salespersons for 3 months: **January**, **February**, and **March**.

---

## Step-by-Step Tasks by Tab

---

### HOME Tab Tasks

1. **Enter the Data:**

| Salesperson | January | February | March |
| ----------- | ------- | -------- | ----- |
| Alex        | 12000   | 13500    | 12800 |
| Brian       | 15000   | 14500    | 13900 |
| Carol       | 11200   | 12000    | 11900 |
| Diana       | 13400   | 13800    | 14000 |
| Evan        | 12500   | 12900    | 13200 |

2. **Formatting:**
   - Make the headers **bold** and apply a **background color**.
   - Use **Currency format** (₹ or $).
   - **Center-align** all values.
   - Increase **row height** and apply **borders** to the table.

3. **Conditional Formatting:**
   - Highlight all cells where sales > 13000.

---

### INSERT Tab Tasks

4. **Insert a Column Chart:**
   - Select the data range (excluding totals).
   - Insert a **Clustered Column Chart** to compare monthly sales.

5. **Add a Slicer (Excel 2013+):**
   - Convert your data to a **Table** (Ctrl + T).
   - Insert a **Slicer** for the **Salesperson** column.

6. **Insert Shapes or Icons:**
   - Add a **shape** at the top with the title:  
     `"Monthly Sales Report"`

---

###  PAGE LAYOUT Tab Tasks

7. **Set the Page:**
   - Change **Orientation** to **Landscape**.
   - Set **Margins** to **Narrow**.
   - Use **Fit to One Page** scaling for printing.

8. **Add a Background (optional):**
   - Add a background image (e.g., company logo).

9. **Set Print Area:**
   - Select only the table and the chart to print.

---

### 🟣 FORMULAS Tab Tasks

10. **Add Total Sales Column:**
   - Use this formula:
     ```excel
     =SUM(B2:D2)
     ```

11. **Add Average Sales Column:**
   - Use this formula:
     ```excel
     =AVERAGE(B2:D2)
     ```

12. **Use Formula Auditing Tools:**
   - Use **Trace Precedents** or **Evaluate Formula** on one formula cell.

13. **Name a Range:**
   - Name the **January** column as:
     ```
     January_Sales
     ```

---

## 📁 Bonus (Optional)

- Create a **dropdown** to filter months using **Data → Data Validation**.
- Use an `IF` formula to highlight “Top Performer” if Total Sales > 40000:
  ```excel
  =IF(E2>40000,"Top Performer","")
