# Laravel Docker development starter project

Use this repo to start a Laravel development environment using Docker.
For now, I assume you have already installed Docker and Docker Compose.

The project is using Laravel 5.8.

To use this little project, do the following:

```
git clone https://github.com/superstoffer/laravel-docker.git <your-project-name>

cp .env.example .env

docker-compose up -d

docker-compose exec app php artisan key:generate

docker-compose exec app php artisan optimize
