Prasyarat: (PHP 8.x, Composer, Node.js, MySQL).

Langkah Backend:
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve

Langkah Frontend:
npm install
npm run dev (dengan konfigurasi proxy ke port Laravel).