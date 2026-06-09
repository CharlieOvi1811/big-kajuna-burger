# 🍔 Big Kajuna Burger Ordering System

A lightweight, interactive command-line terminal application written in Python. It allows restaurant customers to browse a categorized food menu, place customized orders with validation, and view an itemized receipt including taxes and fees.


## 📸 App Preview

Here is a look at the Big Kajuna Burger terminal system in action:

### 1. Main Menu and Ordering
![Uploading Greet_Name_input_order.png…](<img width="1230" height="1022" alt="Greet_Name_input_order" src="https://github.com/user-attachments/assets/91ad2a0d-f009-4434-a6ab-ad34fc6ca933" />
)


### 2. Ordering
![Big Kajuna Order Input.png](assets/<img width="911" height="835" alt="order_input" src="https://github.com/user-attachments/assets/c3583fcb-1721-405a-8a01-a49f017b6e11" />
)



###3. Order Review and Receip
![Big Kajuna Receipt Preview]((assets/<img width="1058" height="786" alt="Readback_total_tax_service_fee" src="https://github.com/user-attachments/assets/371269e1-2ea5-40f8-8627-2aac1f589236" />
)



---

## 🚀 Features

*   **Personalized Experience**: Welcomes customers by name.
*   **Categorized Menu**: Features Burgers, Sandwiches, Sides, Desserts, and Drinks with live prices.
*   **Smart Order Validation**: Prevents invalid orders and non-numeric quantities.
*   **Cumulative Cart**: Allows adding multiple items and automatically calculates dynamic quantities.
*   **Itemized Receipt**: Automatically calculates a 2% IVA tax, a 10% service fee, and outputs a formatted receipt.

---

## 🛠️ Requirements

*   **Python 3.x** installed on your system.

---

## 💻 How to Run

1. **Clone or Download** this repository.
2. Open your terminal or command prompt.
3. Navigate to the project directory:
   ```bash
   cd /path/to/big-kajuna-burger
   ```
4. Run the Python file:
   ```bash
   python main.py
   ```

---

## 📋 Menu Reference

| Category | Item | Price |
| :--- | :--- | :--- |
| **Burgers** | Big Kajuna Cheeseburger | $5.99 |
| | Big Kajuna Texan Burger | $7.99 |
| | Big Kajuna Double Burger | $8.99 |
| **Sandwiches** | Kajuna Philly Sandwich | $5.99 |
| | Kajuna Hero Sandwich | $6.99 |
| | Kajuna Italian Sandwich | $7.99 |
| **Sides** | Fries | $2.99 |
| | Onion Rings | $3.49 |
| | Mozzarella Sticks | $4.99 |
| | Fried Mushrooms | $6.99 |
| **Desserts** | Kajuna Ice Cream | $2.99 |
| | Kajuna Brownie | $3.99 |
| | Kajuna Cookie | $1.99 |
| **Drinks** | Kajuna Soda | $1.99 |
| | Kajuna Spirit | $0.99 |
| | Milkshake | $4.49 |

---

## 🧾 Calculations Breakdown

The final receipt automatically calculates fees based on the user's initial subtotal:
* **Subtotal**: Sum of all items and quantities.
* **IVA**: 2% of the subtotal.
* **Service Fee**: 10% of the subtotal.
* **Total**: Subtotal + IVA + Service Fee.
Author

Carlos Oviedo

Learning Python and building practical projects for software development and automation.
