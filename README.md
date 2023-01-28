<p align="center"><a href="http://147.182.249.129/" target="_blank"><img src="./resources/js/inventory-management-logo/svg/logo-no-background.svg" width="200" alt="Inventory Management Logo"></a></p>

<br>
<p align="center">
<!-- <a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a> -->
</p>

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT). The project itself "Inventory Management" is not open-source (License TBD).

## Setup & Installation

### Requirements
* [PHP](https://www.php.net/downloads.php)
    * enable extensions: fileinfo, pdo-mysql
* [MySQL](https://www.mysql.com/downloads/)
* [Composer](https://getcomposer.org/download/)
* [Node.js](https://nodejs.org/en/download/)

### Installation
* Create an .env file based on the .env.example
* composer install
* composer update
* Install dependencies
    ```
    npm install
    ```
* Serve application
    ```
    php artisan serve
    ```
* Generate app key in browser (first time only)
* Create/migrate database (first time only - or if updates are made to database) - use a new terminal
    ```
    php artisan migrate
    ```
    * make sure that php.ini has the pdo_mysql extension uncommented -> prevent missing driver error
* Using Vite
    ```
    npm run dev
    ```
    * if localhost refuses to connect, update APP_URL in .env to http://127.0.0.1:8000/

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

You may also try the [Laravel Bootcamp](https://bootcamp.laravel.com), where you will be guided through building a modern Laravel application from scratch.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains over 2000 video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed. 