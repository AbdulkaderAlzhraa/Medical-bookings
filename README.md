# 🏥 Medical Appointment Booking System (Laravel + Flutter)

A full-stack project designed to **simplify the process of booking medical appointments in clinics**.  
It consists of a **mobile application (Flutter)** for patients and doctors, and a **web admin dashboard (Laravel)** for system management.  

The system serves three types of users:  
- 👨‍⚕️ **Doctor**: Manage weekly schedules and patient bookings.  
- 🧑‍🤝‍🧑 **Patient**: Easily book available appointments via the mobile app.  
- 🛠️ **Admin**: Manage the system through a dedicated web dashboard.

---

## 🚀 Features
- 📅 Weekly schedule system for doctors to define available time slots.  
- 🧾 Simple and effective electronic appointment booking for patients.  
- 👨‍⚕️ Doctors can approve or reject bookings.  
- 🛠️ Admin dashboard to manage doctors, patients, and appointments.  
- 🔔 Notifications for appointment confirmations and reminders.  
- 📊 Reports and statistics for tracking bookings and activity.  

---

## 🛠️ Requirements
- **PHP** >= 8.1  
- **Composer**  
- **Laravel** 10.x  
- **MySQL**  
- **Node.js & NPM**  
- **Flutter SDK**  

---

## ⚡ Installation & Run

### 1️⃣ Run Backend (Laravel)
```bash
git clone https://github.com/username/medical-appointment-system.git
cd medical-appointment-system/backend

composer install
npm install && npm run dev
cp .env.example .env
php artisan key:generate
php artisan migrate --seed
php artisan serve
