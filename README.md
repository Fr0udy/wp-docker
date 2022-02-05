# wp-docker
wordpress(php8.1,php-fpm)+nginx+mysql on Docker

# usage
```shell
cp .env.example .env
# 各自のDB情報に更新
vi .env

docker-compose build
docker-compose up -d
```
