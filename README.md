# Hospital Management System

This repository contains a Hospital Management System developed using PHP, JavaScript, CSS, HTML, and SQL. The application provides a comprehensive solution for managing various aspects of a hospital, including patient records, appointments, doctors, and more.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Database Setup](#database-setup)
- [How to Use](#how-to-use)
- [Contributing](#contributing)
- [License](#license)

## Features

- User-friendly interface for easy navigation.
- Patient registration and management.
- Doctor information and availability tracking.
- Appointment scheduling and management.
- Prescription and medical record management.
- Billing and invoicing for services.
- Staff management with roles and permissions.
- Secure authentication and access control.
- Database integration with SQL for data storage.

## Installation

To use the Hospital Management System, follow the steps below:

1. Clone the repository using Git:

   ```bash
   git clone https://github.com/thejanmejaysinghh/hospital-management-system.git
   ```

2. Upload the contents to your web server or set up a local development environment like XAMPP.

## Database Setup

1. Create a new MySQL database using the following command or through a database management tool like phpMyAdmin:

   ```sql
   CREATE DATABASE hospital_management;
   ```

2. Import the database schema from the `database/hospital_management.sql` file into your newly created database. This will create the necessary tables.

3. Update the database configuration in `config/db.php` with your database credentials:

   ```php
   <?php
   // Database configuration
   define('DB_SERVER', 'your_database_server');
   define('DB_USERNAME', 'your_database_username');
   define('DB_PASSWORD', 'your_database_password');
   define('DB_NAME', 'hospital_management');
   ?>
   ```

## How to Use

1. After setting up the repository and database, access the Hospital Management System through your web browser.

2. You will be presented with the login screen.

3. Enter your username and password to log in to the system.

4. Once logged in, you will be directed to the dashboard, where you can access various modules like patient management, appointment scheduling, and more.

5. Use the navigation menu to explore different functionalities and manage hospital operations efficiently.

## Contributing

Contributions to this Hospital Management System are welcome. If you find any issues or want to enhance the functionality, feel free to create a pull request.

To contribute to this project, follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push the changes to your fork.
5. Create a pull request to the main repository.

## License

This Hospital Management System is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

Feel free to use this Hospital Management System to streamline hospital operations and improve patient care. If you have any questions or feedback, you can reach out to me via GitHub. Happy managing! 😄
