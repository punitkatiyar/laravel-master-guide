# Controller in Laravel

To create a controller in Laravel, you can use the **make:controller Artisan command**. This command will generate a new controller class in the **app/Http/Controllers** directory of your Laravel application.

<hr>

```
php artisan make:controller UserController
```
```
<?php

namespace App\Http\Controllers;

use Illuminate\Http\Request;

class UserController extends Controller
{
    //
}
?>
```

<hr>

You can also specify an optional --resource flag when creating a controller to generate a controller with the typical RESTful actions (index, create, store, show, edit, update, and destroy) already defined:

```
php artisan make:controller UserController --resource
```

```
<?php

namespace App\Http\Controllers;

use Illuminate\Http\Request;

class AdminController extends Controller
{
    /**
     * Display a listing of the resource.
     *
     * @return \Illuminate\Http\Response
     */
    public function index()
    {
        //
    }

    /**
     * Show the form for creating a new resource.
     *
     * @return \Illuminate\Http\Response
     */
    public function create()
    {
        //
    }

    /**
     * Store a newly created resource in storage.
     *
     * @param  \Illuminate\Http\Request  $request
     * @return \Illuminate\Http\Response
     */
    public function store(Request $request)
    {
        //
    }

    /**
     * Display the specified resource.
     *
     * @param  int  $id
     * @return \Illuminate\Http\Response
     */
    public function show($id)
    {
        //
    }

    /**
     * Show the form for editing the specified resource.
     *
     * @param  int  $id
     * @return \Illuminate\Http\Response
     */
    public function edit($id)
    {
        //
    }

    /**
     * Update the specified resource in storage.
     *
     * @param  \Illuminate\Http\Request  $request
     * @param  int  $id
     * @return \Illuminate\Http\Response
     */
    public function update(Request $request, $id)
    {
        //
    }

    /**
     * Remove the specified resource from storage.
     *
     * @param  int  $id
     * @return \Illuminate\Http\Response
     */
    public function destroy($id)
    {
        //
    }
}

```


<hr>

- This will create a UserController class that extends the ResourceController class provided by Laravel, which includes the typical RESTful actions as methods.

- Once you've created your controller, you can define routes that map to the methods of the controller using the Route:: facade in your routes/web.php file.

- For example, if you have a UserController with a show() method, you could define a route like this:

## laravel 8

```
Route::get('/users/{id}', 'UserController@test');

```
## laravel 9 

```
Route::get('user/{id?}',[UserControler::class, 'test']);
```

