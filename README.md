# 🏥📚 Java-Based Hospital & College Management Systems

This repository contains **two Java GUI projects** developed using **Core Java**, **Java Swing**, **JDBC**, and **MySQL**:

1. **Hospital Management System**
2. **College Management System**

These projects were developed as part of academic practice to learn Java programming, GUI development, and database integration.

---

## 🛠️ Technologies Used

| Component     | Technology         |
|---------------|--------------------|
| Language       | Java (Core + JDBC) |
| GUI/Frontend   | Java Swing         |
| Backend DB     | MySQL              |
| Connectivity   | JDBC               |

---

## 🏥 Hospital Management System – Features

- ➕ **Add Patient** – Register new patients  
- ❌ **Delete Patient** – Remove patient records  
- 🔍 **Search Patient** – Search patients by name, ID, or mobile  
- 📋 **View Patients** – Display all patient records  
- 📅 **Get Appointment** – Schedule new appointments  
- 👩‍⚕️ **View Doctors** – View list of available doctors  
- 🧾 **Search Doctor/Patient** – Search functionality for doctors and patients  
- 🔎 **Check Appointments** – View scheduled appointments  

**Tech Stack:** Java Swing for GUI, MySQL as backend, JDBC for data connectivity.

---

## 📚 College Management System – Features

- 🔐 **Login System** – Simple login/authentication  
- ➕ **Add Student** – Register new students  
- ❌ **Delete Student** – Delete student records  
- 🔍 **Search Student** – Search by name, ID, etc.  
- 📋 **View Students** – Show all student data in a table  
- 🔁 **Update Student** – Modify student details  

**Tech Stack:** Java Swing GUI, JDBC connection to MySQL database.

---

---

## ⚠️ Important Notes

- 📂 A text file containing all the **required SQL queries** is included with each project (`database_hospital.sql` and `database_college.sql`).
- 🛠️ **You must create your own MySQL database** and run the provided SQL queries before starting the application.
- 🔌 In the source code (usually in `DBConnection.java`), **update the following values as per your system**:
  ```java
  String url = "jdbc:mysql://localhost:3306/your_database_name";
  String user = "your_mysql_username";
  String password = "your_mysql_password";

