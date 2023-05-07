# Laravel Route

- Route::get($uri, $callback);
- Route::post($uri, $callback);
- Route::put($uri, $callback);
- Route::patch($uri, $callback);
- Route::delete($uri, $callback);
- Route::options($uri, $callback);



```
<?php
use Illuminate\Support\Facades\Route;
use App\Http\Controllers\User;
use App\Http\Controllers\admin;
Route::get('/', function () {
    return view('welcome');
});
Route::get('/test', function () {
    echo "<h1>This is Developer Page</h1>";
});
Route::get('/blog', function () {
    return view('blog');
});
Route::get('/blog/{id}', function ($id) {
    echo $id;
    return view('blog');
});
////////////////////////////////////////////////////////////////
// blade template
///////////////////////////////////////////////////////////////
// Route::get('/template', function () {
//     return view('template',array('name'=>"Punit"));
// });
Route::get('/template/{admin?}', function ($admin=null) {
    return view('template',array('data'=>array('name'=>"punit",'email'=>'punit@techunitbook.com'),'msg'=>'Welcome User'));
});
// blog routes
Route::view('page','page');
Route::view('post','post');
// component 
Route::get('/page', function () {
    return view('page');
});
// form
Route::get('/form', function () {
    return view('form');
});
// call the router
Route::post('/formSubmit',[User::class, 'index']);
Route::get('admin/{id?}',[Admin::class, 'index']);
```
