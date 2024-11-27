# Billing System with Inventory Management

A Python-based project that implements a billing system with inventory management. This program allows users to browse products, purchase items, generate invoices, and automatically update stock levels in a JSON file while logging sales in a CSV file.

## Features
-Displays available products with their price and stock quantity.
-Allows customers to purchase items based on availability.
-Dynamically updates the inventory stored in a JSON file.
-Applies discounts for purchases over ₹500.
-Calculates taxes (SGST and CGST).
-Generates a detailed receipt for the customer.
-Logs all transactions in a CSV file for future reference.

## Project Overview
This project demonstrates an Object-Oriented Programming (OOP) approach to build a billing system. It is ideal for learning:

-File handling in Python (JSON and CSV).
-Implementation of OOP principles like encapsulation and modularity.
-Practical application of inventory management concepts.

## Code Highlights
. Class-Based Design
The project uses Object-Oriented Programming principles:

-Product: Represents individual products.
-Inventory: Handles inventory loading and updating.
-Customer: Stores customer details.
-Sale: Processes purchases and generates receipts.
2. File Handling
-Inventory is stored and dynamically updated in a JSON file.
-Transactions are logged in a CSV file for audit and reporting.
3. Example Output


----------------------MENU-------------------------
P001 : Laptop         | ₹1000    | Quantity: 10
P002 : Phone          | ₹500     | Quantity: 20
P003 : Tablet         | ₹700     | Quantity: 15

----------------------BILL-------------------------
Name of the Product      : Laptop
Price of the Product(₹)  : ₹ 1000
Quantity                 : 2
SGST(7.5%)               : ₹150.00
CGST(7.5%)               : ₹150.00
Discount(10%)            : ₹200.00
Total Bill               : ₹2100.00
---------------------------------------------------

## Technologies Used
-Programming Language: Python
-File Formats: JSON (for inventory), CSV (for sales records)
