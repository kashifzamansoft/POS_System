<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p> <p align="center"> <a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a> <a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a> <a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a> <a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a> </p> ## About Laravel Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as: - [Simple, fast routing engine](https://laravel.com/docs/routing). - [Powerful dependency injection container](https://laravel.com/docs/container). - Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage. - Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent). - Database agnostic [schema migrations](https://laravel.com/docs/migrations). - [Robust background job processing](https://laravel.com/docs/queues). - [Real-time event broadcasting](https://laravel.com/docs/broadcasting). Laravel is accessible, powerful, and provides tools required for large, robust applications. ## Learning Laravel Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework. You may also try the [Laravel Bootcamp](https://bootcamp.laravel.com), where you will be guided through building a modern Laravel application from scratch. If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains thousands of video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library. ## Laravel Sponsors We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the [Laravel Partners program](https://partners.laravel.com). ### Premium Partners - **[Vehikl](https://vehikl.com/)** - **[Tighten Co.](https://tighten.co)** - **[WebReinvent](https://webreinvent.com/)** - **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)** - **[64 Robots](https://64robots.com)** - **[Curotec](https://www.curotec.com/services/technologies/laravel/)** - **[Cyber-Duck](https://cyber-duck.co.uk)** - **[DevSquad](https://devsquad.com/hire-laravel-developers)** - **[Jump24](https://jump24.co.uk)** - **[Redberry](https://redberry.international/laravel/)** - **[Active Logic](https://activelogic.com)** - **[byte5](https://byte5.de)** - **[OP.GG](https://op.gg)** ## Contributing Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions). ## Code of Conduct In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct). ## Security Vulnerabilities If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed. ## License The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

# POS System

This project is a **Point of Sale (POS) System** built using Laravel. It allows businesses to handle sales, manage products, track inventory, and generate reports with ease. Designed for retail shops, restaurants, and businesses needing a modern POS solution.

---

## Features

- **Authentication**
  - User registration & login
  - Role-based access (Admin, Cashier, Manager)
- **Product Management**
  - Add, edit, and delete products
  - Manage categories and suppliers
- **Sales Management**
  - Create sales invoices
  - Real-time billing system
  - Discount and tax handling
- **Inventory Control**
  - Track stock levels automatically
  - Notifications for low stock items
- **Reports**
  - Daily, monthly, and custom reports
  - Export data for accounting
- **Responsive UI**
  - Mobile-friendly interface with Bootstrap & TailwindCSS

---

## Project Structure

```
POS_System/
│
├── app/                # Application core (Models, Controllers, Middleware)
├── bootstrap/          # Laravel bootstrap files
├── config/             # Configuration files
├── database/           # Migrations, seeders, and SQL schema
├── public/             # Public assets (index.php entry point)
├── resources/          # Blade templates, CSS, JS, views
├── routes/             # Application routes (web.php, api.php)
├── storage/            # Logs, cache, compiled templates
├── tests/              # PHPUnit tests
│
├── .env.example        # Environment configuration example
├── artisan             # Laravel CLI tool
├── composer.json       # Dependencies
├── package.json        # Frontend dependencies
├── tailwind.config.js  # TailwindCSS configuration
└── README.md           # Documentation
```

---

## Installation

Follow these steps to set up the project:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/kashifzamansoft/POS_System.git
   cd POS_System
   ```

2. **Install Dependencies**
   ```bash
   composer install
   npm install && npm run dev
   ```

3. **Environment Setup**
   - Copy `.env.example` to `.env`
   - Update database settings in `.env` file:
     ```
     DB_DATABASE=pos_system
     DB_USERNAME=root
     DB_PASSWORD=
     ```

4. **Generate App Key**
   ```bash
   php artisan key:generate
   ```

5. **Run Migrations**
   ```bash
   php artisan migrate --seed
   ```

6. **Start Development Server**
   ```bash
   php artisan serve
   ```

Visit: `http://127.0.0.1:8000`

---

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. It provides tools required for large, robust applications including:

- [Routing](https://laravel.com/docs/routing)
- [Dependency Injection](https://laravel.com/docs/container)
- [Eloquent ORM](https://laravel.com/docs/eloquent)
- [Migrations](https://laravel.com/docs/migrations)
- [Queues](https://laravel.com/docs/queues)
- [Broadcasting](https://laravel.com/docs/broadcasting)

---

## Contributing

Contributions are welcome!  
To contribute:

1. Fork the repository
2. Create a new branch (`feature/your-feature`)
3. Commit your changes
4. Push the branch
5. Create a Pull Request

---

## License

This project is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
