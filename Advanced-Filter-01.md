Here’s a **practical Excel task using Advanced Filter** that you can give to students or practice yourself:

---

## 📊 **Excel Task: Advanced Filter Practice**

### 🎯 **Objective**

Use the **Advanced Filter** feature in Microsoft Excel to extract specific data based on multiple conditions.

---

## 🧾 **Step 1: Create the Dataset**

Enter the following data in Excel:

| ID | Name   | Department | Salary | Experience |
| -- | ------ | ---------- | ------ | ---------- |
| 1  | Aman   | IT         | 45000  | 2          |
| 2  | Neha   | HR         | 30000  | 1          |
| 3  | Raj    | IT         | 60000  | 5          |
| 4  | Simran | Finance    | 50000  | 4          |
| 5  | Karan  | IT         | 70000  | 6          |
| 6  | Pooja  | HR         | 35000  | 2          |
| 7  | Ravi   | Finance    | 40000  | 3          |

---

## 🧩 **Step 2: Set Criteria Range**

Somewhere else in the sheet (e.g., starting from G1), create criteria:

| Department | Salary |
| ---------- | ------ |
| IT         | >50000 |

👉 This means:

* Department must be **IT**
* Salary must be **greater than 50,000**

---

## ⚙️ **Step 3: Apply Advanced Filter**

1. Select the entire dataset (including headers)
2. Go to **Data Tab → Advanced Filter**
3. Choose:

   * **Copy to another location**
4. Set:

   * **List Range** → Your dataset
   * **Criteria Range** → G1:H2
   * **Copy To** → Select a blank area (e.g., J1)
5. Click **OK**

---

## ✅ **Expected Output**

| ID | Name  | Department | Salary | Experience |
| -- | ----- | ---------- | ------ | ---------- |
| 3  | Raj   | IT         | 60000  | 5          |
| 5  | Karan | IT         | 70000  | 6          |

---

## 🔥 **Advanced Challenge**

Try these variations:

### 1. **OR Condition**

| Department |
| ---------- |
| IT         |
| HR         |

👉 Shows employees from IT **OR** HR

---

### 2. **Multiple Conditions**

| Department | Experience |
| ---------- | ---------- |
| Finance    | >3         |

---

### 3. **Unique Records**

* Use Advanced Filter → Check **Unique records only**
* Extract only unique departments

---

## 💡 **Learning Outcome**

* Understand difference between **Filter vs Advanced Filter**
* Apply **AND / OR logic without formulas**
* Extract data to another location
* Work with structured criteria ranges

---

If you want, I can convert this into a **LinkedIn post**, **worksheet PDF**, or **student assignment sheet** 👍
