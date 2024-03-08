# MariaDB and PHPMyAdmin Docker Compose

## Images
1. mariadb:latest
2. phpmyadmin:fpm-alpine
3. nginx:stable-alpine-slim

Semua menggunakan *Docker Official Image*. 
Kenapa phpmyadmin dan nginx menggunakan versi alpine? Karena distro alpine sangan ringan dan *size* yang sangat kecil.

## Cara menjalankan
Jalankan perintah docker compose seperti berikut:

    docker compose up -d
