
## laravel breeze

composer require laravel/breeze --dev

php artisan breeze:install
 
npm install
npm run dev
php artisan migrate


## laravel Middleware 

### set 1
php artisan make:middleware AdminMiddleware

### set 2
app\Http\Kernel.php

- Add custome middleware

### set 3
routes\web.php

-make view with middleware 


### set 4
app\Providers\RouteServiceProvider.php

- create custome url base on user 

### set 5
app\Http\Controllers\Auth

- add user type base redirection form needed funation 



