## Laravel Ecommerce

Laravel Ecommerce is an open source ecommerce platform management system using laravel

## Packages Used

- composer require barryvdh/laravel-debugbar --dev
- Laravel ide helper
        1. composer require --dev barryvdh/laravel-ide-helper
        2. php artisan vendor:publish --provider="Barryvdh\LaravelIdeHelper\IdeHelperServiceProvider" --tag=config
            2.1 configure the file of config/ide-helper.php
                2.1.1. 'include_fluent' => true,
                2.1.2. 'include_helpers' => true,
        3. php artisan ide-helper:generate

## Installation Instructions

-Clone the repo.
-Run 'composer install'
-Run 'cp .env.example .env' 
-Run 'php artisan migrate --seed'

## Contribution Guideline

-Fork the repo.
-Clone the repo locally.
-Run 'git checkout dev'
-Create a new local branch
-Work on your local branch
-push to remote
-when work is tested, done or ready, push to remote
-Merge to dev

## License

The LLC Ecommerce is open-source software licensed under the [MIT license](https://opensource.org/licenses/MIT).
