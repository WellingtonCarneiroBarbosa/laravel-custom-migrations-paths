# laravel-custom-migrations-paths
Use custom migrations paths instead of having a single file to your all migrations to your Laravel project

# Instalation
1. Install the package
`composer require wellingtoncarneirobarbosa/laravel-custom-migrations-paths`

2. Publish the configs
`php artisan vendor:publish --tag=custom-migrations-paths`

You're done.


## How to use?
Just add your custom migrations paths to the configuration file config/custom_migrations.php
If you are using the default path database/migrations you don't need do nothing.

This package supports: database/migrations/users/create_users_table.php
This package does not supports: database/migrations/users/create/create_users.php (I wanna add this later)
