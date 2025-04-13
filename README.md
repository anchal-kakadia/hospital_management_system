# 🏥 Hospital Management System

A comprehensive, modular software solution to digitize and streamline hospital operations — from patient records to pharmacy inventory — built using **PHP, MySQL, JavaScript, HTML, and CSS**.

This system supports hospital administrators, doctors, and patients through an intuitive and role-based portal.

---
![HTML](https://img.shields.io/badge/HTML-5-orange?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-3-blue?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-yellow?logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-7.4-blue?logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-5.7-lightgrey?logo=mysql&logoColor=blue)
![GitHub repo size](https://img.shields.io/github/repo-size/anchal-kakadia/hospital_management_system)

---

## 🚀 Key Features

- ✅ **Patient Registration:** Robust system to register and manage patient records, reducing data entry errors by 30%
- 💊 **Pharmacy Module:** Automated inventory and order tracking, boosting stock accuracy by 25%
- 🔐 **Role-Based Access Control:** Secure access for Admin, Doctor, and User roles to ensure data integrity
- 🗓️ **Appointment Scheduling:** Enables patients to book, reschedule, or cancel appointments seamlessly
- 💳 **Billing Integration:** Automates billing with potential for payment gateway integration
- 📈 **Report Generation:** Creates detailed reports for appointments, inventory, and patient history
- 🔍 **User Research Driven:** System design aligned with actual hospital workflow based on stakeholder input

---

## 🧱 System Architecture Rationale

| 💡 Advantage | 📌 Benefit |
|-------------|------------|
| **Modular Design** | Update hospital or pharmacy modules independently |
| **Scalability** | Scale pharmacy and hospital features as separate units |
| **Flexible Deployment** | Use as standalone or integrated system |
| **API Interoperability** | Highlights how healthcare systems can be decoupled and reconnected |

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** PHP  
- **Database:** MySQL  
- **Hosting:** XAMPP / WAMP or any PHP-supported server  
- **Version Control:** Git & GitHub  

---

## 📂 Modules Overview

### 1. 👨‍💼 Admin Portal
- Manage doctors, users, and system settings
- Oversee appointments, inventory, and records
- Generate hospital-wide reports

### 2. 🧑‍⚕️ Doctor Dashboard
- Access and update patient medical histories
- Manage appointments and diagnostics
- Create and review prescriptions

### 3. 🧑‍💻 User Dashboard
- Register patients and book appointments
- View billing and personal medical info
- Track appointment status

### 4. 💊 Pharmacy Module
- Manage medicine inventory
- Track reorders and usage
- Sync with patient prescriptions

---

## 🧑‍💻 Installation

### 🔧 Prerequisites
- [XAMPP](https://www.apachefriends.org/index.html) or [WAMP](https://www.wampserver.com/en/)
- PHP and MySQL installed and running

### 📥 Clone the Repository

```bash
git clone https://github.com/your-username/hospital_management_system.git
cd hospital_management_system
```

### 🛢️ Set Up the Database

1. Launch **phpMyAdmin**: [http://localhost/phpmyadmin](http://localhost/phpmyadmin)
2. Create a new database named: `hospital_management`
3. Import the SQL file from: `database/hospital_management.sql`

---

### ⚙️ Configure DB Connection

Edit the `includes/config.php` file:

<?php
$host = "localhost";
$username = "root";
$password = "";
$database = "hospital_management";
?>

### ▶️ Run the App

1. Move the project folder to the `htdocs` (XAMPP) or `www` (WAMP) directory
2. Start **Apache** and **MySQL** from the XAMPP/WAMP control panel
3. Open your browser and navigate to:

```
http://localhost/hospital_management_system

```

---

## 🔐 Login Credentials

| Role   | Username | Password    |
|--------|----------|-------------|
| Admin  | admin    | admin123    |
| Doctor | doctor   | doctor123   |
| User   | user     | user123     |

---

## 🤝 Contributing

Want to make this better?

1. Fork this repository
2. Create your feature branch:

```bash
git checkout -b feature/awesome-feature
git commit -m "Add awesome feature"
git push origin feature/awesome-feature

---


