# laravel Component

## Create A Component

> php artisan make:component Header

# Work Space

- app/view/Component/Header.php

```
<?php

namespace App\View\Components;

use Closure;
use Illuminate\Contracts\View\View;
use Illuminate\View\Component;

class Header extends Component
{
    /**
     * Create a new component instance.
     */
    public function __construct()
    {
        //
    }

    /**
     * Get the view / contents that represent the component.
     */
    public function render(): View|Closure|string
    {
        return view('components.header');
    }
}

```

- resources/view/components/header.blade.php

  ```
  <div>
    <!-- Simplicity is an acquired taste. - Katharine Gerould -->
</div>
  
  ```

# call the component

> < x-header >< /x-header >
