###### To run the IS601MiniPRJ3-pt3 project:
1. git clone FAQ project
2. CD then run: composer install
3. cp .env.example to .env
4. run: php artisan key:generate
5. setup database (with sqlite or other https://laravel.com/docs/5.6/database)
6. run: php artisan migrate
7. run: phpunit
8. run: php artisan migrate:refresh --seed