# Hotel Management System

A complete Java-based Hotel Management System designed to automate hotel operations such as room booking, customer handling, check-in/check-out, and billing management.  
The application provides a simple and interactive graphical interface using Java Swing and ensures reliable data storage using MySQL.

---

## 📘 Introduction

The Hotel Management System is a desktop-based application developed to simplify the management of hotel services.  
Traditional hotel operations involve manual record keeping, which can lead to errors, data loss, and inefficiency.  
This system automates those processes and improves accuracy, speed, and reliability.

The project simulates a real-world hotel workflow and demonstrates how software solutions can be applied in hospitality management.

---

## 🎯 Objectives

- Reduce manual work in hotel management  
- Manage customer and room records efficiently  
- Provide quick booking and billing services  
- Maintain accurate and secure hotel data  
- Understand real-world Java application development  

---

## 🚀 Features

- Secure login system for staff  
- Customer registration and management  
- Room allocation based on availability  
- Check-in and check-out handling  
- Automatic bill calculation  
- Room status update (Available / Occupied)  
- MySQL database integration  
- User-friendly Java Swing GUI  
- Error handling and input validation  

---

## 🛠️ Technologies Used

- **Programming Language:** Java  
- **GUI Framework:** Java Swing  
- **Database:** MySQL  
- **Connectivity:** JDBC  
- **IDE:** VS Code / Eclipse  
- **Version Control:** Git & GitHub  

---

## 🧩 System Modules

### 1. Login Module
- Authenticates hotel staff  
- Provides secure system access  

### 2. Customer Module
- Add and manage customer details  
- Store identity and personal information  
- Assign rooms during check-in  

### 3. Room Management Module
- Display available and occupied rooms  
- Automatically update room status  

### 4. Booking Module
- Handle room reservations  
- Link customers with room information  

### 5. Billing Module
- Calculate bill based on stay duration  
- Display deposit and final amount  

### 6. Database Module
- Store customer, room, and booking data  
- Ensure persistent data storage  

---

## 📂 Project Structure

HotelManagementSystem/
│
├── src/
│ ├── database/
│ ├── model/
│ ├── service/
│ └── ui/
│
├── images/
│ ├── login.png
│ ├── dashboard.png
│ ├── booking.png
│ └── billing.png
│
├── queries.sql
└── README.md

---

## ⚙️ Prerequisites

Ensure the following are installed before running the project:

- Java JDK 8 or higher  
- MySQL Server  
- VS Code or any Java IDE  
- Git (optional)  

---

## 🗄️ Database Configuration

1. Start MySQL server.

2. Create database:

```sql
CREATE DATABASE hotel_db;
USE hotel_db;
Import database tables:

source queries.sql;


Update MySQL username and password in Conn.java.
How to Run the Application

Clone the repository or download the ZIP file.
git clone https://github.com/Charitha-02/HotelManagementSystem.git
Open the project in VS Code or Eclipse.

Ensure MySQL server is running.

Compile and run the main Java file
(Login.java or HotelManagementSystem.java).

The application window will open.
📸 Screenshots

Screenshots of the application interface are available in the images folder:

Login Page

Dashboard

Customer Registration

Room Booking

Billing Window

📚 Learning Outcomes

Through this project, the following concepts were practiced:

Core Java programming

Object-Oriented Programming (OOP)

Java Swing GUI development

JDBC connectivity

SQL database operations

Exception handling

Real-world business workflow design

📌 Note

This project is adapted from an open-source GitHub repository and enhanced for academic, learning, and resume-building purposes.
All features were studied, modified, and understood to strengthen practical Java and database skills.

📄 License

This project is intended for educational and learning use only.