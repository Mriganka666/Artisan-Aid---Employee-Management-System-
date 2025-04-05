# Employee Management Web Application

This is a PHP-based web application designed for managing employees, projects, attendance, and leave requests in a corporate environment. It supports two main roles: **Admin** and **Employee**.

## Features

### Homepage
- Simple interface with `Home` and `Login` buttons.
- Login expands into two options:
  - Admin Login
  - Employee Login

---

## Admin Panel

### Admin Login
- Secure login using email and password.
- Authenticated using data stored in MySQL.

### Admin Dashboard Functionalities
- **View Employees**: Display a list of all employees with their IDs and details.
- **Add Employee**: Admin can add a new employee with fields like:
  - Name, Surname, Email, Phone Number, Join Date, Salary, Designation, etc.
  - Employee ID is auto-generated.
  - Default password is set as the email.
- **Assign Projects**: Assign projects to employees by ID with:
  - Project Name, Assigned Date, Deadline.
- **Leave Requests**: View, approve or decline employee leave requests.
- **Attendance**:
  - Mark daily attendance.
  - View attendance history date-wise.
- **Logout**: Secure logout with confirmation.

---

## Employee Panel

### Employee Login
- Login using email and password credentials.
- Redirected to a personalized employee dashboard.

### Employee Dashboard Functionalities
- **Dashboard**: View current attendance and leave request status (Pending, Approved, Declined).
- **View Profile**: View personal details and update password.
- **View Projects**: See assigned projects, deadlines, and submission details.
- **View Attendance**: Track personal attendance records.
- **Apply Leave**:
  - Select type of leave from a dropdown.
  - Choose start and end dates using calendars.
  - Add a description/reason for leave.
  - Status updates in real-time based on admin action.
- **Logout**: Secure logout with confirmation.

---

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL (via phpMyAdmin)
- **Local Server**: XAMPP (Apache + MySQL)

---

## Setup Instructions

1. **Install XAMPP**
2. **Start Apache and MySQL**
3. **Clone this repository**
4. **Place project folder inside `htdocs` directory**
5. **Import the SQL file into phpMyAdmin to set up the database**
6. **Access the application via browser**  
   `http://localhost/your-project-folder/`

---

## Folder Structure

```plaintext
project-folder/
├── css/
├── js/
├── php/
│   ├── login.php
│   ├── admin_dashboard.php
│   ├── employee_dashboard.php
│   └── ...
├── includes/
├── db/
│   └── config.php
├── index.html / index.php
└── README.md
