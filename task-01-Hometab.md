## **Advanced Task: Sales Report Formatting & Analysis (Using Home Tab)**

###  **Objective:**

Create a professional sales report and apply advanced formatting, calculations, and highlighting using **Home Tab tools**.

---

##  **Step 1: Enter Data**

| Salesperson | Region | Jan   | Feb   | Mar   | Total | Average |
| ----------- | ------ | ----- | ----- | ----- | ----- | ------- |
| Aman        | North  | 12000 | 15000 | 14000 |       |         |
| Simran      | South  | 18000 | 17000 | 16000 |       |         |
| Rahul       | East   | 10000 | 12000 | 11000 |       |         |
| Neha        | West   | 20000 | 22000 | 21000 |       |         |
| Karan       | North  | 9000  | 9500  | 10000 |       |         |

---

## **Step 2: Calculations (Editing Group)**

* Use **AutoSum** to calculate:

  * **Total Sales**
  * **Average Sales**

---

## **Step 3: Advanced Formatting (Home Tab)**

###  **Font & Styling**

* Make headings **Bold + Increase Size (16)**
* Apply different font style
* Change text color for headings

---

###  **Fill, Borders & Styles**

* Apply **table borders (All Borders + Thick Outside Border)**
* Use **Cell Styles** (e.g., Heading 1, Total style)
* Apply alternating row colors manually

---

###  **Alignment**

* Center align headings
* Right align numbers
* Use **Merge & Center** to create a title:
  👉 *“Quarterly Sales Report”*

---

###  **Number Formatting**

* Format values as **Currency (₹)**
* Remove decimal places

---

## **Step 4: Conditional Formatting (Important)**

Apply the following:

* Highlight sales **greater than 20,000** → Green
* Highlight sales **less than 10,000** → Red
* Apply **Data Bars** on Total column
* Use **Top 1 or Top 2 rule** to highlight best performer

---

##  **Step 5: Advanced Editing Tools**

* Use **Sort & Filter**:

  * Sort by **Total Sales (Highest to Lowest)**
* Use **Find & Replace**:

  * Replace a region name (e.g., North → North Zone)

---

##  **Step 6: Format Painter**

* Copy formatting from one row and apply to another using **Format Painter**

---

## **Expected Output:**

* Professional-looking report
* Proper currency formatting
* Highlighted top and low performers
* Clean alignment and structure

---

##  **Bonus Challenge:**

* Highlight entire row of top performer using Conditional Formatting
* Add a **“Performance” column** and mark:

  * Excellent (>20000)
  * Good (15000–20000)
  * Average (<15000)

# ✅ **Solution: Sales Report (Step-by-Step)**

---

##  **Final Data with Calculations**

| Salesperson | Region | Jan   | Feb   | Mar   | Total | Average |
| ----------- | ------ | ----- | ----- | ----- | ----- | ------- |
| Aman        | North  | 12000 | 15000 | 14000 | 41000 | 13667   |
| Simran      | South  | 18000 | 17000 | 16000 | 51000 | 17000   |
| Rahul       | East   | 10000 | 12000 | 11000 | 33000 | 11000   |
| Neha        | West   | 20000 | 22000 | 21000 | 63000 | 21000   |
| Karan       | North  | 9000  | 9500  | 10000 | 28500 | 9500    |

---

##  **Step 1: Formulas Used**

###  **Total Column (F2):**

```
=SUM(C2:E2)
```

Drag down for all rows.

---

###  **Average Column (G2):**

```
=AVERAGE(C2:E2)
```

Drag down.

---

##  **Step 2: Title (Home Tab → Alignment)**

* Select A1:G1
* Click **Merge & Center**
* Type: **Quarterly Sales Report**

---

## **Step 3: Formatting (Home Tab)**

###  **Font**

* Select heading row → **Bold**
* Font Size → **16**
* Font Color → Blue (or any)

---

###  **Fill & Borders**

* Header Row → Apply **Fill Color**
* Select full table → **All Borders**
* Apply **Thick Outside Border**

---

###  **Alignment**

* Headings → **Center Align**
* Numbers → **Right Align**

---

###  **Currency Format**

* Select sales data (C2:G6)
* Click **₹ Currency Format**
* Reduce decimal places to 0

---

##  **Step 4: Conditional Formatting**

###  **High Sales (>20000)**

* Select data (C2:E6)
* Home → Conditional Formatting → Highlight Cell Rules → Greater Than → 20000 → Green

---

###  **Low Sales (<10000)**

* Conditional Formatting → Less Than → 10000 → Red

---

###  **Data Bars (Total Column)**

* Select F2:F6
* Conditional Formatting → Data Bars → Choose style

---

###  **Top Performer**

* Select Total column
* Conditional Formatting → Top/Bottom Rules → Top 1 → Highlight

👉 Result: **Neha is Top Performer (63000)**

---

##  **Step 5: Sorting**

* Select table
* Home → Sort & Filter → Sort Largest to Smallest (by Total)

---

##  **Step 6: Find & Replace**

* Press **Ctrl + H**
* Find: `North`
* Replace with: `North Zone`

---

##  **Step 7: Format Painter**

* Select a formatted row
* Click **Format Painter**
* Apply to another row

---

##  **Bonus Solution: Performance Column**

###  Add Column H → “Performance”

### Formula (H2):

```
=IF(F2>20000,"Excellent",IF(F2>=15000,"Good","Average"))
```

### Final Output Example:

| Name   | Total | Performance |
| ------ | ----- | ----------- |
| Neha   | 63000 | Excellent   |
| Simran | 51000 | Excellent   |
| Aman   | 41000 | Excellent   |
| Rahul  | 33000 | Good        |
| Karan  | 28500 | Average     |

---

##  **Final Result Includes:**

✔ Calculations (SUM, AVERAGE)
✔ Professional formatting
✔ Conditional highlighting
✔ Sorted data
✔ Performance analysis
