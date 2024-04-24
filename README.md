# Task Management System (ETMS)

## Overview
The Task Management System (ETMS) is a web application built using HTML, CSS, PHP, and MySQL database. It provides functionalities for task management, user registration, user login, leave management, and user roles (admin and regular user).

## Features
- **User Registration**: Allows users to create accounts with the system.
- **User Login**: Provides authentication for registered users to access the system.
- **Admin Panel**: Separate login for administrators to manage users and tasks.
- **Task Management**: Allows users to create, update, and delete tasks.
- **Leave Management**: Enables users to submit leave requests and view their leave status.
- **Responsive Design**: Designed with Bootstrap to ensure compatibility across devices.

## File Structure
- **index.php**: Landing page with options to log in or register.
- **delete.php**: Handles task deletion functionality.
- **leaveform.php**: Form for users to submit leave requests.
- **leavestatus.php**: Displays the status of leave requests for the logged-in user.
- **logout.php**: Logs out the current user from the system.
- **manage.php**: Admin panel for managing users and tasks.
- **register.php**: User registration form.
- **task.php**: Handles task-related functionalities.
- **usercreate.php**: Creates new users (for admin use).
- **updatestatus.php**: Updates the status of tasks.
- **userdashboard.php**: Dashboard for logged-in users displaying tasks and leave status.
- **userlogin.php**: Handles user authentication.

## Getting Started
1. Launch an Apache server using XAMPP.
2. Place the project files in the appropriate directory (e.g., htdocs).
3. Import the provided SQL database schema to set up the necessary tables.
4. Access the project through a web browser.

## Technologies Used
- HTML
- CSS
- PHP
- MySQL
- Bootstrap
