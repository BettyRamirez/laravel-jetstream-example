1. We created the project:

`laravel new <project name>`

2. Added Jetstream dependencies to the project:

`composer require laravel/jetstream`
https://github.com/BettyRamirez/laravel-jetstream-example/commit/57a3697ab6f0a5754426ffc868f4a669d30fb21e

3. Added Jetstream with Livewire views:

`php artisan jetstream:install livewire`
https://github.com/BettyRamirez/laravel-jetstream-example/commit/bd7f3571d5b1274395986013e50e968e55cc6c3f

4. Installed npm dependencies:

`npm run install`

5. Create database and configure in .env file:

6. Ran migrations:

`php artisan migrate`

7. run the php server:

`php artisan serve`
