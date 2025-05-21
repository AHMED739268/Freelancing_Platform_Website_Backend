```markdown
# 💼 Freelancing Platform – Backend (Laravel + MySQL)


![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![RESTful API](https://img.shields.io/badge/API-RESTful-blue?style=for-the-badge)


> 🔧 The backend for a fully-featured Freelancing Platform, built using **Laravel** and **MySQL**, provides APIs for user authentication, project management, bids, messaging, and admin control.

---

## ✨ Features

- 🔐 JWT-based Authentication (Laravel Sanctum or Passport)
- 👤 User roles: Freelancer / Client / Admin
- 📋 Project creation, management & bidding
- 📨 Messaging system between users
- 📁 User profile setup with portfolios
- 🛡️ Role-based access control
- 📊 Admin panel for monitoring users and content

---

## 🧰 Tech Stack

- Laravel 10.x (MVC)
- MySQL
- RESTful API structure
- Laravel Sanctum / Passport
- API Resources & Controllers
- Laravel Migrations, Seeders, and Factories

---

## 📁 Folder Structure

freelancing-backend/
├── app/
│ ├── Http/
│ ├── Models/
│ ├── Providers/
├── database/
│ ├── migrations/
│ ├── seeders/
├── routes/
│ └── api.php
├── .env
└── artisan


---

## ⚙️ Setup & Run

### Prerequisites

- PHP 8+
- Composer
- MySQL
- Laravel CLI

### Installation

```bash
git clone https://github.com/YOUR_USERNAME/freelancing-backend.git
cd freelancing-backend

# Install dependencies
composer install

# Set up environment
cp .env.example .env
php artisan key:generate

# Configure DB in .env
DB_DATABASE=freelancing_db
DB_USERNAME=root
DB_PASSWORD=

# Run migrations
php artisan migrate --seed

# Start the server
php artisan serve

API will be available at: http://localhost:8000/api
🔐 API Endpoints Overview
Method	Endpoint	Description
POST	/register	Register user
POST	/login	Login user
GET	/projects	List all projects
POST	/projects	Create a project
POST	/projects/{id}/bid	Bid on a project
GET	/messages	List messages
POST	/messages	Send a message
📬 Contact

👤 Ahmed Mohamed Abdallah
📧 a.m.abdalla.amin@gmail.com
