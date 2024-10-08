Overview
This project is a web-based Attendance Management System that allows students and staff to log in, register, and manage attendance. The system is divided into two primary sections: Staff and Student, each with its own set of login and registration pages.

Features
Staff Section:

Staff can register, log in, and manage student attendance.
Pages: index.php, login.php, register.php, logout.php
Stylesheets: login.css, styles.css
Student Section:

Students can register, log in, and view attendance.
Pages: index.php, login.php, register.php, logout.php
Stylesheets: login.css, styles.css
Database
The project includes an SQL file named Attendence_database.sql which contains the structure for the attendance database. Make sure to import this SQL file into your database system to initialize the required tables.

File Structure
/attendance_management_system/
/staff/: Contains all PHP pages and stylesheets for staff login and attendance management.
/student/: Contains all PHP pages and stylesheets for student login and attendance management.
connection.php: Manages the connection to the database.
Setup Instructions
Download or clone the repository.
Set up a local server (e.g., XAMPP) and place the files in the htdocs directory.
Create a database in MySQL and import the Attendence_database.sql file.
Update the connection.php file with your database credentials.
Access the system via localhost in your browser.
