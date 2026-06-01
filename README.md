# Interactive Terminal Banking System

A pure Python-based command-line application that simulates a real-world ATM/Banking dashboard. This project serves as a practical demonstration of **Object-Oriented Programming (OOP)**, state management, and real-time user-input handling.

---

## 🛠️ Key Programming Concepts Covered

* **Object-Oriented Programming (OOP):** Utilizes a dedicated `BankAccount` class blueprint to instantiate unique, self-contained user account objects with isolated data properties.
* **Encapsulation & State Management:** Safely modifies sensitive account attributes (like net balance balances) strictly through validated class methods (`deposit` and `withdraw`).
* **Dynamic Auditing:** Features a structural list backend that logs an active, immutable string-based ledger of every user transaction made during the runtime session.

---

## 📋 Execution Preview & Demonstration

When initialized, the application launches an interactive recursive loop in the console terminal. Here is a live execution log matching a successful user lifecycle test:

```text
🏦 Welcome to the Python Terminal Banking System
Enter account holder name to start: Malavika S

--- AVAILABLE OPTIONS ---
1. Check Balance & Statement
2. Make a Deposit
3. Withdraw Cash
4. Exit System
Select an option (1-4): 2
Enter deposit amount: $100

✅ Success! Deposited $100.00. New Balance: $200.00

=== 📄 BANK STATEMENT FOR MALAVIKA S ===
 -> Account opened with balance: $100.00
 -> Deposited: $100.00
=====================================
FINAL NET BALANCE: $200.00
