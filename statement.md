# Restaurant Billing System

## Problem Statement

Managing restaurant orders and calculating bills manually can take time and may lead to calculation errors.

The purpose of this project is to develop a simple Restaurant Billing System using Python. The system allows the user to enter customer details, select the type of order, choose food items, beverages and desserts, enter quantities, and generate the final bill.

The program automatically calculates the subtotal, GST and packing charges to generate the final amount.

The project is designed using basic Python programming concepts learned in the course.

## Scope of the Project

The Restaurant Billing System includes the following operations:

- Enter customer name
- Select In-Dining or Takeaway
- Enter table number for In-Dining
- Apply packing charge for Takeaway
- Display food menu
- Display beverages and desserts menu
- Select multiple items
- Enter quantity of each item
- Store item names, prices and quantities
- Calculate subtotal
- Calculate 18% GST
- Calculate packing charge
- Generate the final bill

The project is designed as a basic Python application and does not include online payment, database storage or online food ordering.

## Target Users

The main target users of this system are:

- Small restaurants
- Cafes
- Restaurant staff
- Billing staff
- Customers placing In-Dining or Takeaway orders

The system is designed to provide a simple method for entering orders and calculating restaurant bills.

## High-Level Features

### 1. Customer and Order Details

The system accepts the customer name and allows the user to select between In-Dining and Takeaway.

For an In-Dining order, the system accepts the table number.

For a Takeaway order, a packing charge is applied.

### 2. Menu and Order Selection

The system provides two menu categories:

- Food
- Beverages and Desserts

The user can select an item and enter the required quantity. Multiple items can be added to the order.

### 3. Billing and Calculation

The system calculates the amount of each ordered item based on its price and quantity.

It then calculates:

- Subtotal
- 18% GST
- Packing charge
- Final total

The final bill displays the customer details, ordered items, quantities and total amount.

## Python Concepts Used

The project uses basic Python concepts including:

- Variables
- Input and output statements
- Conditional statements
- if, elif and else
- while loop
- for loop
- range()
- Lists
- append()
- Arithmetic operations

## Project Modules

The project contains three major functional modules:

### Module 1 - Customer and Order Management

Handles customer name, order type, table number and packing charge.

### Module 2 - Menu and Order Processing

Displays the food and beverage menus, accepts item selections and quantities, and stores the order details.

### Module 3 - Billing and Calculation

Calculates the subtotal, GST, packing charge and final bill amount.
