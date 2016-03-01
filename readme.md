## Laravel PHP Framework

[![Build Status](https://travis-ci.org/laravel/framework.svg)](https://travis-ci.org/laravel/framework)
[![Total Downloads](https://poser.pugx.org/laravel/framework/downloads.svg)](https://packagist.org/packages/laravel/framework)
[![Latest Stable Version](https://poser.pugx.org/laravel/framework/v/stable.svg)](https://packagist.org/packages/laravel/framework)
[![Latest Unstable Version](https://poser.pugx.org/laravel/framework/v/unstable.svg)](https://packagist.org/packages/laravel/framework)
[![License](https://poser.pugx.org/laravel/framework/license.svg)](https://packagist.org/packages/laravel/framework)

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable, creative experience to be truly fulfilling. Laravel attempts to take the pain out of development by easing common tasks used in the majority of web projects, such as authentication, routing, sessions, and caching.
Packages
## 

### Javascript

* [jewlofthelotus/SlickQuiz](https://github.com/jewlofthelotus/SlickQuiz) a jQuery plugin for creating pretty, dynamic quizzes.(with custom ability to save mark when the exam is completed);

### PHP
* [laracasts/flash](https://github.com/laracasts/flash) for easy notify user action(with custom styling);
* [frozennode/administrator](https://github.com/FrozenNode/Laravel-Administrator) for quick simple admin interface;


## Requirements and Environment
    * PHP 5.4+
	* Laravel 4.2+

## Installation

Recommended using [Homestead](http://laravel.com/docs/4.2/homestead) for development.

### 1. Clone the repo

    git clone https://github.com/dimitar032/LaravelQuiz

### 2. Composer install

    cd LaravelQuiz
    composer install
    
### 3. Database 

Adjust the database information in app/config/database.php, then: 

    php artisan migrate

Seed the database if you want: 

    php artisan db:seed

### 4. Info(for seeded database)

* Admin Account: ['email' => 'admin@admin.com', 'password' => 'admin']
* Teacher Account: ['email' => 'teacher@teacher.com', 'password' => 'teacher']
* Student Account: ['email' => 'student@student.com', 'password' => 'student']



## License

The Laravel framework is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)
