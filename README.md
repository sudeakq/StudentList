# Student Management System
This project is a simple Student Management System that allows you to perform CRUD (Create, Read, Update, Delete) operations using Vite for the frontend with React, and PHP Laravel for the backend.
This project demonstrates a simple CRUD application for managing student data. It includes a frontend built with Vite and React, and a backend built with PHP Laravel.

## Features
Add a new student
View a list of students
Update student details
Delete a student
Prerequisites
Before you begin, ensure you have met the following requirements:


Node.js and npm installed on your machine
PHP and Composer installed on your machine
MySQL or any other database server installed and running
# Installation
### Backend (Laravel)
Clone the repository:

git clone https://github.com/your-username/student-management-system.git
cd student-management-system/backend
Install PHP dependencies:

composer install
Set up your environment variables by copying the .env.example file to .env and update the database configuration:


cp .env.example .env
Generate the application key:


php artisan key:generate
Run the database migrations:


php artisan migrate
Start the Laravel development server:


php artisan serve
Frontend (Vite + React)
Navigate to the frontend directory:


cd ../lbs-frontend
Install JavaScript dependencies:


npm install
Start the Vite development server:


npm run dev


### Usage
Open your browser and navigate to the frontend URL provided by Vite (e.g., http://localhost:3000).
Use the interface to add, view, update, and delete student records.


### API Endpoints
GET /api/student - Retrieve a list of students
POST /api/student - Add a new student
PUT /api/student/{id} - Update an existing student
DELETE /api/student/{id} - Delete a student


### Contributing
To contribute to this project, please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes.
Commit your changes (git commit -m 'Add some feature').
Push to the branch (git push origin feature-branch).
Create a new Pull Request.
