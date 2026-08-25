# 📚 Library Management System (C++)

A lightweight, console-based **Library Management System** written in C++. This project allows managing book inventories, tracking student/user records, and handling book issue and return operations efficiently.

---

## ✨ Features

* **Book Management:** Add, update, view, and delete books from the database.
* **Member Management:** Register new members/students and track their details.
* **Issue & Return System:** Issue books to members and process book returns seamlessly.
* **Search Functionality:** Search books easily by ID, Title, or Author.
* **File Handling:** Persistent data storage using file streams (`fstream`) to save records permanently.

---

## 🛠️ Tech Stack & Prerequisites

* **Language:** C++ (C++11 or higher recommended)
* **Compiler:** GCC / Clang / MSVC
* **Build Tool:** Terminal or any C++ IDE (VS Code, Code::Blocks, CLion)

---

## 🚀 Getting Started

### 1. Clone the Repository

git clone [https://github.com/Pratyush-rcb/LibraryManagement_System.git](https://github.com/Pratyush-rcb/LibraryManagement_System.git)
cd LibraryManagement_System
2. Compile the Project
Using g++:


g++ -o library_system main.cpp
3. Run the Application

# On Linux/macOS:
./library_system

# On Windows:
library_system.exe
📂 Project Structure
Plaintext
LibraryManagement_System/
│
├── main.cpp          # Main source code containing logic & driver functions
├── books.txt         # Data file storing book records
├── members.txt       # Data file storing student/member records
└── README.md         # Project documentation
