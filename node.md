# Webapp quản lý sản phẩm TMT Innovative Sollution Co.,ltd 
    



### Install laravel modules 
- To install via Composer, run:
    composer require nwidart/laravel-modules
- Optionally, publish the package's configuration file by running:
    php artisan vendor:publish --provider="Nwidart\Modules\LaravelModulesServiceProvider"
- Autoloading 
    {
        "autoload": {
            "psr-4": {
            "App\\": "app/",
            "Database\\Factories\\": "database/factories/",
            "Database\\Seeders\\": "database/seeders/",
            "Modules\\": "Modules/"
            }
        }
    } 

    Tip: don't forget to run composer dump-autoload afterwards.

- Link tham khảo tài liệu 
    https://laravelmodules.com/docs/v10/introduction
