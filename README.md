# 📦 Invenstore: Backend System (Laravel API)

<p align="center">
  <img src="https://img.shields.io/badge/Backend-Laravel%2011-red?style=for-the-badge&logo=laravel" />
  <img src="https://img.shields.io/badge/Language-PHP%208.2-blue?style=for-the-badge&logo=php" />
  <img src="https://img.shields.io/badge/Frontend-Flutter%203.x-02569B?style=for-the-badge&logo=flutter" />
</p>

<p align="center">
  <strong>Robust Backend for Warehouse Management System</strong><br>
  Damascus University – Faculty of Informatics Engineering - Project 1<br>
  <em>Final Grade: 98%</em>
</p>

---

## 📖 Overview

**Invenstore Backend** is the core engine of the Warehouse Management System, built using **Laravel 11** to deliver a secure, scalable, and high-performance RESTful API.

It is designed to handle:
- Complex logistics operations
- Multi-user role management
- Real-time system updates
- Scalable and maintainable architecture

> 🎯 The project focuses on clean architecture and efficient API design for both Web and Mobile platforms.

---

## 🎯 Core Responsibilities (Backend Scope)

### 1. Inventory & Warehouse Engine
- Manage inventory with multiple states (valid, expired, damaged)
- Support multiple warehouses and distribution centers
- Automatic low-stock alerts

### 2. Logistics Operations System
- Warehouse-to-warehouse transfers
- Distribution center operations
- Full order lifecycle tracking

### 3. User & Access Control
- Authentication system (Login / Register / OTP)
- Role-Based Access Control (RBAC) using Spatie
- User banning/unbanning system

### 4. Reporting & Data Layer
- Orders and products reports
- Export reports to PDF and Excel
- Dashboard analytics endpoints

### 5. Real-time Communication
- Live updates via Pusher
- Notifications for:
  - Low stock
  - Expiration alerts
  - Order status updates

---

## ⚙️ Functional Modules (Implemented)

- ✅ User & Role Management  
- ✅ Warehouse Management  
- ✅ Distribution Centers Management  
- ✅ Products & Categories Management  
- ✅ Manufacturers & Suppliers Management  
- ✅ Orders & Transfers Management  
- ✅ Product Destruction Management  
- ✅ Reporting & Analytics  
- ✅ Real-time Notifications  
- ✅ Authentication & Verification (OTP + Email)  

---

## 🔒 Non-Functional Highlights

### Security
- Laravel Sanctum Authentication
- Spatie Permission (RBAC)
- Protection against common vulnerabilities (XSS, CSRF, SQL Injection)

### Performance
- Optimized database queries with Eloquent ORM
- Advanced filtering and pagination
- Efficient handling of large datasets

### Scalability
- Modular architecture design
- Ready for horizontal scaling
- Easy feature extension without major refactoring

### Maintainability
- Clean and structured codebase
- Separation of Concerns
- Organized layers (Controllers, Services, Repositories)

---

## 📄 Documentation

- For a detailed explanation of the system design, architecture, and requirements: 📂 [Project Report](./report%20of%20project%201%20-%20final.pdf)


- Postman Collection: [Dentila.postman_collection.json](WMS.postman_collection.json)

---

## 🏗️ Backend Architecture

```bash
app/
├── Http/
│   ├── Controllers/     # API Controllers
│   ├── Requests/        # Validation
│   └── Resources/       # API Transformers
│
├── Models/              # Eloquent Models
├── Services/            # Business Logic
├── Repositories/        # Data Access Layer
├── Events/              # Broadcasting Events
├── Notifications/       # System Notifications
├── Policies/            # Authorization Logic
│
routes/
├── api.php              # API Routes
│
database/
├── migrations/
├── seeders/
```

---

## 🛠️ Technologies Used

| Technology           | Version    | Purpose                 |
| -------------------- | ---------- | ----------------------- |
| Laravel              | 11         | Backend Framework       |
| PHP                  | 8.2+       | Core Language           |
| MySQL                | 5.7+ / 8.x | Database                |
| Laravel Sanctum      | -          | API Authentication      |
| Spatie Permission    | -          | Roles & Permissions     |
| Spatie Query Builder | -          | Advanced Filtering      |
| Pusher               | -          | Real-time Notifications |
| Eloquent ORM         | -          | Database ORM            |

---

## ⛓️ Runtime Environment Requirements

To run the project, you need:

- PHP >= 8.2  
- Composer >= 2.x  
- MySQL >= 5.7 or 8.x  
- Node.js >= 18 (optional for assets)  
- npm or yarn  

### Required PHP Extensions:
- OpenSSL  
- PDO  
- Mbstring  
- Tokenizer  
- XML  
- Ctype  
- JSON  
- BCMath  
- Fileinfo  

---

## 🚀 How to Run the Backend

### 1. Clone the Repository
```bash
git clone <repository-link>
cd invenstore-backend
```

### 2. Install Dependencies
```bash
composer install
```

### 3. Setup Environment File
```bash
cp .env.example .env
```

### 4. Generate Application Key
```bash
php artisan key:generate
```

### 5. Configure Database
Edit `.env` file:

```env
DB_DATABASE=your_database
DB_USERNAME=root
DB_PASSWORD=your_password
```

### 6. Run Migrations & Seeders
```bash
php artisan migrate --seed
```

### 7. Install Frontend Assets (Optional)
```bash
npm install
npm run build
```

### 8. Start Development Server
```bash
php artisan serve
```

---

## 🌐 API Base URL

```
http://127.0.0.1:8000/api
```

---

## 📊 Project Metrics

- 🎓 Final Grade: **98%**  
- 🔗 50+ REST API Endpoints  
- 🧩 15+ Modules Implemented  
- 💻 10,000+ Lines of Code  

---

## 👥 Development Team

- Mohamad Anas Albalah - Backend
- Mohammad Hosny Wees - Backend
- Leen Rabbou - Frontend
- Yaman Assi - Frontend

**Supervised by:** Eng. Najma Islam Majed Al-Tair  

---

## 🙏 Acknowledgment

Special thanks to:
- Damascus University  
- Faculty of Informatics Engineering  
- Eng. Najma Al-Tair  
- All instructors and mentors  

---

<div align="center">

Built with ❤️ using Laravel  
Invenstore Backend System – 2024

</div>
