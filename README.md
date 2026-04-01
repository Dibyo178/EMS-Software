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
