# Employee Management Web Application

> Based on PHP and MySQL, this Employee Management System provides separate portals for Admin and Employee roles. It includes key features like project assignment, attendance tracking, leave management, and secure authentication — designed for local deployment via XAMPP.

---

## 🚀 Features

### 🏠 Homepage
- Simple UI with `Home` and `Login` buttons.
- Login expands into:
  - Admin Login
  - Employee Login

---

### 👨‍💼 Admin Panel

#### ✅ Admin Login
- Email & password-based authentication (credentials stored in the database).

#### 📊 Dashboard Includes:
- View all employee details (name, ID, etc.)
- Add Employee:
  - Name, surname, email, phone, joining date, salary, designation.
  - Auto-generated employee ID and default password (email as password).
- Assign Projects to employees by ID with:
  - Assigned date, deadline, and project name.
- Handle Leave Requests:
  - View, approve, or decline requests in real-time.
- Manage Attendance:
  - Mark attendance for employees.
  - View attendance history date-wise.
- Logout with confirmation prompt.

---

### 👷‍♂️ Employee Panel

#### ✅ Employee Login
- Email & password-based login.

#### 📊 Dashboard Includes:
- View personal attendance and leave request status (Approved / Declined / Pending).
- View Profile:
  - Edit password only.
  - Profile data is controlled by the admin.
- View Assigned Projects:
  - View assigned projects with deadlines and submission dates.
- View Attendance Records:
  - Personal attendance listed date-wise.
- Apply for Leave:
  - Dropdown to select leave type (e.g., Sick Leave, Casual Leave).
  - Start and end date selection using calendar pickers.
  - Description box to explain reason for leave.
  - Real-time update once approved/declined by admin.
- Logout with confirmation prompt.

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: PHP  
- **Database**: MySQL (via phpMyAdmin)  
- **Local Server**: XAMPP (Apache + MySQL)

---

## 🗂️ Setup Instructions

1. **Install XAMPP** from [https://www.apachefriends.org](https://www.apachefriends.org)
2. Start the **Apache** and **MySQL** modules.
3. Place your project folder inside the `htdocs` directory.
4. Open **phpMyAdmin** and import the database SQL file.
5. Visit `http://localhost/your-project-folder/` in your browser.

---

## 📁 Project Folder Structure

```plaintext
your-project-folder/
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
├── index.php
└── README.md
