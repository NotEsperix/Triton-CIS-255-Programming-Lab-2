# CIS255 Lab 2: Object-Oriented Laptop Inventory System

## Project Overview
This was a C++ application to apply the concepts of object-oriented programming, focusing on the principle of encapsulation. Program allowing a user to manage some laptops, add laptops to a shopping cart, and check out. It contains one class, `Laptop`, including attributes and methods like constructors, getters, and setters, among others, including some interaction with input functions.

## Program Features
- **Library Management:** Admin users can view, add, or remove laptops from the library.
- **Shopping Cart:** Consumer users can add or remove laptops from a cart, and view their total price at checkout.
- **Object-Oriented Design:** The program utilizes encapsulation, constructors, getters, setters, and member functions to interact with the `Laptop` class.

## Class Definition
The `Laptop` class has the following attributes:
- `brand` (string)
- `model` (string)
- `price` (double)
- `ramSizeGB` (int)
- `storageSizeGB` (int)
- `barcode` (int)

## Dataset
The program starts with three predefined laptops:
| Brand        | Model              | Price  | RAM Size | Storage Size | Barcode |
|--------------|--------------------|--------|----------|--------------|---------|
| Dell         | XPS 13             | $999.99| 16 GB    | 512 GB       | Randomly generated |
| Apple        | MacBook Pro        | $1999.99| 16 GB   | 1024 GB      | Randomly generated |
| Lenovo       | ThinkPad X1 Carbon | $1299.99| 16 GB   | 256 GB       | Randomly generated |

## How to Run
1. Clone the repository to your local machine.
2. Open the `main.cpp`, `laptop.cpp`, and `laptop.h` files in a C++ IDE (e.g., Visual Studio, Code::Blocks).
3. Compile and run the program to interact with the laptop inventory system.

### User Interface
- **Admin Menu:**
  - View laptops in the library.
  - Add a new laptop.
  - Remove a laptop from the library.
- **Consumer Menu:**
  - View laptops.
  - Add laptops to the shopping cart.
  - Remove laptops from the shopping cart.
  - Checkout the shopping cart.

## Files Included
- **main.cpp:** The main program file that handles user interaction.
- **laptop.cpp:** The implementation file for the `Laptop` class.
- **laptop.h:** The header file containing the `Laptop` class definition.

## Requirements
This project requires the following:
- A C++ compiler (e.g., g++, Visual Studio, or Code::Blocks)

## Author
Edgardo Richard Ventura (Eddie)
CIS255: C++ Programming, Fall 2024
