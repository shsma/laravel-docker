## Laravel-Docker plug-and-play

This is quick plug-and-play setup for your `Laravel-Docker` projects

Comes with:
- web-app: `Laravel/PHP-7.2`
- web-server: `Nginx:alpine`
- database: `Mysql-5.7.22`

## Installatioin
- `git clone git@github.com:shsma/laravel-docker.git`
- `cd laravel-docker-master`
- `docker-compose up -d`
- `docker-compose exec app composer install`
- `cp .env.exemple .env`
- `docker-compose exec app php artisan key:generate`

Now that all containers are up, we can add `project.local` to our `/etc/hosts` file

Boom! access `project.local` on your favorite browser

## Questions and Improvements

For any question or emprovement please send an e-mail Shady Smaoui [shady@veloxsolutions.ca](mailto:shady@veloxsolutions.ca).

## License

ShadySmaoui©2019 licensed under the [MIT license](https://opensource.org/licenses/MIT).
