# 📝 Online Note App

A full-featured, responsive note-taking web application built with PHP, MySQL, HTML, CSS, and JavaScript. This app allows users to register, log in, and manage their personal notes securely.

## 🔧 Features

- User Registration and Authentication
- Create, Read, Update, and Delete (CRUD) Notes
- Responsive Design for Desktop and Mobile
- Secure Password Reset via Email
- User Profile Management (Username, Email, Password)
- Session Management with Logout Functionality

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript
- **Backend:** PHP
- **Database:** MySQL

## 🚀 Getting Started

### Prerequisites

- PHP 7.0 or higher
- MySQL Database
- Web Server (e.g., Apache, Nginx)

### Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/luckaty/online-note-app.git
   cd online-note-app
Set Up the Database:

Create a new MySQL database.

Import the provided SQL file to set up the necessary tables:


mysql -u your_username -p your_database_name < database.sql

Configure Database Connection:

Open connection.php and update the database credentials:

$host = 'localhost';
$username = 'your_username';
$password = 'your_password';
$database = 'your_database_name';
Start the Development Server:

If using PHP's built-in server:

php -S localhost:8000
Then, navigate to http://localhost:8000 in your web browser.

📁 Project Structure

online-note-app/
├── css/
│   └── styling.css
├── fonts/
├── js/
│   ├── javascript.js
│   ├── mynotes.js
│   └── profile.js
├── index.php
├── mainpageloggedin.php
├── login.php
├── signup.php
├── logout.php
├── profile.php
├── settings.php
├── forgot-password.php
├── resetpassword.php
├── storeresetpassword.php
├── activate.php
├── activatenewemail.php
├── remember.php
├── updateemail.php
├── updatepassword.php
├── updateusername.php
├── createnote.php
├── loadnotes.php
├── updatenote.php
├── deletenote.php
├── connection.php
├── README.md
└── image.png


📜 License
This project is licensed under the MIT License. Feel free to use, modify, and distribute it as per the license terms.

🙌 Contributions
Contributions are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.
