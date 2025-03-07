# Bank Management System

## 🌟 Project Overview
The **Bank Management System** is a Java-based desktop application designed to manage banking operations efficiently. This project provides users with features such as account creation, deposits, withdrawals, balance inquiries, and transaction history tracking. The graphical user interface (GUI) is built using **Swing**, making it interactive and user-friendly.

## Features
- 🔹 User-friendly interface with a clean design
- 🔹 Secure login system with authentication
- 🔹 Deposit and withdraw money
- 🔹 View balance and mini-statements
- 🔹 Fast cash withdrawal option
- 🔹 PIN management for security

## Technologies Used
- **Java (Swing & AWT)** – For GUI development
- **JDBC (Java Database Connectivity)** – For database connectivity
- **MySQL** – For storing user and transaction details
- **IntelliJ IDEA / VS Code** – Recommended IDEs

---

## Setup & Installation
Follow these steps to set up and run the project on your local system.

### Clone the Repository
```sh
 git clone https://github.com/dushyantmehta07/Bank-Management-System.git
```

### Import the Project
- Open **IntelliJ IDEA** or **VS Code**
- Select **Open Project** and navigate to the cloned repository
- Wait for dependencies to load

### Configure Database
- Install **MySQL** if not already installed
- Open MySQL Workbench or terminal and create a database:
  ```sql
  CREATE DATABASE bank_management;
  ```
- Update the database connection details in `Connn.java`:
  ```java
  Connection con = DriverManager.getConnection("jdbc:mysql://localhost:3306/bank_management", "root", "yourpassword");
  ```

### Run the Project
- Compile and run `main_Class.java`
- The login screen should appear, and you can start using the system!

---


## Future Enhancements
- Adding an Admin panel for managing users
- Implementing two-factor authentication (2FA)
- Adding a mobile-friendly version

---

## Contributing
Feel free to fork the repository and submit pull requests with improvements or bug fixes.

---

## Contact
For any queries or support, reach out at **dushyantmehta07@gmail.com**

Enjoy coding! 

