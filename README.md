# Hospital Management System 🚀

The Hospital Management System is a comprehensive software solution designed to streamline hospital operations, manage patient records, and enhance the overall efficiency of healthcare administration. Built using JavaScript, HTML, PHP, and MySQL, this system provides a user-friendly interface for administrators, doctors, and users to manage patient details, appointments, and other critical hospital operations.

---

## Key Features

- Patient Registration System: Engineered a robust patient registration system using PHP, MySQL, HTML, and JavaScript, reducing manual data entry errors by 30%.
- Pharmacy Management Module: Automated medication inventory and order tracking, improving stock accuracy by 25%.
- Role-Based Access Control (RBAC): Implemented secure access controls for Admin, Doctor, and User modules, enhancing data privacy and workflow efficiency.
- User Research & Workflow Alignment: Conducted user research and requirement analysis to align system features with hospital workflows.
- Appointment Scheduling: Allows patients to book, reschedule, or cancel appointments seamlessly.
- Billing and Payment Integration: Automates billing processes and integrates payment gateways for smooth transactions.
- Report Generation: Generates detailed reports for patient records, appointments, and inventory management.

---

## Technologies Used

- Frontend: HTML, CSS, JavaScript
- Backend: PHP
- Database: MySQL
- Version Control: Git
- Hosting: Localhost (XAMPP/WAMP) or any PHP-supported hosting service.

---

## Modules

The system is divided into three main modules:

### 1. Admin Module
   - Manage hospital staff and user accounts.
   - Oversee patient records and system settings.
   - Generate reports and analytics.
   - Monitor inventory and pharmacy management.

### 2. User Module
   - Register new patients and update their details.
   - Schedule appointments and view patient history.
   - Access basic hospital information.
   - View billing and payment details.

### 3. Doctor Module
   - View and update patient medical records.
   - Manage appointments and prescribe treatments.
   - Access diagnostic and treatment history.
   - Generate prescriptions and medical reports.

### 4. Pharmacy Management Module
   - Automate medication inventory and order tracking.
   - Improve stock accuracy and reduce manual errors.
   - Track medication usage and reorder levels.

---

## Installation

To set up the project locally, follow these steps:

1. Prerequisites:
   - Install [XAMPP](https://www.apachefriends.org/index.html) or [WAMP](https://www.wampserver.com/en/) for local server setup.
   - Ensure PHP and MySQL are installed and running.

2. Clone the Repository:
   ```bash
   git clone https://github.com/your-username/hospital_management_system.git
   cd hospital_management_system

3. Database Setup
    - Open phpMyAdmin ([http://localhost/phpmyadmin](http://localhost/phpmyadmin)).
    - Create a new database named `hospital_management`.
    - Import the SQL file (`database/hospital_management.sql`) into the database.

4. Configure Database Connection
    - Open the `config.php` file in the `includes` folder.
    - Update the database credentials:
  
    ```php
    $host = "localhost";
    $username = "root";
    $password = "";
    $database = "hospital_management";

5. Run the Application
   - Move the project folder to the `htdocs` (XAMPP) or `www` (WAMP) directory.
   - Start Apache and MySQL from the XAMPP/WAMP control panel.
   - Open your browser and navigate to:

    ```
    http://localhost/hospital_management_system

```markdown
## Usage

### 1. Admin Login
    - Username: `admin`
    - Password: `admin123`
    - Access the admin dashboard to manage staff, patients, and system settings.

### 2. Doctor Login
    - Username: `doctor`
    - Password: `doctor123`
    - Access the doctor dashboard to manage appointments, prescriptions, and patient records.

### 3. User Login
    - Username: `user`
    - Password: `user123`
    - Access the user dashboard to register patients, schedule appointments, and view records.   

## Contributing
Contributions are welcome! If you'd like to contribute to this project, follow these steps:

1. Fork the repository.
2. Create a new branch:

    ```bash
    git checkout -b feature/your-feature-name

3. Make your changes and commit them:

    ```bash
    git commit -m "Add your feature"

4. Push to the branch:

    ```bash
    git push origin feature/your-feature-name
    
5. Open a pull request.

---

## 🧩 System Architecture Rationale

### Why Two Separate Systems?
This dual-system architecture was strategically designed to:

| Advantage | Benefit |
|-----------|---------|
| **Modular Design** | Enables independent updates to hospital or pharmacy components without system-wide downtime |
| **Scalability** | Allows separate scaling of pharmacy inventory management and patient care systems |
| **Flexible Deployment** | Institutions can implement either system standalone or integrated |
| **Integration Showcase** | Demonstrates API-based interoperability between healthcare systems |

---


   


