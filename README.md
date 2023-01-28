# startup_laravel_with_auth_ui

# startup_laravel_with_auth
<b>startup_laravel_with_auth</b>


-----------------------------------*** <b>Create project with bootstrap auth</b> ***-----------------------------------------------

<p>1.composer create-project --prefer-dist laravel/laravel laravel-crud</p>
<p>2.composer require laravel/ui --dev</p>
<p>3.php artisan ui bootstrap --auth</p>
<p>4.npm install</p>
<p>5.npm run dev</p>
<p>6.npm run build</p>
<p>7.php artisan migrate</p>

-----------------------------------*** <b>Laravel Project with theme AdminLTE</b> ***-----------------------------------------------

<p>1.composer create-project --prefer-dist laravel/laravel laravel-demo</p>
<p>2.php artisan migrate:fresh</p>
<p>3.composer require infyomlabs/laravel-ui-adminlte</p>
<p>4.php artisan ui adminlte --auth</p>
<p>5.npm install</p>
<p>6.npm install --save-dev laravel-mix</p>
<p>7.npm remove vite laravel-vite-plugin</p>
<p>8.rm vite.config.js</p>

<p>9.package.json=> 
     "scripts": {
            "dev": "mix",
            "build": "mix build" 
     }</p>

<p>10.npm i laravel-mix</p>
<p>11.npm run dev</p>
<p>12.npm run build</p>
<p>13.Php artisan serve</p>
