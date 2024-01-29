#  Book Rental Library

## Exercise 4: 

Enhance the book rental library application by implementing various advanced features. Add support for different languages, send email notifications to users, utilize event-driven programming for various actions, and manage file storage for digital assets like book covers or digital copies.


## Installation

- Copy `.env.example` to `.env`
- Run `composer install`
- Run `php artisan key:generate --ansi`
- Run `php artisan migrate`
- Run `php artisan db:seed --class=GenresTableSeeder`
- Run `php artisan db:seed --class=BooksTableSeeder`

## Admin Account

To create an admin account run:

`php artisan db:seed --class=AdminSeeder`

## Run Application

Run `php artisan serve` or visit project `public` directory from the browser.

## Public files

To make public  files accessible run: `php artisan storage:link`
