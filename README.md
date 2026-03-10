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
   git clone [https://github.com/Badsha012/Advance_Java_Lab_Task_04.git](https://github.com/Badsha012/Advance_Java_Lab_Task_04.git)
