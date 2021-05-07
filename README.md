## Laravel Octane test using Roadrunner on macOS (without Laravel Sail)

### Steps

1. `git clone git@github.com:Elandlord/octane-test.git`
2. `composer install`
3. `php artisan octane:install`
4. `composer require spiral/roadrunner` (when prompted for downloading RoadRunner, select "Y") This should install Roadrunner Application server.
5. `php artisan octane:start`
6. Access to your application at the URL: `http://127.0.0.1:8000`

