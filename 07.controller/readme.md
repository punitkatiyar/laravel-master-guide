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
