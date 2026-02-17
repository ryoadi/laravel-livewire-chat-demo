# Laravel Livewire Realtime Chat App
A simple chat app, built with Laravel Livewire as it's core stack, showcasing ability to build a realtime chat app without relying on a frontend frameworks.

## Installation

### Prerequisites
- **PHP 8.4** or higher
- **Node.js 18** or higher
- **Composer**
- A database (SQLite, MySQL, PostgreSQL, etc.)

### Steps

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd laravel-livewire-chat-demo
   ```

2. **Install PHP dependencies**
   ```bash
   composer install
   ```

3. **Install Node dependencies**
   ```bash
   npm install
   ```

4. **Set up environment configuration**
   ```bash
   cp .env.example .env
   ```
   Edit `.env` and configure your database connection.

5. **Generate application key**
   ```bash
   php artisan key:generate
   ```

6. **Run database migrations**
   ```bash
   php artisan migrate
   ```

7. **Seed the database (optional)**
   ```bash
   php artisan db:seed
   ```

8. **Build assets**
   ```bash
   npm run build
   ```

9. **Start development servers**

   ```bash
   composer dev
   ```

10. **Access the application**
    Open your browser and navigate to `http://localhost:8000`

## Features
- Add, edit, delete message
- Realtime message update
- Room creation, room member management
- Direct (1 on 1) room
- Group room (multiple users)

## Tech stack
- PHP 8.4
- Laravel 12
- Livewire 3
- Laravel Folio
- Laravel Reverb
- Flux UI 2
- Tailwind 4
- PestPHP 4
- Laravel Pint
- Larastan/PHPstan
- Laravel Boost

Primary composer dependencies are listed in [composer.json](composer.json).

## Architecture, design patterns & best practices
- Action pattern
- UI - Single-file components
- File path based routing
- Unit testing
- Feature testing
- Laravel code standard

## AI
AI were used on the development for:

- Writing implementation details
- Generating tests
- Debugging issues

All AI suggestions were reviewed and edited by the developer. Tests and static analysis were used to validate the changes.

## Files & places to look
1. [Actions](app/Actions)
2. [Models](app/Models)
3. [Policies](app/Models/Policies)
4. [Migrations](database/migrations)
5. [Web pages](resources/views/pages)
6. [Livewire components](resources/views/livewire)
7. [Tests](tests/Unit)
