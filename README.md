# Bank Management System (Java OOP Project)

An object-oriented Java application designed to manage different types of bank accounts with a flexible and scalable architecture, built as part of Software Engineering studies at Afeka College.

## 🏛️ System Architecture & Classes
The system is built using **Object-Oriented Programming (OOP)** principles (Inheritance, Polymorphism):
- **`Account` (Base Class):** Manages core attributes shared across all accounts: account number, balance, and average overdraft (`avgOverdraft`).
- **`CheckingAccount` (عو"ש):** Implements dynamic loan calculations based on overdraft limits (grants up to 50,000 ₪ if the average overdraft condition is met).
- **`MortgageAccount` (משכנתא):** Extends checking accounts to include specific mortgage data (`mortgage`).
- **`ManagerAccount` (מנהלים):** Handles bank managers' accounts, incorporating seniority years (`years`) and a fixed maximum loan limit of up to 100,000 ₪.

## 🚀 Key Features & Operations
- **`showLoan`:** Evaluates and displays the maximum eligible loan amount for each specific account based on predefined bank rules.
- **`sort`:** Sorts bank accounts in descending order based on their maximum loan capability using classical sorting algorithms.
- **`clone`:** Implements deep/independent cloning for accounts, ensuring complete independence from the original objects.

## 🛠️ Tech Stack
- **Language:** Java (OOP, Arrays, Algorithms)
- **Concepts:** Inheritance, Interfaces/Cloning, Sorting Algorithms, Encapsulation.

## ⚙️ How to Run
1. Clone or download the repository.
2. Open the project in any Java IDE (e.g., IntelliJ IDEA, Eclipse, or VS Code).
3. Compile and run the `Main` class to view the output demonstration matching the system test cases.
