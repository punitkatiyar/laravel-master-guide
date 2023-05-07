# Directory Structure

```
app/                    // contains application logic
├── Console/            // contains console commands
├── Exceptions/         // contains exception handlers
├── Http/               // contains controllers, middleware, and requests
│   ├── Controllers/    // contains web controllers
│   ├── Middleware/     // contains HTTP middleware
│   └── Requests/       // contains form request classes
├── Providers/          // contains service providers
└── ...                 // other application code

bootstrap/              // contains bootstrap files and cache
├── app.php             // loads application
├── autoload.php        // loads Composer autoloader
├── cache/              // contains cached files
└── ...

config/                 // contains configuration files
├── app.php             // application-level configuration
├── database.php        // database configuration
└── ...

database/               // contains database files and migrations
├── migrations/         // contains database migrations
└── seeds/              // contains database seeders

public/                 // contains public-facing files
├── index.php           // application entry point
├── css/                // contains CSS files
└── ...

resources/              // contains application resources
├── assets/             // contains raw assets
├── lang/               // contains language files
├── views/              // contains Blade templates
└── ...

routes/                 // contains route definitions
├── web.php             // web routes
├── api.php             // API routes
└── ...

storage/                // contains generated files
├── app/                // contains application-generated files
├── framework/          // contains framework-generated files
└── ...

tests/                  // contains automated tests
├── Feature/            // contains feature tests
├── Unit/               // contains unit tests
└── ...

```
