<img src="https://laravel.com/img/logomark.min.svg">

# Laravel Blade Template

- **Laravel Blade is a templating engine that is included with the Laravel PHP framework. It allows developers to create reusable views and templates for their web applications. Blade is a powerful tool that simplifies the process of building and maintaining web applications by providing a way to separate the application's logic from its presentation layer.**

- **Blade templates are written in plain PHP code and use a simple syntax that makes them easy to read and write. Blade templates use the .blade.php file extension, and are stored in the resources/views directory of a Laravel application.**

- **One of the key features of Blade is its support for template inheritance. This allows developers to create a base template that contains common elements such as a header and footer, and then extend that template to create new views that include specific content for each page.**

- **Blade also includes a number of other useful features, such as control structures (e.g. if/else statements, loops), variables, and includes, which make it easy to create dynamic views that respond to user input.**

# Data Binding

```
<?php
$data="Hello";
echo $data;   
?>

{{$data}}

```

# Control Statement

```
<?php
$data="Hello";
?>

@if($data=='Hello')
<h1>Welcome User</h1>
@elseif($data=='user')
<h1>Welcome Admin</h1>
@else
<h1>Hello Guest </h1>
@endif

```
# For Loop 

```
@for($i=0;$i<10;$i++)
<h2>{{$i}}</h2>
@endfor
```

# foreach loop

```
@foreach ($users as $user)
<h3>{{$user}}</h3>
    
@endforeach
```



```
@yield(title)
@section("title","Hello App");
```

