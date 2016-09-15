# Laravel Social Authentication

## Installation

- Must have a LAMP stack with PHP 5.5, PHP Mcrypt extension and Composer
- Clone this repository
- Run `composer install`
- Give write permissions (recursively) to web user on storage
- Run `cp example.env .env`
- Update DB and Social App configurations
- Create Database
- Run `php artisan migrate`

## Run Application using PHP Server

- Go to application public directory
- Execute `php -S localhost:1111`