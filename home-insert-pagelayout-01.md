## Excel Practice Task – Student Attendance & Summary Sheet

### Part 1 – Create the main table (Home tab)

1. Open a new Excel sheet.

2. In **Row 1**, enter these headings:

   ```
   A1 – Roll No  
   B1 – Student Name  
   C1 – Class  
   D1 – Total Classes  
   E1 – Classes Attended  
   F1 – Attendance %  
   ```

3. Enter data for **8 students**.

   * Roll No: 101 to 108
   * Total Classes: 50 for all
   * Classes Attended: Any numbers between 30 and 50

4. Use **Home tab** to:

   * Make the headings **Bold**
   * Change the heading **background color**
   * Center-align Roll No and Class
   * Add **All Borders** to the table

---

### Part 2 – Use Insert Tab

5. Insert a **Column Chart** showing:

   * Student Name (X-axis)
   * Classes Attended (Y-axis)

6. Add a **Chart Title**:

   * *“Student Attendance Chart”*

7. Resize and move the chart below your table.

---

### Part 3 – Use Page Layout Tab

8. Go to **Page Layout** and:

   * Set **Orientation** to **Landscape**
   * Set **Margins** to **Narrow**
   * Change **Page Size** to **A4**
   * Add a **Header**:

     ```
     Student Attendance Report
     ```

9. Add a **Footer** with your name.

---

### Bonus Task (Optional)

10. Change the font of the entire sheet to **Calibri or Arial**.
11. Apply **Conditional Formatting** (optional) for:

* Attendance less than 75% → Red

## SOLUTION – Student Attendance & Summary Sheet

### Part 1 – Main Table (Home Tab)

**Step 1: Enter headings in Row 1**

| Cell | Text             |
| ---- | ---------------- |
| A1   | Roll No          |
| B1   | Student Name     |
| C1   | Class            |
| D1   | Total Classes    |
| E1   | Classes Attended |
| F1   | Attendance %     |

**Step 2: Enter sample data (Row 2 – Row 9)**

| Roll No | Student Name | Class | Total Classes | Classes Attended |
| ------- | ------------ | ----- | ------------- | ---------------- |
| 101     | Rahul        | 10th  | 50            | 45               |
| 102     | Aanya        | 10th  | 50            | 39               |
| 103     | Karan        | 10th  | 50            | 48               |
| 104     | Simran       | 10th  | 50            | 41               |
| 105     | Rohan        | 10th  | 50            | 35               |
| 106     | Pooja        | 10th  | 50            | 47               |
| 107     | Arjun        | 10th  | 50            | 44               |
| 108     | Neha         | 10th  | 50            | 38               |

**Step 3: Calculate Attendance %**

In **F2** type this formula:

```
=E2/D2*100
```

Press **Enter**, then drag it down to **F9**.

Format column **F** as **Percentage (%)** from **Home → Number → %**

---

### Formatting using Home Tab

1. Select **A1:F1**

   * Click **Bold**
   * Change **Fill Color** (any light color)
   * Set **Font Color** = White (optional)
   * Click **Center Alignment**

2. Select **A1:F9**

   * Click **All Borders**

3. Center-align columns:

   * **A (Roll No)**
   * **C (Class)**

---

### Part 2 – Chart (Insert Tab)

**Step 4: Select data for chart**
Select only:

```
B1:B9  (Student Name)
E1:E9  (Classes Attended)
```

**Step 5: Insert Chart**

Go to:

```
Insert → Column Chart → Clustered Column
```

**Step 6: Add Chart Title**

Click chart title and type:

```
Student Attendance Chart
```

Move the chart below the table.

---

### Part 3 – Page Setup (Page Layout Tab)

**Step 7: Apply page settings**

Go to **Page Layout** and set:

| Option      | Setting   |
| ----------- | --------- |
| Orientation | Landscape |
| Size        | A4        |
| Margins     | Narrow    |

**Step 8: Add Header**

1. Page Layout → Page Setup launcher (small arrow)
2. Go to **Header/Footer tab**
3. Click **Custom Header**
4. In Center section type:

```
Student Attendance Report
```

**Step 9: Add Footer**

In **Custom Footer** type your name, for example:

```
Prepared by: Navjot Kaur
```

---

### Bonus – Conditional Formatting (Optional)

1. Select **F2:F9**
2. Home → Conditional Formatting → Less than
3. Type `75`
4. Select **Red Fill**

Students below 75% will be marked in **Red**.
