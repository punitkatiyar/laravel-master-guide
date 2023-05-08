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

