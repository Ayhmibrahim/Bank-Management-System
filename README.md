# 🏦 Bank Management System (C++)

--
📌 Overview

A complete banking system built in C++, developed in three progressive stages, starting from a simple client manager and evolving into a full system with:

Authentication system (Login)
Role-Based Access Control (Permissions)
Client & User management
File-based persistence

This project simulates a real-world banking architecture using structured C++ design.

🧭 System Modules
👤 Clients Management System
💰 Transactions System
🔐 Authentication System
👥 Users Management System
🚀 Project Stages
🧩 Stage 1 — Client Management System

Basic CRUD system for clients.

Features:

Add client
Delete client
Update client
Search client
File storage system
💰 Stage 2 — Transactions System

Financial operations added.

Features:

Deposit funds
Withdraw funds
Balance validation
Total balance report
🔐 Stage 3 — Full System (Final Version)

Complete secure system.

Features:

Login system
Users management
Permissions (RBAC)
Full access control
Secure operations
🔐 Permissions System
Permission	Value
Show Clients	1
Add Clients	2
Delete Clients	4
Update Clients	8
Find Clients	16
Transactions	32
Manage Users	64
Full Access	-1
📁 Data Storage Structure
Clients File

Each client is stored in this format:

AccountNumber#//#PinCode#//#Name#//#Phone#//#Balance

Users File

Each user is stored in this format:

Username#//#Password#//#Permissions

🔄 Program Flow

Login → Main Menu → Select Option → Check Permissions → Execute Action → Return Menu

👤 Test Users

Admin#//#1234#//#-1
Ahmad#//#1111#//#63
Sara#//#2222#//#31
Omar#//#3333#//#15
Lina#//#4444#//#7
Yousef#//#5555#//#32
Khaled#//#6666#//#64
Noor#//#7777#//#2
Fahad#//#8888#//#8
Mona#//#9999#//#16

🛠 Tech Stack
C++
File Handling (fstream)
Vectors (STL)
Struct-based design
Console UI (CLI)
📈 Key Learnings
System design thinking
File-based database simulation
Authentication systems
Role-based access control (RBAC)
Modular C++ architecture
🧠 Concept

This project demonstrates how a simple CRUD system can evolve into a real banking system architecture step-by-step.

👨‍💻 Author

C++ Learning Project

⭐ Note

Educational project — focuses on system design & architecture, not production banking security.

C++ Developer (Learning Project)

⭐ Note

This project is built for educational purposes and demonstrates how real systems are structured step-by-step.
