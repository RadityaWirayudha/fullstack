Prasyarat: (PHP 8.x, Composer, Node.js, MySQL).

Langkah Backend:
cp .env.example .env;
php artisan key:generate;
php artisan migrate;
php artisan serve;

Langkah Frontend:
npm install;
npm run dev (dengan konfigurasi proxy ke port Laravel).

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ba679a5b-22fd-4c9f-a728-f3360ae65146" />
