🏥 Hospital Management System - Setup Guide

🔐 Login Details
Role	Username	Password
Admin	admin	admin
IPD/Account	manager	admin
Doctor	arif	admin
Staff/Employee	staff	admin
Patient	patient3	admin

Follow these steps to set up and run the Hospital Management System locally.

📦 1. Prerequisites
XAMPP installed on your system.

A copy of the Hospital Management System project folder.

Copy the project folder to:

C:\xampp\htdocs\hospital
Open XAMPP Control Panel and start:

Open XAMPP Control Panel and start:
Turn On
Apache
MySQL

Open your browser and go to:
http://localhost/phpmyadmin

Create a new database named: hospital
Import the provided .sql file into the hospital database.

download the sql file from 
https://www.vectorcoding.com/2024/05/hospital-management-system-php-nodejs.html

For tutorials and resources, visit our blog:
🔗 procoderarifbd.blogspot.com

# 🏥 Hospital Management System

A PHP-based Hospital Management System with role-based login (Admin, Doctor, Patient, Staff, IPD) designed to streamline appointments, reporting, staff coordination, and hospital operations.

---

## 🔐 Login Credentials

| Role           | Username   | Password |
|----------------|------------|----------|
| Admin          | `admin`    | `admin`  |
| IPD/Account    | `manager`  | `admin`  |
| Doctor         | `arif`     | `admin`  |
| Staff/Employee | `staff`    | `admin`  |
| Patient        | `patient3` | `admin`  |

---

## 🚀 Getting Started

Follow the steps below to set up and run the project on your local machine:

### 📦 Prerequisites
- [XAMPP](https://www.apachefriends.org/) installed
- This project downloaded into your system

### ⚙️ Installation Steps

1. Move the project folder to:
C:\xampp\htdocs\hospital

markdown
Copy
Edit
2. Start **Apache** and **MySQL** from the XAMPP Control Panel.
3. Open your browser and visit:
http://localhost/phpmyadmin

css
Copy
Edit
4. Create a database named:
hospital

yaml
Copy
Edit
5. Import the provided SQL file into the `hospital` database.

---

## 💻 Running the App

1. Visit:
http://localhost/hospital/index.php

2. Select your role (Admin, Patient, Doctor, etc.).
3. Use the credentials above to log in.

---

## 📎 Note

After logging in, the system may redirect to our official tutorial site for additional resources:

🔗 https:Vectorcoding.com

---

## 🛠 Troubleshooting

- Ensure **Apache** and **MySQL** are running.
- Make sure all tables are successfully imported into the database.
- Double-check DB credentials if the connection fails.

---

## 📚 Learn More

Detailed guides and resources can be found on our blog:

🔗  Vectorcoding.com

---

© 2024 Vectorcoding.com | All Rights Reserved
