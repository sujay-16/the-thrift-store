# 🛍️ The Thrift Store

A web-based thrift store application built using **PHP** and **MySQL**, allowing users to browse, buy, and manage second-hand products efficiently.

---

## 🚀 Features

* User authentication (login/signup)
* Browse products by category
* Add items to cart
* Product listing & management
* Order handling (basic)
* Responsive UI

---

## 🛠️ Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** PHP
* **Database:** MySQL
* **Server:** XAMPP / Apache

---

## 📁 Project Structure

```
the-thrift-store/
│
├── php/                # Backend logic
├── assets/             # CSS, JS, images
├── thrift images/      # Product images (ignored large files)
├── config/             # Database/config files
├── .gitignore
└── README.md
```

---

## ⚙️ Setup Instructions

### 1. Clone the repository

```
git clone https://github.com/sujay-16/the-thrift-store.git
cd the-thrift-store
```

---

### 2. Move project to XAMPP

Copy the project folder to:

```
/Applications/XAMPP/xamppfiles/htdocs/
```

---

### 3. Start server

* Open XAMPP
* Start **Apache** and **MySQL**

---

### 4. Setup Database

* Open **phpMyAdmin**
* Create a new database (e.g., `thrift_store`)
* Import the SQL file (if available)

---

### 5. Configure Database Connection

Update your config file (example):

```php
$host = "localhost";
$user = "root";
$password = "";
$database = "thrift_store";
```

---

### 6. Run the project

Open browser:

```
http://localhost/the-thrift-store
```

---

## ⚠️ Important Notes

* `.env`, logs, and large files are ignored using `.gitignore`
* Do NOT upload sensitive credentials
* Avoid committing large binary files

---

## 📌 Future Improvements

* Payment integration
* Admin dashboard
* Search & filtering
* API-based backend
* Deployment (AWS / VPS)

---

## 👨‍💻 Author

**Sujay R**
GitHub: https://github.com/sujay-16

---

## 📄 License

This project is for educational purposes. You can modify and use it freely.
