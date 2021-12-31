- PHP8・Laravel8・mysql・Nginx・docker・phpdebug3
- 参考ブログ記事
https://maasaablog.com/development/laravel/docker/

docker-compose up -d

http://localhost:8000/

docker exec -it app-dl bash
cd my-app

http://localhost:8580
php artisan migrate:status
php artisan migrate
php artisan migrate:rollback


2021-12-31 09:11:56

Line Login OK

