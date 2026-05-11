Alright, let’s push it even further with a **real-world, expert-level Advanced Filter task** 👇

---

## 📊 **Excel Expert Task: Dynamic Advanced Filter with Duplicate Detection & Conditional Extraction**

### 🎯 **Objective**

Use **Advanced Filter** in Microsoft Excel to:

* Extract **duplicate records**
* Apply **multiple conditional logic**
* Use **formula-based dynamic filtering**

---

## 🧾 **Step 1: Create Dataset**

| Order ID | Customer | City    | Product | Amount | Status    |
| -------- | -------- | ------- | ------- | ------ | --------- |
| 101      | Aman     | Delhi   | Laptop  | 55000  | Delivered |
| 102      | Neha     | Mumbai  | Mobile  | 20000  | Pending   |
| 103      | Raj      | Delhi   | Tablet  | 30000  | Delivered |
| 104      | Simran   | Chennai | Laptop  | 65000  | Cancelled |
| 105      | Aman     | Delhi   | Laptop  | 55000  | Delivered |
| 106      | Karan    | Mumbai  | Mobile  | 22000  | Delivered |
| 107      | Ravi     | Delhi   | Laptop  | 70000  | Pending   |
| 108      | Neha     | Mumbai  | Mobile  | 20000  | Pending   |

---

## 🧩 **Step 2: Task Requirements**

### 🔹 **Task A: Extract Duplicate Orders**

👉 Find records where:

* Same **Customer + Product + Amount** appears more than once

---

### 🧠 **Criteria Setup (Formula-Based)**

Create criteria like this:

| Formula                                             |
| --------------------------------------------------- |
| =COUNTIFS($B$2:$B$9,B2,$D$2:$D$9,D2,$E$2:$E$9,E2)>1 |

---

## ⚙️ Apply Advanced Filter

* List Range → Full dataset
* Criteria Range → Formula cell
* Copy to another location

---

## ✅ **Expected Output**

👉 Duplicate entries (Aman Laptop 55000, Neha Mobile 20000)

---

## 🔥 **Task B: High-Value Delivered Orders (Complex AND Condition)**

### 🎯 Condition:

* Status = Delivered
* Amount > 50000
* City = Delhi

### Criteria Table:

| City  | Status    | Amount |
| ----- | --------- | ------ |
| Delhi | Delivered | >50000 |

---

## 🔥 **Task C: Mixed OR + Formula Logic**

### 🎯 Condition:

* Orders from **Mumbai** with Amount > 20000
  **OR**
* Orders where Product = Laptop AND Status ≠ Cancelled

---

### Criteria Setup:

| City   | Amount | Product | Status      |
| ------ | ------ | ------- | ----------- |
| Mumbai | >20000 |         |             |
|        |        | Laptop  | <>Cancelled |

---

## 🚀 **Bonus Challenge (Dynamic Condition)**

👉 Extract records where:

* Amount is **greater than average of all orders**
* Status is **not Pending**

### Formula Criteria:

| Formula                                   |
| ----------------------------------------- |
| =AND(E2>AVERAGE($E$2:$E$9),F2<>"Pending") |

---

## 💡 **Learning Outcome**

* Handle **real-world datasets**
* Identify **duplicates using Advanced Filter**
* Combine **COUNTIFS + Advanced Filter**
* Apply **complex OR + AND logic**
* Use **dynamic formulas inside filter criteria**

---

If you want next level, I can create:

* 🔹 **Dashboard + Advanced Filter combined task**
* 🔹 **Exam paper (beginner → expert)**
* 🔹 **LinkedIn carousel post for this task series**

Just tell me 👍

# 📊 Sample Output Tables — Advanced Filter Tasks in Microsoft Excel

---

# ✅ Task A — Duplicate Orders Output

### 🎯 Condition

Same **Customer + Product + Amount** appears more than once.

### ✅ Sample Output

| Order ID | Customer | City   | Product | Amount | Status    |
| -------- | -------- | ------ | ------- | ------ | --------- |
| 101      | Aman     | Delhi  | Laptop  | 55000  | Delivered |
| 105      | Aman     | Delhi  | Laptop  | 55000  | Delivered |
| 102      | Neha     | Mumbai | Mobile  | 20000  | Pending   |
| 108      | Neha     | Mumbai | Mobile  | 20000  | Pending   |

---

# ✅ Task B — High-Value Delivered Orders Output

### 🎯 Condition

* City = Delhi
* Status = Delivered
* Amount > 50000

### ✅ Sample Output

| Order ID | Customer | City  | Product | Amount | Status    |
| -------- | -------- | ----- | ------- | ------ | --------- |
| 101      | Aman     | Delhi | Laptop  | 55000  | Delivered |
|          |          |       |         |        |           |

Only one record satisfies all conditions.

---

# ✅ Task C — Mixed OR + AND Logic Output

### 🎯 Condition

* Mumbai orders with Amount > 20000
  **OR**
* Product = Laptop AND Status ≠ Cancelled

### ✅ Sample Output

| Order ID | Customer | City   | Product | Amount | Status    |
| -------- | -------- | ------ | ------- | ------ | --------- |
| 101      | Aman     | Delhi  | Laptop  | 55000  | Delivered |
| 105      | Aman     | Delhi  | Laptop  | 55000  | Delivered |
| 106      | Karan    | Mumbai | Mobile  | 22000  | Delivered |
| 107      | Ravi     | Delhi  | Laptop  | 70000  | Pending   |

---

# ✅ Bonus Challenge Output

### 🎯 Condition

* Amount > Average Amount
* Status ≠ Pending

### 🧠 Average Amount Calculation

Average = **44,000**

### ✅ Sample Output

| Order ID | Customer | City    | Product | Amount | Status    |
| -------- | -------- | ------- | ------- | ------ | --------- |
| 101      | Aman     | Delhi   | Laptop  | 55000  | Delivered |
| 104      | Simran   | Chennai | Laptop  | 65000  | Cancelled |
| 105      | Aman     | Delhi   | Laptop  | 55000  | Delivered |

---

# 💡 Practice Extension

Try changing:

* `>50000` to `>=50000`
* `<>Cancelled` to `<>Pending`
* Add one more duplicate record and test again

This helps understand how Advanced Filter reacts to changing criteria.

