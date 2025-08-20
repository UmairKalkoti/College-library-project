📚 College Library Management System

A **Library Management System** built in **PHP** using **XAMPP**. This project is designed to help manage library operations such as maintaining books, tracking issued/returned books, and handling student records efficiently.

---

#🚀 Features

* 📖 Add, update, and delete books
* 👩‍🎓 Manage student records
* 🔑 User authentication (Admin login)
* 📊 Dashboard with library statistics
* 📅 Track issued & returned books
* 🔍 Search functionality for books and students

---

## 🛠️ Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** PHP
* **Database:** MySQL (via phpMyAdmin)
* **Server:** XAMPP (Apache, MySQL, PHP)

---

## ⚙️ Installation & Setup

1. **Install XAMPP**

   * Download and install [XAMPP](https://www.apachefriends.org/index.html).
   * Start **Apache** and **MySQL** from the XAMPP Control Panel.

2. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/library-management-php.git
   ```

   * Move the project folder into:

     ```
     C:\xampp\htdocs\
     ```

3. **Set Up Database**

   * Open **phpMyAdmin** by visiting [http://localhost/phpmyadmin](http://localhost/phpmyadmin).
   * Create a new database, e.g., `library_db`.
   * Import the provided SQL file (`library_db.sql`) from the project’s `database/` folder.

4. **Configure Database Connection**

   * Open `config.php` (or wherever your DB connection is set).
   * Update the database credentials if needed:

     ```php
     $host = "localhost";
     $user = "root";
     $password = "";
     $database = "library_db";
     ```

5. **Run the Project**

   * Visit [http://localhost/library-management-php](http://localhost/library-management-php) in your browser.

---

## 🔑 Default Credentials (if applicable)

* **Admin Username:** `admin`
* **Password:** `Test@123`

---
📂 Project Structure


library-management-php/
│-- config.php          # Database connection
│-- index.php           # Login page
│-- dashboard.php       # Admin dashboard
│-- books.php           # Book management
│-- students.php        # Student management
│-- issue_return.php    # Issue & return handling
│-- database/           # SQL file for setup
│-- assets/             # CSS, JS, images

