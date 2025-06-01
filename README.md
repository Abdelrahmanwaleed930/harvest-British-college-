# Harvest

A Laravel-based web application built with modern PHP and Laravel ecosystem tools.

## Overview

Harvest is a modular Laravel application that leverages various powerful PHP packages and Laravel features to provide a robust web solution. The application is built using Laravel 10 and PHP 8.1+, with a focus on maintainability, scalability, and modern development practices.

## Key Features

- Modular Architecture using Nwidart Laravel Modules
- User Authentication and Authorization
- Social Media Integration
- Real-time Features with Pusher
- File Management with Intervention Image
- Calendar Integration
- Activity Logging
- Permission Management
- Translation Support
- Excel Import/Export
- Captcha Integration
- Livewire for Real-time UI Components

## Technical Stack

### Core Framework
- Laravel 10
- PHP 8.1+
- Laravel Sanctum for API Authentication
- Laravel Socialite for Social Authentication

### Frontend
- Livewire 3.5 for Real-time Components
- Laravel UI for Authentication Scaffolding
- Laravel Collective HTML for Form Management

### Modules & Packages
- Nwidart Laravel Modules for Modular Architecture
- Spatie Laravel Permission for Role Management
- Spatie Laravel Activity Log for User Actions
- Maatwebsite Excel for Spreadsheet Operations
- Anhskohbo No-Captcha for Security
- Tanmuhittin Laravel Google Translate for Multilingual Support
- Twilio SDK for SMS/Communication
- Pusher PHP Server for Real-time Features

## Project Structure

```
harvest/
├── app/                 # Core Laravel application code
├── Modules/             # Modular application code
├── config/              # Application configuration
├── database/            # Database migrations and seeds
├── public/              # Public assets and entry point
├── resources/           # Views, assets, and translations
├── routes/              # Application routes
├── storage/             # Application storage
└── tests/               # Application tests
```

## Installation

1. Clone the repository
2. Copy `.env.example` to `.env` and configure your environment
3. Run `composer install` to install PHP dependencies
4. Run `npm install` to install frontend dependencies
5. Generate application key: `php artisan key:generate`
6. Run database migrations: `php artisan migrate`
7. Start the development server: `php artisan serve`

## Environment Configuration

The project uses a `.env` file for configuration. Key environment variables include:
- Database connection settings
- Application URL
- Mail configuration
- API keys for third-party services
- Cache and session configuration

## Development

The project uses Laravel Sail for Docker-based development. You can start the development environment with:

```bash
./vendor/bin/sail up
```

## Testing

Run tests using:

```bash
./vendor/bin/sail artisan test
```

## Security

- Uses Laravel's built-in security features
- Implements CSRF protection
- Uses Laravel Sanctum for API authentication
- Implements rate limiting
- Uses secure password hashing

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details
