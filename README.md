# Laravel React Survey App

A full-stack Survey application built using **Laravel** for the backend (API) and **React.js** for the frontend. This project allows users to register, log in, create surveys, collect responses, and manage survey data through a modern and user-friendly interface.

## 🚀 Features

- User Authentication (Register/Login)
- Survey creation and management
- Public survey sharing
- Collect survey responses
- Dashboard with charts and statistics
- Protected API routes using Sanctum
- Pagination and form validation

---

## 🛠️ Tech Stack

**Frontend:**

- React.js
- Tailwind CSS
- React Router
- Axios

**Backend:**

- Laravel
- Laravel Sanctum (Authentication)
- MySQL (or any preferred database)
- Laravel API Resource

---


2. Backend Setup (Laravel)

cd backend

# Install dependencies
composer install

# Create .env file
cp .env.example .env

# Generate app key
php artisan key:generate

# Set up your database credentials in the .env file

# Run migrations
php artisan migrate

# Start Laravel server
php artisan serve


3. Frontend Setup (React)

Open a new terminal window:

cd frontend

# Install dependencies
npm install

# Start React dev server
npm run dev

React frontend will typically run on http://localhost:5173.

🔐 Authentication
This project uses Laravel Sanctum for API authentication. Ensure that frontend requests include the correct XSRF-TOKEN for CSRF protection. The app uses Axios to handle this automatically via withCredentials: true.


📁 Project Structure

laravel-react-survey/
├── backend/        # Laravel API
└── frontend/       # React.js SPA


📌 To Do / Improvements

1. Email verification

2. Password reset functionality

3. Deployment guide

4. Admin dashboard with advanced analytics


📄 License
This project is open-source and available under the MIT License.
