
# Install
	- composer install / update
    - duplicate file .env.example jadi .env 
    - php artisan key:generate
    - buat database pada phpmyadmin 
    - php artisan migrate
    - php artisan jwt-secret -> lalu copy paste pada file .env -> jwt-secret 
