# Excel Practice Task – Product Price List (Solution)

## Scenario: Supermarket Product List

You are creating a printable price list for a small supermarket.

---

## HOME Tab – Data Entry & Formatting

### 1. Enter the Data

Create the following table starting from cell A1:

| Product Name | Category  | Price | Stock Status |
| ------------ | --------- | ----- | ------------ |
| Rice 5kg     | Grocery   | 320   | In Stock     |
| Milk 1L      | Dairy     | 55    | In Stock     |
| Bread        | Bakery    | 40    | Out of Stock |
| Chips        | Snacks    | 20    | In Stock     |
| Orange Juice | Beverages | 90    | In Stock     |
| Cheese       | Dairy     | 180   | Out of Stock |
| Biscuits     | Snacks    | 35    | In Stock     |
| Tea Powder   | Grocery   | 250   | In Stock     |

---

### 2. Formatting

* Select the header row (A1:D1):

  * Click **Bold**
  * Apply **Light Blue Fill Color**
* Select Price column:

  * Go to **Home → Number → Currency**
* Center align:

  * Price
  * Stock Status
* Select entire table:

  * Apply **All Borders**
* Adjust column width and row height automatically.

---

### 3. Conditional Formatting

Highlight "Out of Stock" in red:

1. Select column D (Stock Status)
2. Go to **Home → Conditional Formatting → Highlight Cell Rules → Text that Contains**
3. Type: `Out of Stock`
4. Choose **Red fill with white text**

---

## INSERT Tab – Visual Enhancements

### 4. Convert to Table

* Select A1:D9
* Press **Ctrl + T**
* Check **My table has headers** → OK

---

### 5. Insert Column Chart

* Select:

  * Product Name and Price columns
* Go to:

  * **Insert → Column Chart → Clustered Column**
* Chart title:
  **Product Price Comparison**

---

### 6. Insert Shape (Title)

* Insert → Shapes → Rectangle
* Place it above the table
* Type:

  > Supermarket Product Price List
* Increase font size and apply a light fill color.

---

### 7. Add Icon / SmartArt

* Go to **Insert → Icons or SmartArt**
* Add a shopping cart or store-related icon near the title.

---

## PAGE LAYOUT Tab – Print Setup

### 8. Page Setup

* Orientation → **Landscape**
* Margins → **Narrow**

---

### 9. Apply Theme

* Page Layout → Themes
* Choose a simple professional theme (e.g., **Facet** or **Ion**)

---

### 10. Set Print Area

* Select table + chart + title
* Page Layout → Print Area → **Set Print Area**

---

### 11. Fit to One Page

* Page Layout → Scale to Fit:

  * Width: 1 page
  * Height: 1 page

---

## Final Result Should Include

✅ Neatly formatted table
✅ Highlighted out-of-stock items
✅ Column chart showing price comparison
✅ Professional title and visuals
✅ Ready-to-print layout on one page

---

## ⭐ Bonus Solution

* Alternate Row Colors:

  * Click table → Table Design → Choose a style with banded rows
* Footer:

  * Insert → Header & Footer → Footer:

  ```
  Created by: Your Name | Date: DD/MM/YYYY
  ```

---
