# ✅ Excel Practice Task – Employee Attendance Tracker (Solution)

This Excel task demonstrates the use of key Excel features from the **Home**, **Insert**, **Page Layout**, and **Formulas** tabs using a real-world scenario: tracking employee attendance.

---

## 📊 Scenario: Employee Attendance Tracker

Create a worksheet to track the attendance of 6 employees over a 10-day working period.

---

## ✅ Step-by-Step Tasks by Tab (With Solutions)

---

### 🔵 HOME Tab – Data Entry & Formatting

1. **Enter the Data:**

| Employee Name | 01-Jul | 02-Jul | 03-Jul | 04-Jul | 05-Jul | 06-Jul | 07-Jul | 08-Jul | 09-Jul | 10-Jul |
|---------------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|
| Aman          | P      | P      | P      | A      | P      | P      | P      | P      | P      | P      |
| Bhavna        | P      | A      | P      | P      | L      | P      | P      | P      | P      | P      |
| Chetan        | P      | P      | P      | P      | P      | P      | P      | A      | A      | P      |
| Divya         | L      | L      | P      | P      | P      | P      | P      | P      | P      | A      |
| Esha          | A      | P      | P      | P      | P      | L      | P      | P      | P      | P      |
| Faisal        | P      | P      | P      | P      | P      | P      | P      | P      | A      | A      |

2. **Formatting:**
   - Make header row **bold** and fill with a light color.
   - Use **Center alignment** for all cells.
   - Add **borders** around all data.
   - Increase **row height** for better visibility.

3. **Conditional Formatting:**
   - Highlight cells:
     - "A" with **Red Fill**
     - "P" with **Green Fill**
     - "L" with **Yellow Fill**
   - Go to **Home → Conditional Formatting → New Rule → Format only cells that contain**.

---

### 🟢 INSERT Tab – Table & Chart

4. **Insert Table:**
   - Select data (A1:K7) → Press **Ctrl + T** to convert into a table.

5. **Insert Chart:**
   - Add two new columns: **Total Present** and **Total Absent** (see formula below).
   - Select those columns and insert a **Clustered Column Chart**.

6. **Add Shape/Icon:**
   - Go to **Insert → Shapes → Rectangle**, and add a title like “Employee Attendance Tracker”.

---

### 🟡 PAGE LAYOUT Tab – Setup for Printing

7. **Change Orientation:**
   - Go to **Page Layout → Orientation → Landscape**

8. **Margins:**
   - Set to **Wide** under **Margins**

9. **Fit to Page:**
   - Page Layout → Scale to Fit → Width: 1 page, Height: 1 page

10. **Set Print Area:**
    - Select the attendance table and chart → Page Layout → **Print Area → Set Print Area**

---

### 🟣 FORMULAS Tab – Calculations

11. **Add Total Present Column:**
    In column `L`, use the formula:
    ```excel
    =COUNTIF(B2:K2, "P")
    ```

12. **Add Total Absent Column:**
    In column `M`, use the formula:
    ```excel
    =COUNTIF(B2:K2, "A")
    ```

13. **Add Attendance % Column:**
    In column `N`, use:
    ```excel
    =L2/COUNTA(B2:K2)
    ```
    Format it as a **percentage**.

14. **Name a Range:**
    - Select B1:K1 → go to **Formulas → Define Name** → name it `Working_Days`.

15. **Formula Auditing:**
    - Click any formula → Go to **Formulas → Trace Precedents** to view linked cells.

---

## 🎯 Bonus Solutions

1. **Conditional Format Attendance %:**
   - If attendance % < 80%, highlight with red text.
   - Use: **Home → Conditional Formatting → New Rule → Use formula**  
     Formula:
     ```excel
     =N2<0.8
     ```

2. **Dropdown Search (Optional):**
   - On another sheet, create a dropdown using **Data → Data Validation**.
   - Use `=INDIRECT` and `FILTER` functions to show attendance per employee (advanced).

---

> ✅ **Tip:** Save your work regularly and practice repeating the steps without looking at this solution.
