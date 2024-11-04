## About
API-сервер.

## Установка
```bash
cp .env.example .env
docker-compose up -d
composer install
php artisan key:generate
php artisan storage:link
php artisan migrate
```

## Swagger

php artisan l5-swagger:generate
Документация по http://your-app-url/docs
