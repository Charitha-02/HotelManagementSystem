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

- To reduce manual work in hotel management  
- To manage customer and room records efficiently  
- To provide quick booking and billing services  
- To maintain accurate and secure hotel data  
- To understand real-world Java application development  

---

## 🚀 Features

- Secure login system for staff  
- Customer registration and management  
- Room allocation based on availability  
- Check-in and check-out handling  
- Automatic bill calculation  
- Room status update (Available / Occupied)  
- Database integration using MySQL  
- User-friendly Java Swing GUI  
- Error handling and validation  

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
- Add new customers
- Store personal and identity details
- Assign rooms during check-in

### 3. Room Management Module
- Displays available and occupied rooms
- Automatically updates room status

### 4. Booking Module
- Handles room reservations
- Links customers with room data

### 5. Billing Module
- Calculates total bill based on stay duration
- Displays deposit and final amount

### 6. Database Module
- Stores customer, room, and booking data
- Ensures persistent storage

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
└── README.mdHotelManagementSystem/
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

Before running the project, ensure the following are installed:

- Java JDK 8 or higher  
- MySQL Server  
- VS Code or any Java IDE  
- Git (optional)  

---

## 🗄️ Database Configuration

1. Start MySQL server.
2. Create a database:
   ```sql
   CREATE DATABASE hotel_db;
Select the database:

USE hotel_db;


Import SQL file:

source queries.sql;


Update database credentials inside the Java connection file.
▶️ How to Run the Application

Clone or download the repository.

Open the project in VS Code or Eclipse.

Ensure MySQL server is running.

Compile and run the main Java file.

The Hotel Management System window will appear.

📸 Screenshots

Screenshots of the application interface are available in the images folder.

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

---

