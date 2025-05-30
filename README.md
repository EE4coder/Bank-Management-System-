# 🏦 Bank Management System

## Overview

The **Bank Management System** is a software application designed to manage the day-to-day operations of a banking system, including user registration, login, transactions (deposit/withdrawal), balance inquiry, and more. This project simulates the functionality of an ATM machine, allowing users to perform basic banking operations in a user-friendly interface.

The system is implemented using **Java** for the application logic, with a **MySQL** database for storing user data, transactions, and account information.

## Features

1. **User Registration**: Users can sign up by providing personal and account information such as name, address, email, and more.
   
2. **User Login**: Users log in to the system using a unique card number and PIN.

3. **Deposit**: Users can deposit money into their account.

4. **Withdrawal**: Users can withdraw money, with a maximum limit of Rs. 10,000 per transaction.

5. **Balance Enquiry**: Users can check their current balance.

6. **Fast Cash**: Users can quickly withdraw predefined amounts (Rs. 100, Rs. 500, Rs. 1000, etc.).

7. **Mini Statement**: Users can view a mini statement that lists recent transactions.

## 🛠️ Tech Stack
- **Frontend**:Java, Swing
  - **Java**: Main programming language for building the GUI and application logic.
  - **Swing**: Java library used to create graphical user interfaces.
- **Backend**: JDBC
  - **JDBC (Java Database Connectivity)**: For connecting the Java application to the MySQL 
                                           database.
- **Database**: MySQL
  - **MySQL**: Used for storing user and transaction data.

## ⚡ Quick Start
  **Prerequisites**

Before running the project, make sure we have the following installed:

- **Java Development Kit (JDK)** version 8 or higher.
- **MySQL** database server.
- **MySQL Workbench** (optional, for managing the database).
    - [mysql-connector-java](https://dev.mysql.com/downloads/connector/j/)
- JDBC Driver for MySQL (typically `mysql-connector-java`).

### File Structure:

The project consists of the following key files:

- **src/**: Contains the Java source files for the application logic.
  - `Deposit.java`: Handles the deposit functionality.
  - `BalanceEnquiry.java`: Handles the balance enquiry functionality.
  - `Withdrawl.java`: Handles the withdrawal functionality.
  - `FastCash.java`: Handles fast cash withdrawals.
  - `mini.java`: Displays a mini statement of recent transactions.
  - `Con.java`: Manages the database connection.
  - `main_Class.java`: Entry point to the application, initializing the login screen.

- **database/**: Contains the SQL scripts for setting up the MySQL database and tables.

- **icon/**: Contains any icons used in the application (e.g., ATM images).

## 🌟 Features
- **User Authentication** (Card Number + PIN)
- **Transactions**:
  - 💵 Deposit/Withdrawal (₹10,000 limit)
  - 🚀 Fast Cash (₹100/500/1000)
- **Account Management**:
  - 📊 Balance Inquiry
  - 📜 Mini Statements
- **New User Registration**

## 🖥️ Screenshots
- | **Signup** |
 |----------|
 ![**SignUp1 Screen**](https://github.com/EE4coder/Bank-Management-System-/blob/main/SignUp1.png) ![**SignUp2 Screen**](https://github.com/EE4coder/Bank-Management-System-/blob/main/SignUp2.png) ![**SignUp3 Screen**](https://github.com/EE4coder/Bank-Management-System-/blob/main/SignUp3.png) 

- | **Login** |
 |---------|
 ![**Login**](https://github.com/EE4coder/Bank-Management-System-/blob/main/Login%20Screen.png) 

- | **Transactions** |
 |----------------|
 ![**Deposit**](https://github.com/EE4coder/Bank-Management-System-/blob/main/Deposite%20Screen.png)  ![**Mini Statement Screen**](https://github.com/EE4coder/Bank-Management-System-/blob/main/Mini%20Statement%20Screen.png) 

## 🤝Acknowledgements

Special thanks to the open-source community for the tools and libraries used in this project. The MySQL documentation helped in understanding database management and query structure.




