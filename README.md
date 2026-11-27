# 🏦 C++ Banking System
**C++ | OOP | Console Application | File-Based Persistence**

---

## 📌 Overview
A complete console banking system built in C++ with a strong focus on Object-Oriented Programming and clean, modular design.

It was built as the final project of a C++ OOP course, with every part of the system implemented from scratch using only the C++ Standard Library (no external dependencies).

The system simulates a realistic banking environment: clients, accounts, users, currencies, transfers, permissions, and activity logging.

---

## ✨ Key Features
- **Clients Management:** Add, edit, delete, and search clients with full balance tracking.
- **Bank Accounts:** Deposits, withdrawals, and internal transfers with real-time balance updates.
- **User Management:** Multi-user system with username/password and role-based access control (binary enums + bitwise permission checks).
- **Currencies:** Store, update, and convert between currencies with exchange rates.
- **Logging & Monitoring:** Transfers, logins, and user activities tracked in .txt log files.
- **Security:** Restricted access to sensitive screens and active user session control.
- **File-Based Persistence:** Clients.txt, Users.txt, Currencies.txt and log files act as a simulated database.
- **Utilities:** Custom utility classes (clsString, clsDate, clsInputValidate, clsUtil) for parsing, validation, and date handling.

---

## 🧠 OOP Concepts Implemented
- **Encapsulation:** All data handled securely inside classes.
- **Inheritance:** Every screen inherits from a common `clsScreen` base class.
- **Polymorphism & Abstraction:** Used across UI screens for flexibility and scalability.

---

## 🧰 Technology Stack
- C++ (Standard Library only)
- Visual Studio 2022

---

## ▶️ Getting Started

### 1️⃣ Requirements
- Windows + Visual Studio 2022 (C++ workload)

### 2️⃣ Build & Run
1. Open `Bank Project.sln` in Visual Studio.
2. Build the solution and run.

### 3️⃣ Demo Login
Sample users are stored in `Bank Project/Users.txt`, for example:
- Username: `User1` - Password: `1234` (full permissions)
- Username: `User2` - Password: `1234`

---

## 📂 Project Structure
- `Bank Project.cpp` - program entry point
- `clsMainScreen` + screen classes (`cls*Screen.h`) - UI screens, all inheriting from `clsScreen`
- `clsBankClient.h`, `clsUser.h`, `clsPerson.h` - core domain classes
- `clsString.h`, `clsDate.h`, `clsInputValidate.h`, `clsUtil.h` - utility classes
- `Clients.txt`, `Users.txt`, `Currencies.txt` - file-based data store
- `TransferLog.txt`, `LoginRegister.txt` - activity logs

---

## 📝 Notes
This is a learning project: data is stored in plain-text files to simulate a database, and sample passwords are visible in those files. A production system would use a real database and hashed passwords.
