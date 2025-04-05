# 👥 Employee Management Web Application

A role-based employee management system built using **PHP**, **MySQL**, and **XAMPP**. This application supports **Admin** and **Employee** portals with core features like project assignment, leave management, attendance tracking, and secure authentication — ideal for local deployment.

---

## 🚀 Features

### 🏠 Homepage
- Clean interface with:
  - `Home` button
  - `Login` button → expands into:
    - `Admin Login`
    - `Employee Login`

---

### 👨‍💼 Admin Panel

#### 🔐 Admin Login
- Email & password-based authentication (credentials stored in the database).

#### 📊 Dashboard
- **View All Employees**: See employee ID, name, and details.
- **Add Employee**:
  - Form to input employee details: name, surname, email, phone, joining date, salary, designation.
  - Auto-generated employee ID and default password (email = password).
- **Assign Project**:
  - Assign tasks to employees by ID with assigned date, deadline, and project title.
- **Manage Leave Requests**:
  - View submitted leaves.
  - Approve or decline requests in real-time.
- **Attendance Management**:
  - Mark daily attendance for employees.
  - View historical attendance data, sorted date-wise.
- **Logout**:
  - Confirmation prompt on logout.

---

### 👷‍♂️ Employee Panel

#### 🔐 Employee Login
- Email & password-based login.

#### 📊 Dashboard
- **Attendance Overview**: View personal attendance record (date-wise).
- **Leave Requests**:
  - See real-time status (Approved / Declined / Pending).
- **View Profile**:
  - Access personal profile (edit password only).
- **Assigned Projects**:
  - View assigned projects, deadlines, and submission details.
- **Apply for Leave**:
  - Dropdown to select leave type (e.g., Sick, Casual, etc.).
  - Start & End date selectors using calendar pickers.
  - Description box for reason.
  - Live updates post admin decision.
- **Logout**:
  - Confirmation before logging out.

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: PHP  
- **Database**: MySQL (phpMyAdmin)  
- **Server**: XAMPP (Apache + MySQL)

---

## ⚙️ Setup Instructions

1. **Download & Install XAMPP** from [apachefriends.org](https://www.apachefriends.org)
2. Start the **Apache** and **MySQL** modules from the XAMPP control panel.
3. Clone or move your project to the `htdocs` directory:
   ```bash
   C:\xampp\htdocs\your-project-folder\
   ```
4. Open **phpMyAdmin** at `http://localhost/phpmyadmin/`
5. Import the provided `.sql` file to create the database.
6. Visit the application at:
   ```bash
   http://localhost/your-project-folder/
   ```

---

## 📁 Project Structure

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
```

---

## 🙌 Contributing

Pull requests and suggestions are welcome! If you find a bug or have a feature request, feel free to open an issue.

---

## 📄 License

This project is for educational/demo purposes. You are free to use, modify, and enhance it as needed.

---

## 👤 Author

**Mriganka Ghosh**  
Developer & Project Author  

