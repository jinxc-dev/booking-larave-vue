# booking-larave-vue
Booking website using Laravel+Vue

#For Local/Development
composer install
php artisan key:generate
php artisan storage:link
php artisan migrate [--seed]
For Production
# Running this on development environment will throw error so run below command only on production
composer install --no-dev --optimize-autoloader
php artisan key:generate
php artisan storage:link
php artisan migrate --force
