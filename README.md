# Laravel Starter

This project is a bare-bones Laravel 10 project that includes some additional boilerplate:

- NVM support
- Valet support
- Github workflows
- Laravel pint (PHP-CS-fixer)
- Larastan (PHP Static analysis)

## Requirements

- PHP 8.2
- MySQL 8.0
- NVM
- Valet or other PHP development server

## Installation

- Copy env file `cp .env.example .env`
- Install composer dependencies `composer install`
- Setup node `nvm install & nvm use`
- Install node models `npm install`
- Generate key `php artisan key:generate`
- Setup database credentials and other env variables in `.env`
- Migrate database `php artisan migrate`
- Build frontend `npm run build`

## Valet setup

- Setup the correct PHP version `valet use`
- Create a valet link `valet link`

## Frontend

### Development

Use `npm run dev` to start a vite dev server to build frontend assets.

### Production

Use `npm run build` to build the frontend for production.

## Testing

If you wish to use a different database for testing you can create a `.env.testing` file or edit the `phpunit.xml`
to change the test database.

- Use `php artisan test` to run PHP test suite.

## Coding standards

- Use `composer run lint` to run coding standards checks.
- Use `composer run fix` to fix any coding standard issues.
