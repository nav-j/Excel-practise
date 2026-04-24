# Excel Task – Using AND & OR Functions

## Task 1: Employee Bonus Eligibility (AND Function)

Create the following table in Excel:

| Employee Name | Sales Amount | Attendance % | Bonus Eligible |
| ------------- | ------------ | ------------ | -------------- |
| Aman          | 85000        | 92           |                |
| Priya         | 72000        | 88           |                |
| Rohit         | 95000        | 96           |                |
| Simran        | 60000        | 91           |                |
| Karan         | 78000        | 85           |                |

### Condition:

An employee will get a bonus only if:

* Sales Amount is greater than 80000
* Attendance is greater than or equal to 90%

### Formula:

In the **Bonus Eligible** column use:

```excel
=AND(B2>80000,C2>=90)
```

Then drag the formula down.

---

# Task 2: Student Pass Status (OR Function)

Create the following table:

| Student Name | Theory Marks | Practical Marks | Pass Status |
| ------------ | ------------ | --------------- | ----------- |
| Neha         | 28           | 45              |             |
| Arjun        | 35           | 22              |             |
| Mehak        | 18           | 40              |             |
| Raj          | 30           | 30              |             |
| Tina         | 25           | 20              |             |

### Condition:

Student will pass if:

* Theory Marks are greater than or equal to 30
  OR
* Practical Marks are greater than or equal to 30

### Formula:

In the **Pass Status** column use:

```excel
=OR(B2>=30,C2>=30)
```

Then drag the formula down.

---

# Task 3: Advanced Task Using AND + OR Together

Create this table:

| Employee | Department | Experience (Years) | Performance Score | Promotion Eligible |
| -------- | ---------- | ------------------ | ----------------- | ------------------ |
| Ravi     | IT         | 6                  | 88                |                    |
| Sonia    | HR         | 3                  | 91                |                    |
| Vikas    | IT         | 7                  | 75                |                    |
| Pooja    | Sales      | 5                  | 95                |                    |
| Manpreet | IT         | 2                  | 85                |                    |

### Condition:

Employee is eligible for promotion if:

* Department is IT
  AND
* Experience is greater than or equal to 5
  AND
* Performance Score is greater than 80

### Formula:

```excel
=AND(B2="IT",C2>=5,D2>80)
```

---

# Task 4: Smart Discount System (AND + OR)

| Customer | Purchase Amount | Membership | Coupon Applied | Discount Given |
| -------- | --------------- | ---------- | -------------- | -------------- |
| Aditi    | 12000           | Yes        | No             |                |
| Mohit    | 7000            | No         | Yes            |                |
| Riya     | 15000           | Yes        | Yes            |                |
| Kabir    | 5000            | No         | No             |                |
| Jaspreet | 11000           | No         | Yes            |                |

### Condition:

Discount will be given if:

* Purchase Amount is greater than 10000
  AND
* Customer is a member
  OR
* Coupon is applied

### Formula:

```excel
=OR(AND(B2>10000,C2="Yes"),D2="Yes")
```
