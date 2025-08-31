# Panduan 

Ini adalah skema docker compose yang bisa digunakan untuk menjalankan laravel. Beberapa program yang digunakan adalah:
- Apache
- PHP 8
- Laravel versi 12
- MySQL 8.0

# Cara Instalasi
1. Pastikan sudah mengintal aplikasi docker dan docker-compose.
2. Download atau clone repository ini.
3. Tempatkan isi folder hasil cloning pada root folder aplikasi Laravel.
4. Pastikan nama database, username, dan password pada file .env & docker-compose.yml sama persis.
5. Buka terminal dan jalan perintah berikut:
   ```json docker compose up -d ```
6. Setelah container berjalan, buka browser dan akses http:localhost:8080 untuk membuka aplikasi dan http:localhost:8081 untuk membuka phpmyadmin.
