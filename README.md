# Inventory-Management-System-With-Files
Here’s a sample *README.md* file for  Python inventory management system project. 
---

### README.md

markdown
# Simple Inventory Management System

This is a simple command-line based Inventory Management and Billing System written in Python. It allows a user to purchase a product from the inventory, updates the inventory accordingly, and generates a sales record.

---

##  Features

- Read products from `Inventory.txt`
- User input for name, phone, email, product ID, and quantity
- Checks inventory for availability
- Generates a bill for the purchase
- Logs the sale into `Sales.txt`
- Updates the inventory automatically

---

## File Structure

- `Inventory.txt` — Contains a list of available products in the format:
  
  
  ProductID,ProductName,Price,Quantity
  

  Example:

  
  101,Apple,10,100
  102,Banana,5,50
  

- `Sales.txt` — Appends sale transactions in the format:

  
  Username,Phone,Email,ProductName,ProductID,Quantity,TotalAmount,Timestamp
  

- `inventory_system.py` — The main Python script to run the system.

---

##  How to Use

1. Make sure you have Python installed (Python 3.x).
2. Create a text file named `Inventory.txt` and populate it with product data (see format above).
3. Run the script:

   bash
   python inventory_system.py
   

4. Enter the requested user and product details when prompted.
5. If the product exists and the quantity is sufficient, the order is processed and the inventory is updated.
6. A record of the sale is saved in `Sales.txt`.

---

##  Example Interaction


Enter your Name: Alice
Enter your Phone No: 1234567890
Enter your Mail: alice@example.com
Enter product ID: 101
Enter product Quantity: 2
--------------------------------------------
Product Name     : Apple
Price            : 10
Quantity         : 2
--------------------------------------------
Billing Amount   : 20
--------------------------------------------

------------------------------------------
Thanks for your order, Inventory updated! 
------------------------------------------


---

##  Future Improvements (Optional)

- Add support for multiple purchases in a single session
- Improve error handling for file issues and input formats
- Add product management features (add/delete/update items)
- Implement a GUI or web interface

---

##  Author

Developed by [Sahana ]  
