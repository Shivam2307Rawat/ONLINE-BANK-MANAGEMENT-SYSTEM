# 🏦 Online Bank Account Management System

## 📋 Project Overview
This is a simple Java-based **Online Bank Account Management System** built as a command-line application. Users can create a new bank account by entering their name, deposit and

withdraw money, and view account details including balance and account number.


The project focuses on implementing **robust exception handling** techniques such as:

- User-defined exceptions (`InvalidAmountException`, `InsufficientFundsException`)
  
- Handling input mismatches (`InputMismatchException`)
  
- Using `try-catch-finally` blocks
   
- Propagating exceptions using `throw` and `throws`


## ✨ Features

- Create a new bank account
  
- Deposit money (with error handling for invalid amounts)
  
- Withdraw money (with insufficient funds check)
  
- View account balance and account details
  
- Proper input validation and safe scanner closure
  

## 🛠️ Technologies Used

- Java
  
- OOP Concepts (Classes, Objects)
  
- Exception Handling (User-defined and built-in)
  

## 🚀 How to Run

1. Clone the repository or download the source code.

2. Compile the Java files:
   ```bash
   javac BANK.java
   ```
  
3. Run the program:
   ```bash
   java BANK
   ```
   

## 📂 Project Structure

- `BANK.java` — Main class containing program logic and menu
  
- `BankAccount` — Model class representing a bank account
  
- `InvalidAmountException` — Custom exception for invalid deposit/withdrawal
  
- `InsufficientFundsException` — Custom exception for withdrawal beyond balance
