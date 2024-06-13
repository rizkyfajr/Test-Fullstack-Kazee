# Test Fullstack Kazee

This repository contains the code for the Test Fullstack project at Kazee. It is a fullstack application built with Laravel.

## Stacks
 - Laravel 11
 - MySQL
 

## Installation

1. Clone the repository:

   git clone https://github.com/rizkyfajr/Test-Fullstack-Kazee.git


2. Install the dependencies:

   composer install
   npm install

3. Copy the .env.example file and rename it to .env. Update the .env file with your database configuration:

    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3307
    DB_DATABASE=testing-app
    DB_USERNAME=root
    DB_PASSWORD=

4. Generate the application key:
    php artisan key:generate

5. Run the database migrations and seed the database:
    php artisan migrate --seed

6. Compile the assets:

   npm run dev

8. Start the development serve
   
    php artisan serve

9. Open your browser and visit http://localhost:8000 to see the application.

10. Username & Password
    email => test@example.com,
    password => admin123
