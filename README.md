<p align="center">
<a target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo">
</a>
</p>


# The Veronique's Stack

***We Believe, Every Piece of Jewerly Tells a Radiant Story.***

VR is a boilerplate that ready-to-use for production.
The good news is, this project is build on top of [Laravel](https://laravel.com) — Laravel is a web application framework with expressive, elegant syntax. 

We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development.

## Motivation

The motivation behind making this project is to standardize and make it easier to create applications with complex features, by using this project we hope to get it done faster.

## Pre-requisite

To be able to run this project, several supporting tools are needed, such as:

- Web server : 
    - `xampp` 
    - `lampp` 
    - or `mampp`
- Core language : 
    - `php ^8.x`
- JavaScript runtime : 
    -   `Node Js`
- Package manager : 
    - `composer`

## Built-in Dependency & Scaffolding
- Authentication : 
    - `Laravel UI`
- Code styling :
    - `Laravel Pint`
- Checking health : 
    - `Spatie Laravel health`
- Good-looking user interface : 
    - `Tailiwndcss`
- Icon : 
    - `Feather icon` (for blade templating engine)

## Run development mode

1. Clone this project: `git clone https://github.com/wearevero/VR.git`

2. Open **double** `bash` in the VR directory: one to run node js the other to run composer engine.

3. Install all required php dependencies with the command `composer install --ignore-platform-req=ext-gd` and... wait for the apocalypse, just kidding.

4. On another `bash`, run the command `npm install --legacy-peer-deps` to install the dependencies related to the required assets.

5. Generate key `php artisan key:generate`

6. Make database

7. Copying environment example `cp .env.example .env`

8. Running migration `php artisan migrate`

9. Seed default data `php artisan db:seed`

10. Checking the health? `php artisan health:check`

11. Take a look on your browser at: `127.0.0.1:8000`

## Run the testing

For tinkering with testing related-thing, by default this poject is using [Pest php](https://pestphp.com/) library. 

For running testing, you can use this command: 
```php
php artisn test
```

## Code formatting
We use [Laravel Pint](https://laravel.com/docs/10.x/pint) package for making this code base to more human readability.
You can run with this command:
```php
./vendor/bin/pint
```

## Run for production
1. Install autoloader optimization `composer require --optimize-autoloader --ignore-platform-req=ext-gd`

2. Let's optimize it! `php artisan optimize` 


## Code of Conduct

Please review and abide our [Code of Conduct](./CODE_OF_CONDUCT.md).

## Security Vulnerabilities

If you discover a security vulnerability, please send an e-mail to me via [kridoveronique@gmail.com](mailto:kridoveronique@gmail.com). All security vulnerabilities will be promptly addressed.

## Maintainer

- [Krido](https://github.com/yuxxeun)

## License

VR is open-sourced software licensed under the [MIT License](./LICENSE).
