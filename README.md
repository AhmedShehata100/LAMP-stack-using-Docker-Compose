# 🚀 LAMP Stack using Docker Compose

This project sets up a simple **LAMP** (Linux, Apache, PHP) environment using **Docker Compose**.  
It is perfect for beginners who want to learn how to containerize a PHP application with a MySQL database.

---

## 📦 What’s Included?

- **PHP 7.4 + Apache** (`php:7.4-apache`)
- **MySQL** (`mysql:latest`)
- **Volumes** for code and database persistence
- **Port mapping** to access the web server via `http://localhost:8080`

---

## 🛠️ Project Structure
lamp-docker-compose/
│
├── docker-compose.yml
└── html/
└── index.php

---

## ▶️ How to Run

```bash
git clone https://github.com/AhmedShehata100/LAMP-stack-using-Docker-Compose.git
cd LAMP-stack-using-Docker-Compose
docker-compose up

Then open your browser at: http://localhost:8080

🧠 What I Learned
Basic Docker Compose syntax

Linking containers together (web & db)

Using volumes for persistence

Setting up a working LAMP stack in minutes

📌 Next Steps
Add PHPMyAdmin container

Use .env file for environment variables

Build a real PHP app on top of it

📬 Feedback
If you have any suggestions or tips, feel free to open an issue or connect with me on LinkedIn! https://www.linkedin.com/in/ahmed-shehata10/

