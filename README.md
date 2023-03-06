# project-final-martin
CRM dgn Laravel - Vue JS
upload pertama

backend: laravel
frontend: vue js

Cara menjalankan backend laravel:
1. cd backend && composer install
2. cp .env.example .env (sesuai koneksi db pgsql)
3. php artisan key:generate
4. php artisan migrate
5. php artisan db:seed
6. php artisan server(localhost:8000)

jika migrate/seed gagal, bisa menggunakan backup file .tar di backend/database/dump

Cara menjalankan frontend vue js:
1. cd frontend && npm install
2. npm run dev
