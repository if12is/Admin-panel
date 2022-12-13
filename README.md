```composer install  {composer update --ignore-platform-reqs }
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan db:seed
npm install
npm run dev
php artisan serve```
