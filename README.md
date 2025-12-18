# Laravel Skeleton

A minimal Laravel skeleton with essential functionality to get you started quickly.

## Features

- ✨ Minimal setup with core Laravel functionality
- 🚀 Quick installation process
- 📦 Clean directory structure
- 🎨 Simple welcome page
- ⚙️ Basic configuration files

## Requirements

- PHP 8.2 or higher
- Composer

## Installation

1. Clone the repository:
```bash
git clone https://github.com/barateza/laravel-skeleton.git
cd laravel-skeleton
```

2. Install dependencies:
```bash
composer install
```

3. Set up environment configuration:
```bash
cp .env.example .env
php artisan key:generate
```

4. Run the application:
```bash
php artisan serve
```

5. Open your browser and visit `http://localhost:8000`

## Structure

```
├── app/                  # Application core
│   ├── Http/            # Controllers and middleware
│   ├── Models/          # Eloquent models
│   └── Providers/       # Service providers
├── bootstrap/           # Framework bootstrap
├── config/              # Configuration files
├── database/            # Database files
├── public/              # Web server root
├── resources/           # Views and assets
│   └── views/          # Blade templates
├── routes/              # Route definitions
│   ├── web.php         # Web routes
│   └── console.php     # Console routes
└── storage/             # Application storage
```

## Usage

### Web Routes

Define your web routes in `routes/web.php`:

```php
Route::get('/example', function () {
    return 'Hello World!';
});
```

### Creating Controllers

```bash
php artisan make:controller ExampleController
```

### Environment Configuration

Edit `.env` file to configure your application settings.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Feel free to submit a Pull Request.