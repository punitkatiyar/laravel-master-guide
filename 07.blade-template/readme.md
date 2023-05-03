<img src="https://laravel.com/img/logomark.min.svg">

# Laravel Blade Template

- **Laravel Blade is a templating engine that is included with the Laravel PHP framework. It allows developers to create reusable views and templates for their web applications. Blade is a powerful tool that simplifies the process of building and maintaining web applications by providing a way to separate the application's logic from its presentation layer.**

- **Blade templates are written in plain PHP code and use a simple syntax that makes them easy to read and write. Blade templates use the .blade.php file extension, and are stored in the resources/views directory of a Laravel application.**

- **One of the key features of Blade is its support for template inheritance. This allows developers to create a base template that contains common elements such as a header and footer, and then extend that template to create new views that include specific content for each page.**

- **Blade also includes a number of other useful features, such as control structures (e.g. if/else statements, loops), variables, and includes, which make it easy to create dynamic views that respond to user input.**

## Blade template uses a basic HTML structure to display some dynamic content

```
<!-- resources/views/welcome.blade.php -->

<!DOCTYPE html>
<html>
<head>
    <title>{{ $title }}</title>
</head>
<body>
    <h1>Welcome to my website!</h1>
    <p>{{ $description }}</p>
    @if($show_button)
        <a href="{{ $button_link }}" class="button">{{ $button_text }}</a>
    @endif
</body>
</html>


```
## This controler File For Hold The data

```
// app/Http/Controllers/WelcomeController.php

namespace App\Http\Controllers;

use Illuminate\Http\Request;

class WelcomeController extends Controller
{
    public function index()
    {
        $data = [
            'title' => 'Welcome to my website',
            'description' => 'This is a demo of a Laravel Blade template',
            'show_button' => true,
            'button_link' => 'https://example.com',
            'button_text' => 'Click here to learn more',
        ];

        return view('welcome', $data);
    }
}

```

