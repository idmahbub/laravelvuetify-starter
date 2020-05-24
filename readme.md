<h2>Laravel 7.0~ + VueJS + Vuetify</h2>
<p>NOTE: This uses hybrid routing. Inner pages is SPA using vue-router for smoother user experience. So if you are an advanced user of laravel and vueJS, then this one is for you. But if you are just learning laravel and vueJS, then this might not be for you.</p>
<h2>Installation</h2>
NOTE: Requirements need to be with laravel version 7.x or higher and PHP Version 7.3 or higher.

Clone repository git clone https://github.com/idmahbub/laravel-vuetify-starter.git
cp .env.example .env Then open .env file and put necessary credentials. Make sure to put proper APP_URL because it will be use in file manager module.
composer install
php artisan key:generate
php artisan migrate
php artisan db:seed
php artisan storage:link
npm install
npm run dev or watch or prod to re-generate the new build scripts for UI/UX
Default User: admin@gmail.com Pass: 12345678



<h3>Thanks To :</h3>
# [Darryl](https://github.com/darryldecode/laravel-starter-kit.git)
<p>With Laravel 7.x, Laramix 5.x, More improvement</p>