# 🏦 Bank Account Management System (Java OOP)

This is a professional Java implementation of a **Bank Account Management System** based on Object-Oriented Programming (OOP) principles. It demonstrates **Inheritance**, **Encapsulation**, and **Composition** through a structured class hierarchy.

---

## 🛠️ Features
* **Account Base Class**: Centralized logic for account number, holder name, and balance.
* **Savings Account**: Specialized account with interest rate management.
* **Fixed Account**: Specialized account with tenure year tracking.
* **Bank Composition**: A `Bank` class that manages both Savings and Fixed accounts.
* **Encapsulation**: All data fields are private, accessed via public getter and setter methods.

---

## 🏗️ System Architecture

The project follows the structure defined in the UML diagram:

* **`Account`**: Parent class providing common attributes.
* **`SavingsAccount`**: Inherits from `Account`.
* **`FixedAccount`**: Inherits from `Account`.
* **`Bank`**: Uses composition to hold instances of accounts.
* **`Start`**: The entry point of the application.

---

## 🚀 Getting Started

### Prerequisites
* **Java Development Kit (JDK)** 8 or higher installed.
* Any IDE (IntelliJ, Eclipse, VS Code) or Terminal.

### Installation & Execution
1. **Clone the repository:**
   ```bash
https://github.com/Badsha012/Advance_Java_Lab_Task_04.git

Compile the source code:

##Bash
javac *.java
###Run the application:

Bash
java Start

Bank Name: DBBL
---------------------------
Savings Account Details:
Number: 11111111
Holder: OOP1
Balance: 10000.0
Interest Rate: 7.5%
---------------------------
Fixed Account Details:
Number: 11111112
Holder: OOP1
Balance: 100000.0
Tenure Year: 10


📜 Project Structure
Bash
├── Account.java        # Base Class
├── SavingsAccount.java # Inherited Class
├── FixedAccount.java   # Inherited Class
├── Bank.java           # Composition Class
└── Start.java          # Main Execution Class
