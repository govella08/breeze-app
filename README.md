Do the following after cloning the project:
composer install
npm i

Create database

Then rename .env.example file to .env
change database name to reflect your database, change user name of your database and password
Then run:
php artisan migrate
php artisan serve
