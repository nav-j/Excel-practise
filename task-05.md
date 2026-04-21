
# 📈 Excel Task: Currency Conversion Table (With Solution)

## 🔧 Task Description

This Excel task helps you understand how to use **absolute** and **relative** cell references by building a simple currency conversion table.

You are given a list of product prices in **Indian Rupees (INR)**. Your goal is to convert each price to **US Dollars (USD)** using a fixed exchange rate.

---

## 📁 Given Data

| Product Name | Price (INR) | USD Rate | Price (USD) |
|--------------|-------------|----------|-------------|
| Laptop       | 60000       |          |             |
| Headphones   | 2500        |          |             |
| Keyboard     | 1500        |          |             |
| Smartphone   | 30000       |          |             |

✅ **USD Rate** is `0.012` and should be entered in **cell C1**.

---

## ✅ Solution Steps

1. **Enter** the exchange rate `0.012` in **cell C1**.
2. In **cell D2**, write the formula:

   ```excel
   =B2*$C$1
* `B2` (Price in INR) is a **relative reference**.
* `$C$1` (USD Rate) is an **absolute reference**.

3. **Drag down** the formula from D2 to D5 to apply it to all products.

---

## ✅ Final Output Example

| Product Name | Price (INR) | USD Rate | Price (USD) |
| ------------ | ----------- | -------- | ----------- |
| Laptop       | 60000       | 0.012    | 720         |
| Headphones   | 2500        | 0.012    | 30          |
| Keyboard     | 1500        | 0.012    | 18          |
| Smartphone   | 30000       | 0.012    | 360         |

---

## 🧠 Learning Recap

* ✅ **Relative Reference** (e.g., `B2`) adjusts automatically when copied.
* ✅ **Absolute Reference** (e.g., `$C$1`) remains fixed regardless of where the formula is applied.
* ✅ Combining both allows dynamic yet consistent calculations.

---

> 💬 Try changing the USD rate in `C1` to see how all prices in USD update instantly!

```
