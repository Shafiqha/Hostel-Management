🏨 Hostel Management System
A complete Hostel Management System built using PHP & MySQL with a responsive Bootstrap 4 UI.
It provides a centralized platform for students, admins, and wardens to manage hostel rooms, bookings, and student information efficiently.

✨ Features
👨‍🎓 Student Panel

🔑 Secure Login & Registration

🏠 Apply for hostel room

📄 View booking details

🔔 Notifications for updates

👨‍💼 Admin Panel

🛏️ Manage Rooms (Add/Edit/Delete)

📚 Manage Courses

📋 Approve/Reject Student Applications

👥 Manage Students & User Logs

📊 Dashboard with live counters & charts

🛠️ Tech Stack

Frontend: Bootstrap 4, jQuery, Chart.js

Backend: PHP (v5.6–7.4 recommended)

Database: MySQL

Build Tools: Gulp (SCSS compilation, minification, live reload)

⚙️ Installation

Clone this repository:

git clone https://github.com/yourusername/hostel-management-system.git
cd hostel-management-system


Import the database:

Open phpMyAdmin

Create a database named hostelmsphp

Import the hostelmsphp.sql file

Update database credentials in:

includes/dbconn.php


Start a local PHP server:

php -S localhost:8000


Login credentials (default):

Admin → admin / Password@123

Student → Register through login page

📂 Project Structure
hostel-management-system/
│── admin/           # Admin panel files
│── assets/          # CSS, JS, Images
│── dist/            # Compiled assets
│── includes/        # Database connection & auth checks
│── student/         # Student dashboard
│── index.php        # Student login
│── package.json     # NPM dependencies
│── gulpfile.js      # Build automation
└── README.md        # Project documentation

📊 Dashboard Preview
Admin Dashboard
+-------------------------------------------+
| Registered Students | Total Rooms         |
| Booked Rooms        | Featured Courses    |
+-------------------------------------------+

Student Login Page

🚀 Future Enhancements

Online payment integration

Email/SMS notifications

Attendance & mess management

Multi-admin role support

📜 License

This project is licensed under the ISC License.
