<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Laravel Jetstream

1. Install laravel version 8
   ```sh
   composer create-project laravel/laravel example "8.*.*"
   ```
2. Install laravel jetstream
   ```sh
   composer require laravel/jetstream
   ```
3. Install jetstream livewire
   ```sh
   php artisan jetstream:install livewire
   ```
4. Install npm (node package manager)
   ```sh
   npm install && npm run dev
   ```
5. Jetstream vendor
   ```sh
   php artisan vendor:publish --tag=jetstream-views
   ```
6. First migration
   ```sh
   php artisan migrate
   ```


## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
