Here’s a **more advanced-level Excel task using Advanced Filter**, designed to really test logic building and data handling:

---

## 📊 **Excel Advanced Task: Multi-Level Advanced Filter with Complex Criteria**

### 🎯 **Objective**

Use **Advanced Filter** in Microsoft Excel with **AND, OR, and formula-based conditions** to extract highly specific data.

---

## 🧾 **Step 1: Create the Dataset**

Enter the following table:

| ID | Name   | Department | Salary | Experience | Joining Date |
| -- | ------ | ---------- | ------ | ---------- | ------------ |
| 1  | Aman   | IT         | 45000  | 2          | 12-01-2022   |
| 2  | Neha   | HR         | 30000  | 1          | 05-03-2023   |
| 3  | Raj    | IT         | 60000  | 5          | 10-07-2020   |
| 4  | Simran | Finance    | 50000  | 4          | 22-11-2021   |
| 5  | Karan  | IT         | 70000  | 6          | 15-09-2019   |
| 6  | Pooja  | HR         | 35000  | 2          | 18-02-2022   |
| 7  | Ravi   | Finance    | 40000  | 3          | 30-06-2021   |
| 8  | Meena  | IT         | 52000  | 3          | 01-01-2024   |

---

## 🧩 **Step 2: Create Complex Criteria Range**

Create this criteria (e.g., starting from H1):

| Department | Salary | Experience | Joining Date |
| ---------- | ------ | ---------- | ------------ |
| IT         | >50000 | >3         |              |
| HR         |        |            | >01-01-2022  |

---

### 🧠 **Logic Explained**

* Row 1 → IT employees with **Salary > 50,000 AND Experience > 3**
* Row 2 → HR employees who **joined after 01-Jan-2022**
  👉 This uses **OR logic between rows**

---

## ⚙️ **Step 3: Apply Advanced Filter**

1. Select dataset (including headers)
2. Go to **Data → Advanced Filter**
3. Choose:

   * **Copy to another location**
4. Set:

   * **List Range** → Full dataset
   * **Criteria Range** → H1:K3
   * **Copy To** → Any blank area (e.g., M1)
5. Click **OK**

---

## ✅ **Expected Output**

| ID | Name  | Department | Salary | Experience | Joining Date |
| -- | ----- | ---------- | ------ | ---------- | ------------ |
| 3  | Raj   | IT         | 60000  | 5          | 10-07-2020   |
| 5  | Karan | IT         | 70000  | 6          | 15-09-2019   |
| 2  | Neha  | HR         | 30000  | 1          | 05-03-2023   |
| 6  | Pooja | HR         | 35000  | 2          | 18-02-2022   |

---

## 🔥 **Super Advanced Challenge (Formula Criteria)**

### 🎯 Task:

Filter employees whose:

* Name starts with **"R"**
* Salary is **above average salary**

---

### 🧩 Criteria Setup:

| Name | Formula                                     |
| ---- | ------------------------------------------- |
|      | =AND(LEFT(B2,1)="R", D2>AVERAGE($D$2:$D$9)) |

⚠️ Important:

* Leave header blank for formula column
* Use **relative reference (B2, D2)** based on first row

---

## 💡 **Learning Outcome**

* Master **AND + OR combination**
* Use **date filtering in Advanced Filter**
* Apply **formula-based filtering**
* Understand **dynamic criteria logic**

---

If you want, I can turn this into a **complete Excel assignment sheet**, **test paper**, or **LinkedIn Day-wise post** for your series.
