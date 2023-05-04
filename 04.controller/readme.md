# Controller in Laravel

To create a controller in Laravel, you can use the **make:controller Artisan command**. This command will generate a new controller class in the **app/Http/Controllers** directory of your Laravel application.

<hr>

```
php artisan make:controller UserController
```
<hr>

You can also specify an optional --resource flag when creating a controller to generate a controller with the typical RESTful actions (index, create, store, show, edit, update, and destroy) already defined:

```
php artisan make:controller UserController --resource
```
<hr>

- This will create a UserController class that extends the ResourceController class provided by Laravel, which includes the typical RESTful actions as methods.

- Once you've created your controller, you can define routes that map to the methods of the controller using the Route:: facade in your routes/web.php file.

- For example, if you have a UserController with a show() method, you could define a route like this:

```
Route::get('/users/{id}', 'UserController@test');

```
## laravel 9 

```
Route::get('user/{id?}',[UserControler::class, 'test']);
```

