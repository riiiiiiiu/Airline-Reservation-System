# ✈️ Airline Reservation System

A full-stack web-based **Airline Reservation System** built using **Java (JSP & JDBC)** with **MySQL** as the database and **HTML, CSS, JavaScript** for the frontend.  
This system allows users to search flights, book tickets, manage bookings, raise complaints, and enables admins to manage flights, offers, and customer issues.

---

## 🚀 Features

### 👤 User Features
- 🔍 Search available flights
- 📖 Book flight tickets
- 👀 View booked tickets
- ❌ Cancel bookings
- 📝 Raise complaints / issues
- 📄 View booking history

### 🛠️ Admin Features
- ➕ Add new flights
- ✏️ Update flight details
- 🗑️ Delete flights
- 🎁 Manage offers
- 📊 View all bookings
- 🧑‍💼 Resolve customer complaints and issues

---

## 🧰 Tech Stack

### Backend
- Java (JSP, Servlets)
- JDBC
- Apache Tomcat (or any Java server)

### Frontend
- HTML
- CSS
- JavaScript

### Database
- MySQL

---

## 🗄️ Database

- MySQL is used to store:
  - User details
  - Flight details
  - Bookings
  - Complaints
  - Admin data

---

1. Clone the repository:
   ```bash
   git clone https://github.com/riiiiiiu/airline-reservation-system.git
Import the project into:

Eclipse / IntelliJ / NetBeans (as a Dynamic Web Project or Maven project)

Setup MySQL Database:

Create a database (e.g., airline_db)

Import the provided SQL file (if you have one)

Update database credentials in your JDBC connection file:

String url = "jdbc:mysql://localhost:3306/airline_db";
String user = "root";
String password = "your_password";
Add the project to Apache Tomcat server.

Run the project and open in browser:

http://localhost:8080/YourProjectName

📌 Modules
User Authentication

Flight Search & Booking

Booking Management

Complaint Management

Admin Dashboard

Flight & Offer Management

Role-based authentication


✅ Future Improvements (Optional)
Online payment integration

Email/SMS booking confirmation

Seat selection system

Better UI/UX


👨‍💻 Author
Rehan Shaikh
Feel free to connect and contribute!
