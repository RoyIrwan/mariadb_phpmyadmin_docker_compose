# MariaDB and PHPMyAdmin Docker Compose

## Images
1. [mariadb:latest](https://hub.docker.com/_/mariadb)
2. [phpmyadmin:fpm-alpine](https://hub.docker.com/_/phpmyadmin)
3. [nginx:stable-alpine-slim](https://hub.docker.com/_/nginx)

Semua menggunakan *Docker Official Image*. 
Kenapa phpmyadmin dan nginx menggunakan versi alpine? Karena distro alpine sangan ringan dan *size* yang sangat kecil.

## Cara menjalankan
Jalankan perintah docker compose seperti berikut:

    docker compose up -d
