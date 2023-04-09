<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

-   [Simple, fast routing engine](https://laravel.com/docs/routing).
-   [Powerful dependency injection container](https://laravel.com/docs/container).
-   Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
-   Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
-   Database agnostic [schema migrations](https://laravel.com/docs/migrations).
-   [Robust background job processing](https://laravel.com/docs/queues).
-   [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains over 1500 video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the Laravel [Patreon page](https://patreon.com/taylorotwell).

### Premium Partners

-   **[Vehikl](https://vehikl.com/)**
-   **[Tighten Co.](https://tighten.co)**
-   **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
-   **[64 Robots](https://64robots.com)**
-   **[Cubet Techno Labs](https://cubettech.com)**
-   **[Cyber-Duck](https://cyber-duck.co.uk)**
-   **[Many](https://www.many.co.uk)**
-   **[Webdock, Fast VPS Hosting](https://www.webdock.io/en)**
-   **[DevSquad](https://devsquad.com)**
-   **[Curotec](https://www.curotec.com/services/technologies/laravel/)**
-   **[OP.GG](https://op.gg)**
-   **[WebReinvent](https://webreinvent.com/?utm_source=laravel&utm_medium=github&utm_campaign=patreon-sponsors)**
-   **[Lendio](https://lendio.com)**

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

## Authors

-   [@jahidul2018](https://www.github.com/jahidul2018)

## 🚀 About Me

I'm a full stack developer...

My interests range from data science to machine learning.love to work as a web Developer with new technology. Currently, studying Applied statistics and Data Science at Jahangirnagar University. System Analysis is one of my favourites. Learning Project management methodology and Documentation (Technical, Analytical) help me a lot to understand Software Usability Support and Technical Support. And last but not least I am a nature lover like Albert Einstein and one of my favourite Quote is "Look deep into nature, and then you will understand everything better".

here is my linkedin profile:
https://www.linkedin.com/in/jahidulalammishuk/

## Acknowledgements

-   [ larainfo](https://larainfo.com)
-   [ larainfo](https://larainfo.com)
-   [ larainfo](https://larainfo.com)

# Project Title

Laravel NextJS Backend with Breeze API

## Demo

demo you are looking for :

-   [larainfo.com](https://larainfo.com/blogs/laravel-breeze-api-install-setup-authentication-with-nextjs/)
-   [dummy](https://www.laravelcode.com/)
-   [dummy](https://www.laravelcode.com/)
-   [dummy](https://www.laravelcode.com/)

## Data set

this a dummy data set

## create laravel project

So let's start from creating latest Laravel application.
<code>
composer create-project Laravel/laravel laravel-breeze-api  
</code>

## Setup your .env file

.env

<code>

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=database_name
DB_USERNAME=database_user_name
DB_PASSWORD=database_password</code>

## Install breeze

<code>composer require laravel/breeze --dev</code>

## Install breeze api

<code>php artisan breeze:install api</code>

<p>
After install breeze api, you can see .env file two url for backend and frontend. You can change url in production, for local leave it.
</p>
<p>
.env</p>
<code>

APP_URL=http://localhost:8000
FRONTEND_URL=http://localhost:3000</code>

run project and leave it.

<code>php artisan serve </code>

## Note: Open two terminal one for run laravel application & second to create nextjs project and run.

## Next js Frontend Setup For Breeze

Laravel Breeze authentication starter kit frontend in Next.js. All of the authentication boilerplate is already written for you - powered by Laravel Sanctum, allowing you to quickly begin pairing your beautiful Next.js frontend with a powerful Laravel backend.

You need to clone or download breeze-next

Clone breeze-next repository

run below command to clone repo. you can check repository link.

## git clone https://github.com/laravel/breeze-next.git

Install dependencies.

# for node js

npm install
or

# for yarn

yarn install

Copy env file

cp .env.example .env

.env

## you can change url in production.

NEXT_PUBLIC_BACKEND_URL=http://localhost:8000

## run next js project

<code> npm run dev </code>
next js run command

Nextjs register page

http://localhost:3000/register

nextjs sign up page

Nextjs login page

http://localhost:3000/login

nextjs login
