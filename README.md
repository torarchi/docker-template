# docker-template

собираем контейнеры
`docker-compose up --build -d`

командная строка
`docker-compose exec php-cli bash` or
`docker-compose exec php-fpm bash`

создаем проект
`composer create-project laravel/laravel`

меняем директории
`mv laravel/* ./`
`mv laravel/.* ./`

командная строка
`docker-compose exec php-cli bash` or
`docker-compose exec php-fpm bash`

решаем проблему с правами
`sudo chmod 777 -R storage/`

все команды `php artisan ...` через
`docker-compose exec php-cli bash` or
`docker-compose exec php-fpm bash`




