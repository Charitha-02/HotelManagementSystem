# Hotel Management System

A Java-based Hotel Management System developed to automate hotel operations such as room booking, customer handling, check-in/check-out, and billing management.  
The application provides an interactive graphical interface using Java Swing and ensures reliable data storage using MySQL.

---

## 📘 Introduction

The Hotel Management System is a desktop application designed to simplify hotel management tasks.  
Manual record keeping often leads to errors, data loss, and inefficiency. This system replaces manual work with an automated solution that improves accuracy and performance.

The project demonstrates how Java applications can be integrated with databases to solve real-world business problems.

---

## 🎯 Objectives

- Reduce manual workload in hotel operations  
- Maintain accurate customer and room records  
- Automate check-in, check-out, and billing  
- Improve data reliability and efficiency  
- Gain practical experience in Java application development  

---

## 🚀 Features

- Secure staff login system  
- Customer registration and management  
- Room allocation based on availability  
- Check-in and check-out handling  
- Automatic bill calculation  
- Room status updates (Available / Occupied)  
- MySQL database integration  
- User-friendly Java Swing GUI  
- Input validation and error handling  

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

### Login Module
- Authenticates hotel staff  
- Controls system access  

### Customer Module
- Add and manage customer information  
- Assign rooms during check-in  

### Room Management Module
- View available and occupied rooms  
- Automatically update room status  

### Booking Module
- Manage room reservations  
- Connect customer and room data  

### Billing Module
- Calculate charges based on stay duration  
- Display deposit and final amount  

### Database Module
- Store and retrieve persistent data  
- Maintain customer and booking records  

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

Before running the project, ensure the following are installed:

- Java JDK 8 or higher  
- MySQL Server  
- VS Code or any Java IDE  
- Git (optional)  

---

## 🗄️ Database Setup

1. Start the MySQL server.

2. Create the database:

```sql
CREATE DATABASE hotel_db;
USE hotel_db;
Import database tables:
source queries.sql;
Update MySQL username and password in Conn.java.
## 🗄️ Database Configuration

1. Start the MySQL server.

2. Create the database:

```sql
CREATE DATABASE hotel_db;
USE hotel_db;
Import the database tables:

source queries.sql;


Update MySQL username and password in Conn.java.
Import the database tables:

source queries.sql;


Update MySQL username and password in Conn.java.

▶️ How to Run the Application

Clone the repository:

git clone https://github.com/Charitha-02/HotelManagementSystem.git


Open the project in VS Code or Eclipse.

Ensure MySQL server is running.

Compile and run the main Java file
(Login.java or HotelManagementSystem.java).

The application window will launch.

📸 Screenshots

Application screenshots are available in the images folder:

Login Page

Dashboard

Customer Registration

Room Booking

Billing Window

📄 License

This project is intended for educational and learning use only.