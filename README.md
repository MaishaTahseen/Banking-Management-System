# 🏦 Banking Management System (BMS)

A **C# Windows Forms Banking Management System** designed to simulate real-world banking operations for learning and demonstration purposes. This application provides role-based access for customers, employees, and managers to manage accounts, transactions, and loans in a simple and user-friendly interface.

---

## Features

### User Roles

**Customer**
* View account details and balance
* Deposit and withdraw money
* Apply for loans
* Repay loans

**Employee**
* Manage customer information
* Review loan applications
* Process transactions

**Manager / Admin**
* Approve or reject loans
* Manage employees and customers
* Monitor transactions and activities

---

##  Core Functionalities

**Secure Login System**

* Role-based authentication
* Separate access for customers, employees, and managers

**Account Management**

* Create accounts
* Update customer details
* Deactivate accounts

**Transaction Handling**

* Deposits
* Withdrawals
* Fund transfers
* Transaction records

**Loan Management**

* Loan application system
* Approval/rejection workflow
* Loan repayment tracking

**User Interface**

* Clean and interactive Windows Forms UI
* Easy navigation

---

## Technologies Used

* **Language:** C# (.NET Framework)
* **IDE:** Visual Studio
* **UI Framework:** Windows Forms
* **Database:** Microsoft SQL Server 2014
* **Version Control:** Git & GitHub

---

## Installation and Setup

1. Download the Project
    * Go to the repository: **Banking Management System**
    * Click the green **Code** button and select **Download ZIP**
    * Extract the ZIP file to a folder on your computer
2. Set Up SQL Server Database
    * Install **Microsoft SQL Server** and **SQL Server Management Studio (SSMS)** if not already installed
    * Open SSMS and create a new database named: BankingManagementSystem
    * Open the provided SQL script file
    * Import/run the script in SSMS to create tables and sample data
3. Configure Database Connection
    * Open the project in **Visual Studio**
    * Locate the file: ApplicationHelper.cs
    * Update the connection string with your SQL Server details:
    ```csharp
    Data Source=YOUR_SERVER_NAME;
    Initial Catalog=BankingDB;
    Integrated Security=True;
    ```
4. Run the Application
    * Open the `.sln` file in **Visual Studio**
    * Click **Build → Build Solution**
    * Press **F5** or click **Start** to run

---

## Contributing

Contributions and suggestions are welcome! Open an issue or submit a pull request for improvements.

---

## Maintainer

**Maisha Tahseen**
GitHub: MaishaTahseen

---

## License

This project is open-source and available under the **MIT License**.


