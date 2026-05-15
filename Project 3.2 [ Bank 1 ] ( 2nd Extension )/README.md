🏦 Bank Management System (C++)
📌 Overview

This is a console-based Bank Management System written in C++.
The system allows managing clients and users, performing banking transactions, and controlling access using a permissions system.

The project uses file handling to store data permanently in text files.

⚙️ Features
👤 Client Management
Add new clients
Delete clients
Update client information
Search for a client
Display all clients
Show total balances
💰 Transactions
Deposit money into client account
Withdraw money from client account
Validate balance before withdrawal
View total balances report
👥 User Management
Add new users
Delete users
Update user information
Search users
Display all users
🔐 Security System
Login system (Username & Password)
Permissions-based access control
Restricted access for unauthorized users
🧾 Permissions System

Each user has a permission value using bitwise flags:

Permission	Value
Show Clients	1
Add Clients	2
Delete Clients	4
Update Clients	8
Find Clients	16
Transactions	32
Manage Users	64
Full Access	-1
💾 Data Storage

The system stores data in text files:

📁 Clients File
Clients.txt

Format:

AccountNumber#//#PinCode#//#Name#//#Phone#//#Balance
📁 Users File
Users.txt

Format:

Username#//#Password#//#Permissions
🚀 How to Run
Compile the program using any C++ compiler (g++ or Visual Studio)
Run the executable file
Login using username and password
Navigate through the menus
🧭 Program Structure
Main Flow:
Login → Main Menu → Select Option → Execute Function → Return to Menu
Menus:
Main Menu
Transactions Menu
Manage Users Menu
🔐 Security Logic
Every action checks user permissions
Unauthorized access shows Access Denied screen
Users with Full Access bypass all checks
🛠 Technologies Used
C++
File Handling (fstream)
Vectors (STL)
Structs
String Manipulation
Console UI (CLI)
📂 Project Structure
Bank System
│
├── main.cpp
├── Clients.txt
├── Users.txt
└── README.md
👨‍💻 Author

Developed as a training project for learning:

File handling
System design
Menu-driven applications in C++
⭐ Notes

This project is designed for educational purposes and demonstrates:

Modular programming
Basic banking operations
Permission-based access control