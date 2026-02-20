# Grocery-Billing-System_AbhasSrivastava_202501100700004
# 🛒 Grocery Billing System (Python)

## 📌 Problem Statement

Develop a simple Grocery Billing System using Python that:

- Accepts the prices of three grocery items from the user.
- Calculates the total bill amount.
- Applies a 10% discount if the total exceeds $50.
- Displays the final payable amount after discount.

The goal of this project is to understand basic Python concepts such as:
- User input
- Conditional statements
- Arithmetic operations
- Formatted output

---

## 🧠 Approach

The program follows a straightforward step-by-step approach:

### 1️⃣ Display Welcome Message  
The program prints a formatted welcome message to greet the user.

### 2️⃣ Take User Input  
It takes the prices of three items as input using the `input()` function and converts them to `float` to allow decimal values.

### 3️⃣ Calculate Total  
The total bill amount is calculated by summing the three item prices:

```python
total = it1 + it2 + it3
```

### 4️⃣ Apply Discount  
- If the total amount is greater than 50, a 10% discount is applied.
- Discount is calculated as:

```python
discount = total * 0.1
```

### 5️⃣ Generate Final Bill  
The program prints:
- Total amount
- Discount amount
- Final payable price (Total - Discount)

Formatted output is used to display values up to 2 decimal places.

---

## ⚙️ Technologies Used

- Python 3
- Basic console input/output
- Conditional statements (`if`)
- f-strings for formatted printing

---

## ▶️ How to Run the Program

1. Install Python 3 on your system.
2. Copy the code into a file named:

```
grocery_billing.py
```

3. Open terminal or command prompt.
4. Navigate to the file location.
5. Run the program using:

```
python grocery_billing.py
```

6. Enter item prices when prompted.

---

## 📊 Example Output

```
------------------------
--> WELCOME TO <--
GROCERY BILLING SYSTEM
------------------------

Enter Price of item 1: 20
Enter price of item 2: 25
Enter price of item 3: 15

-----------------------
---Billing Details---
-----------------------
Total : 60.00
Discount : 6.00
Final Price : 54.00

Thank You For Shopping
```

---
