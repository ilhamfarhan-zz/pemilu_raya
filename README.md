# Pemilu Raya Web App

This is a web application built as a mean to held the yearly election for SMK Wikrama Student Council President.

## How to Setup The Environment

1. Create a MySQL database to store the application data
2. Create a .env file (just rename the `.env.example` as `.env`)
3. Change the `DB_DATABASE` field in .env file to your database name
4. If you would like to have only the db structure, open a terminal inside the project directory, run `php artisan migrate` command
5. If you would like to copy the entire data, import the `laravel_pemilu.sql` file into your MySQL database

## How to Run The Application

1. Open a terminal window inside the project directory
2. Run `php artisan serve` command
