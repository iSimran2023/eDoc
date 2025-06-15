eDoc - Online Doctor Appointment System

Project Overview

eDoc is a web-based application designed to streamline the process of booking medical appointments. It allows patients to schedule appointments with doctors, view doctor schedules, and manage their profiles. The system also includes an admin panel for managing doctors, appointments, and patient details. The project is built using HTML, CSS, PHP, and MySQL to provide an efficient and user-friendly experience for both patients and medical staff.

Features
Patient Features:
Register and log in to the system.
Browse doctors by specialty and view their weekly schedules.
Book appointments by selecting a suitable date and time.
View and manage appointment history.

Doctor Features:
View and manage appointment schedules.
Update personal profiles and availability.

Admin Features:
Manage doctor profiles, including specialties and credentials.
Oversee patient records and appointment schedules.
Confirm or cancel appointments.
Manage treatment facilities and system settings.

Responsive Design: Mobile-friendly interface using CSS.

Secure Database: MySQL database to store user, doctor, and appointment data securely.

Technologies Used
Frontend: HTML, CSS
Backend: PHP (for server-side logic and database interaction)
Database: MySQL (for storing user, doctor, and appointment data)
Server: Apache (via XAMPP or similar)

Installation Instructions
Follow these steps to set up the eDoc project on your local machine:
Prerequisites:
Install XAMPP or any web server with PHP and MySQL support.
Ensure Apache and MySQL services are running.

Setup:
Download the project source code (e.g., from a GitHub repository or provided zip file).
Extract the project folder to your web server's root directory (e.g., C:\xampp\htdocs\ for XAMPP).
Rename the extracted folder to edoc (optional for consistency).

Database Configuration:
Open a browser and navigate to http://localhost/phpmyadmin.
Create a new database named edoc.
Import the provided SQL file (e.g., DATABASE_edoc.sql or edoc.sql) located in the project’s root folder into the edoc database.

Database Connection:
Open the connection.php file in the project folder.
Update the database credentials (e.g., host, username, password, database name) to match your MySQL setup. 

Run the Application:
Start Apache and MySQL from the XAMPP Control Panel.
Open a browser and navigate to http://localhost/edoc/ to access the application.
For admin access, go to http://localhost/edoc/admin/ (use provided admin credentials, e.g., email: admin@edoc.com, password: 123).
