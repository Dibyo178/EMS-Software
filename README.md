# School Management System 🏫

A professional, high-performance School Management System built with **Laravel 12** and **Inertia.js (Vue.js 3)**. It provides a seamless, Single Page Application (SPA) experience for school administration, students, and staff.

---

## 🚀 Key Modules & Features

- **User Roles:** Admin, Teacher, Student, and Accountant.
- **Academic Management:** Classes, Sections, Subjects, sessions, and groups.
- **Attendance:** Student and Teacher daily attendance tracking.
- **Exam System:** Scheduling, Mark entry, Seat plans, and automated Results.
- **Finance:** Fee structures, Invoices, and Payment history.
- **Library & Transport:** Book borrowing records and Bus/Transport scheduling.
- **Payroll:** Staff salary structures and payroll generation.
- **Settings:** Global system configurations and branding.

---

## 🛠️ Tech Stack

- **Backend:** Laravel 12.x
- **Frontend:** Vue.js 3 + Inertia.js
- **UI Styling:** Tailwind CSS + Bootstrap 5 (CDN)
- **Database:** MySQL
- **Real-time:** Laravel Reverb / Pusher
- **Server:** XAMPP (Local) / cPanel (Production)

---

## 📥 Installation & Setup

### 1. Clone & Install
```bash
git clone [https://github.com/your-username/school-management.git](https://github.com/your-username/school-management.git)
cd school-management

# Install PHP dependencies (Bypass Xdebug if slow)
XDEBUG_MODE=off composer install

# Install JS dependencies
npm install
```

### 2. Environment Configuration
```bash
# Copy example environment file
cp .env.example .env

# Generate application key
php artisan key:generate
```
### Note: Open .env and set your database and app name:
```bash
APP_NAME="School Management"
VITE_APP_NAME="${APP_NAME}"

DB_DATABASE=your_database_name
DB_USERNAME=your_username
DB_PASSWORD=your_password

```
### 3. Database Migration & Assets
```bash
# Run migrations and seeders
php artisan migrate --seed

# Build frontend assets for production
npm run build

# Or run for development
npm run dev
```
## 📂 Project Structure Highlights

- app/Models/  
  All core Eloquent models (e.g., Attendance, Exam, Student, Teacher, Invoice).

- app/Http/Controllers/  
  Backend logic handling for all modules like ExamController and FeeController.

- resources/js/Pages/  
  Contains Vue.js components and Inertia.js pages for the frontend.

- database/migrations/  
  Database schema and table structures.

- routes/web.php  
  All application routes and server-side navigation.

