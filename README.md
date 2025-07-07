# Laravel Blog Project

This is a simple blog application built.
It features user authentication, post management (CRUD), and Bootstrap styling.

## Features

- User Registration & Login
- Authenticated Post Creation
- Bootstrap UI
- Protected Routes (middleware)

## Requirements

- PHP 7.4+
- Composer
- MySQL
- Node.js & NPM (optional for frontend assets)

## Setup Instructions

```bash
git clone https://github.com/Syed-Iras-Ali/blog-laravel.git
cd blog-laravel
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
