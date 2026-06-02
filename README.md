# 💰 Toko Amien Expense Tracker

A clean and modern personal expense tracker built for **Toko Amien**.

![Dashboard Preview](screenshots/01-dashboard.png)

## ✨ Features

- Dashboard with monthly summary & trend chart
- Add Income & Expense transactions
- View all transactions with pagination
- Delete transactions
- Dark mode + responsive design
- Clean & simple user interface

## 📸 Screenshots

| Dashboard | Add Transaction | All Transactions |
|-----------|-----------------|------------------|
| ![Dashboard](screenshot/dash.png) | ![Add](screenshot/transaction.png) | ![All](screenshot/total.png) |

🛠️ Tech Stack

Laravel 11
Tailwind CSS + Alpine.js
MySQL
Chart.js

## 🚀 How To Run

```bash
cp .env.example .env
composer install
npm install && npm run build
php artisan key:generate
php artisan migrate
php artisan serve
Visit: http://127.0.0.1:8000

