<pre>
  Windows PowerShell
Copyright (C) Microsoft Corporation. All rights reserved.

Install the latest PowerShell for new features and improvements! https://aka.ms/PSWindows

</pre>

## PS C:\> composer -v

<pre>
   ______
  / ____/___  ____ ___  ____  ____  ________  _____
 / /   / __ \/ __ `__ \/ __ \/ __ \/ ___/ _ \/ ___/
/ /___/ /_/ / / / / / / /_/ / /_/ (__  )  __/ /
\____/\____/_/ /_/ /_/ .___/\____/____/\___/_/
                    /_/
Composer version 2.5.8 2023-06-09 17:13:21

Usage:
  command [options] [arguments]

Options:
  -h, --help                     Display help for the given command. When no command is given display help for the list command
  -q, --quiet                    Do not output any message
  -V, --version                  Display this application version
      --ansi|--no-ansi           Force (or disable --no-ansi) ANSI output
  -n, --no-interaction           Do not ask any interactive question
      --profile                  Display timing and memory usage information
      --no-plugins               Whether to disable plugins.
      --no-scripts               Skips the execution of all scripts defined in composer.json file.
  -d, --working-dir=WORKING-DIR  If specified, use the given directory as working directory.
      --no-cache                 Prevent use of the cache
  -v|vv|vvv, --verbose           Increase the verbosity of messages: 1 for normal output, 2 for more verbose output and 3 for debug

Available commands:
  about                Shows a short information about Composer
  archive              Creates an archive of this composer package
  audit                Checks for security vulnerability advisories for installed packages
  browse               [home] Opens the package's repository URL or homepage in your browser
  bump                 Increases the lower limit of your composer.json requirements to the currently installed versions
  check-platform-reqs  Check that platform requirements are satisfied
  clear-cache          [clearcache|cc] Clears composer's internal package cache
  completion           Dump the shell completion script
  config               Sets config options
  create-project       Creates new project from a package into given directory
  depends              [why] Shows which packages cause the given package to be installed
  diagnose             Diagnoses the system to identify common errors
  dump-autoload        [dumpautoload] Dumps the autoloader
  exec                 Executes a vendored binary/script
  fund                 Discover how to help fund the maintenance of your dependencies
  global               Allows running commands in the global composer dir ($COMPOSER_HOME)
  help                 Display help for a command
  init                 Creates a basic composer.json file in current directory
  install              [i] Installs the project dependencies from the composer.lock file if present, or falls back on the composer.json
  licenses             Shows information about licenses of dependencies
  list                 List commands
  outdated             Shows a list of installed packages that have updates available, including their latest version
  prohibits            [why-not] Shows which packages prevent the given package from being installed
  reinstall            Uninstalls and reinstalls the given package names
  remove               Removes a package from the require or require-dev
  require              [r] Adds required packages to your composer.json and installs them
  run-script           [run] Runs the scripts defined in composer.json
  search               Searches for packages
  self-update          [selfupdate] Updates composer.phar to the latest version
  show                 [info] Shows information about packages
  status               Shows a list of locally modified packages
  suggests             Shows package suggestions
  update               [u|upgrade] Updates your dependencies to the latest version according to composer.json, and updates the composer.lock file
  validate             Validates a composer.json and composer.lock
</pre>

## PS C:\> composer global require laravel/installer

<pre>
Changed current directory to C:/Users/codew/AppData/Roaming/Composer
Info from https://repo.packagist.org: #StandWithUkraine
./composer.json has been created
Running composer update laravel/installer
Loading composer repositories with package information
Updating dependencies
Lock file operations: 11 installs, 0 updates, 0 removals
  - Locking laravel/installer (v4.5.0)
  - Locking psr/container (2.0.2)
  - Locking symfony/console (v6.3.0)
  - Locking symfony/deprecation-contracts (v3.3.0)
  - Locking symfony/polyfill-ctype (v1.27.0)
  - Locking symfony/polyfill-intl-grapheme (v1.27.0)
  - Locking symfony/polyfill-intl-normalizer (v1.27.0)
  - Locking symfony/polyfill-mbstring (v1.27.0)
  - Locking symfony/process (v6.3.0)
  - Locking symfony/service-contracts (v3.3.0)
  - Locking symfony/string (v6.3.0)
Writing lock file
Installing dependencies from lock file (including require-dev)
Package operations: 11 installs, 0 updates, 0 removals
  - Downloading symfony/process (v6.3.0)
  - Downloading symfony/polyfill-mbstring (v1.27.0)
  - Downloading symfony/polyfill-intl-normalizer (v1.27.0)
  - Downloading symfony/polyfill-intl-grapheme (v1.27.0)
  - Downloading symfony/polyfill-ctype (v1.27.0)
  - Downloading symfony/string (v6.3.0)
  - Downloading psr/container (2.0.2)
  - Downloading symfony/service-contracts (v3.3.0)
  - Downloading symfony/deprecation-contracts (v3.3.0)
  - Downloading symfony/console (v6.3.0)
  - Downloading laravel/installer (v4.5.0)
  - Installing symfony/process (v6.3.0): Extracting archive
  - Installing symfony/polyfill-mbstring (v1.27.0): Extracting archive
  - Installing symfony/polyfill-intl-normalizer (v1.27.0): Extracting archive
  - Installing symfony/polyfill-intl-grapheme (v1.27.0): Extracting archive
  - Installing symfony/polyfill-ctype (v1.27.0): Extracting archive
  - Installing symfony/string (v6.3.0): Extracting archive
  - Installing psr/container (2.0.2): Extracting archive
  - Installing symfony/service-contracts (v3.3.0): Extracting archive
  - Installing symfony/deprecation-contracts (v3.3.0): Extracting archive
  - Installing symfony/console (v6.3.0): Extracting archive
  - Installing laravel/installer (v4.5.0): Extracting archive
2 package suggestions were added by new dependencies, use `composer suggest` to see details.
Generating autoload files
9 packages you are using are looking for funding.
Use the `composer fund` command to find out more!
No security vulnerability advisories found
Using version ^4.5 for laravel/installer
PS C:\> laravel new techunitbook

   _                               _
  | |                             | |
  | |     __ _ _ __ __ ___   _____| |
  | |    / _` | '__/ _` \ \ / / _ \ |
  | |___| (_| | | | (_| |\ V /  __/ |
  |______\__,_|_|  \__,_| \_/ \___|_|

    Creating a "laravel/laravel" project at "./techunitbook"
    Installing laravel/laravel (v10.2.4)
  - Downloading laravel/laravel (v10.2.4)
      - Installing laravel/laravel (v10.2.4): Extracting archive
    Created project in C:\/techunitbook
> @php -r "file_exists('.env') || copy('.env.example', '.env');"
    Loading composer repositories with package information
    Updating dependencies
Lock file operations: 108 installs, 0 updates, 0 removals
  - Locking brick/math (0.11.0)
  - Locking dflydev/dot-access-data (v3.0.2)
  - Locking doctrine/inflector (2.0.8)
  - Locking doctrine/lexer (3.0.0)
  - Locking dragonmantank/cron-expression (v3.3.2)
  - Locking egulias/email-validator (4.0.1)
  - Locking fakerphp/faker (v1.23.0)
  - Locking filp/whoops (2.15.2)
  - Locking fruitcake/php-cors (v1.2.0)
  - Locking graham-campbell/result-type (v1.1.1)
  - Locking guzzlehttp/guzzle (7.7.0)
  - Locking guzzlehttp/promises (2.0.0)
  - Locking guzzlehttp/psr7 (2.5.0)
  - Locking guzzlehttp/uri-template (v1.0.1)
  - Locking hamcrest/hamcrest-php (v2.0.1)
  - Locking laravel/framework (v10.14.1)
  - Locking laravel/pint (v1.10.3)
  - Locking laravel/sail (v1.23.0)
  - Locking laravel/sanctum (v3.2.5)
  - Locking laravel/serializable-closure (v1.3.0)
  - Locking laravel/tinker (v2.8.1)
  - Locking league/commonmark (2.4.0)
  - Locking league/config (v1.2.0)
  - Locking league/flysystem (3.15.1)
  - Locking league/flysystem-local (3.15.0)
  - Locking league/mime-type-detection (1.11.0)
  - Locking mockery/mockery (1.6.2)
  - Locking monolog/monolog (3.4.0)
  - Locking myclabs/deep-copy (1.11.1)
  - Locking nesbot/carbon (2.67.0)
  - Locking nette/schema (v1.2.3)
  - Locking nette/utils (v4.0.0)
  - Locking nikic/php-parser (v4.16.0)
  - Locking nunomaduro/collision (v7.7.0)
  - Locking nunomaduro/termwind (v1.15.1)
  - Locking phar-io/manifest (2.0.3)
  - Locking phar-io/version (3.2.1)
  - Locking phpoption/phpoption (1.9.1)
  - Locking phpunit/php-code-coverage (10.1.2)
  - Locking phpunit/php-file-iterator (4.0.2)
  - Locking phpunit/php-invoker (4.0.0)
  - Locking phpunit/php-text-template (3.0.0)
  - Locking phpunit/php-timer (6.0.0)
  - Locking phpunit/phpunit (10.2.3)
  - Locking psr/container (2.0.2)
  - Locking psr/event-dispatcher (1.0.0)
  - Locking psr/http-client (1.0.2)
  - Locking psr/http-factory (1.0.2)
  - Locking psr/http-message (2.0)
  - Locking psr/log (3.0.0)
  - Locking psr/simple-cache (3.0.0)
  - Locking psy/psysh (v0.11.18)
  - Locking ralouphie/getallheaders (3.0.3)
  - Locking ramsey/collection (2.0.0)
  - Locking ramsey/uuid (4.7.4)
  - Locking sebastian/cli-parser (2.0.0)
  - Locking sebastian/code-unit (2.0.0)
  - Locking sebastian/code-unit-reverse-lookup (3.0.0)
  - Locking sebastian/comparator (5.0.0)
  - Locking sebastian/complexity (3.0.0)
  - Locking sebastian/diff (5.0.3)
  - Locking sebastian/environment (6.0.1)
  - Locking sebastian/exporter (5.0.0)
  - Locking sebastian/global-state (6.0.0)
  - Locking sebastian/lines-of-code (2.0.0)
  - Locking sebastian/object-enumerator (5.0.0)
  - Locking sebastian/object-reflector (3.0.0)
  - Locking sebastian/recursion-context (5.0.0)
  - Locking sebastian/type (4.0.0)
  - Locking sebastian/version (4.0.1)
  - Locking spatie/backtrace (1.5.3)
  - Locking spatie/flare-client-php (1.4.0)
  - Locking spatie/ignition (1.9.0)
  - Locking spatie/laravel-ignition (2.2.0)
  - Locking symfony/console (v6.3.0)
  - Locking symfony/css-selector (v6.3.0)
  - Locking symfony/deprecation-contracts (v3.3.0)
  - Locking symfony/error-handler (v6.3.0)
  - Locking symfony/event-dispatcher (v6.3.0)
  - Locking symfony/event-dispatcher-contracts (v3.3.0)
  - Locking symfony/finder (v6.3.0)
  - Locking symfony/http-foundation (v6.3.1)
  - Locking symfony/http-kernel (v6.3.1)
  - Locking symfony/mailer (v6.3.0)
  - Locking symfony/mime (v6.3.0)
  - Locking symfony/polyfill-ctype (v1.27.0)
  - Locking symfony/polyfill-intl-grapheme (v1.27.0)
  - Locking symfony/polyfill-intl-idn (v1.27.0)
  - Locking symfony/polyfill-intl-normalizer (v1.27.0)
  - Locking symfony/polyfill-mbstring (v1.27.0)
  - Locking symfony/polyfill-php72 (v1.27.0)
  - Locking symfony/polyfill-php80 (v1.27.0)
  - Locking symfony/polyfill-php83 (v1.27.0)
  - Locking symfony/polyfill-uuid (v1.27.0)
  - Locking symfony/process (v6.3.0)
  - Locking symfony/routing (v6.3.1)
  - Locking symfony/service-contracts (v3.3.0)
  - Locking symfony/string (v6.3.0)
  - Locking symfony/translation (v6.3.0)
  - Locking symfony/translation-contracts (v3.3.0)
  - Locking symfony/uid (v6.3.0)
  - Locking symfony/var-dumper (v6.3.1)
  - Locking symfony/yaml (v6.3.0)
  - Locking theseer/tokenizer (1.2.1)
  - Locking tijsverkoyen/css-to-inline-styles (2.2.6)
  - Locking vlucas/phpdotenv (v5.5.0)
  - Locking voku/portable-ascii (2.0.1)
  - Locking webmozart/assert (1.11.0)
Writing lock file
Installing dependencies from lock file (including require-dev)
Package operations: 108 installs, 0 updates, 0 removals
  - Downloading doctrine/inflector (2.0.8)
  - Downloading doctrine/lexer (3.0.0)
  - Downloading webmozart/assert (1.11.0)
  - Downloading dragonmantank/cron-expression (v3.3.2)
  - Downloading fakerphp/faker (v1.23.0)
  - Downloading symfony/polyfill-php80 (v1.27.0)
  - Downloading symfony/polyfill-php83 (v1.27.0)
  - Downloading symfony/http-foundation (v6.3.1)
  - Downloading fruitcake/php-cors (v1.2.0)
  - Downloading psr/http-message (2.0)
  - Downloading psr/http-client (1.0.2)
  - Downloading ralouphie/getallheaders (3.0.3)
  - Downloading psr/http-factory (1.0.2)
  - Downloading guzzlehttp/psr7 (2.5.0)
  - Downloading guzzlehttp/promises (2.0.0)
  - Downloading guzzlehttp/guzzle (7.7.0)
  - Downloading guzzlehttp/uri-template (v1.0.1)
  - Downloading laravel/pint (v1.10.3)
  - Downloading symfony/yaml (v6.3.0)
  - Downloading voku/portable-ascii (2.0.1)
  - Downloading phpoption/phpoption (1.9.1)
  - Downloading graham-campbell/result-type (v1.1.1)
  - Downloading vlucas/phpdotenv (v5.5.0)
  - Downloading symfony/css-selector (v6.3.0)
  - Downloading tijsverkoyen/css-to-inline-styles (2.2.6)
  - Downloading symfony/var-dumper (v6.3.1)
  - Downloading symfony/polyfill-uuid (v1.27.0)
  - Downloading symfony/uid (v6.3.0)
  - Downloading symfony/routing (v6.3.1)
  - Downloading symfony/polyfill-php72 (v1.27.0)
  - Downloading symfony/polyfill-intl-idn (v1.27.0)
  - Downloading symfony/mime (v6.3.0)
  - Downloading psr/event-dispatcher (1.0.0)
  - Downloading symfony/event-dispatcher-contracts (v3.3.0)
  - Downloading symfony/event-dispatcher (v6.3.0)
  - Downloading psr/log (3.0.0)
  - Downloading egulias/email-validator (4.0.1)
  - Downloading symfony/mailer (v6.3.0)
  - Downloading symfony/error-handler (v6.3.0)
  - Downloading symfony/http-kernel (v6.3.1)
  - Downloading symfony/finder (v6.3.0)
  - Downloading ramsey/collection (2.0.0)
  - Downloading brick/math (0.11.0)
  - Downloading ramsey/uuid (4.7.4)
  - Downloading psr/simple-cache (3.0.0)
  - Downloading nunomaduro/termwind (v1.15.1)
  - Downloading symfony/translation-contracts (v3.3.0)
  - Downloading symfony/translation (v6.3.0)
  - Downloading nesbot/carbon (2.67.0)
  - Downloading monolog/monolog (3.4.0)
  - Downloading league/mime-type-detection (1.11.0)
  - Downloading league/flysystem (3.15.1)
  - Downloading league/flysystem-local (3.15.0)
  - Downloading nette/utils (v4.0.0)
  - Downloading nette/schema (v1.2.3)
  - Downloading dflydev/dot-access-data (v3.0.2)
  - Downloading league/config (v1.2.0)
  - Downloading league/commonmark (2.4.0)
  - Downloading laravel/serializable-closure (v1.3.0)
  - Downloading laravel/framework (v10.14.1)
  - Downloading laravel/sail (v1.23.0)
  - Downloading laravel/sanctum (v3.2.5)
  - Downloading nikic/php-parser (v4.16.0)
  - Downloading psy/psysh (v0.11.18)
  - Downloading laravel/tinker (v2.8.1)
  - Downloading hamcrest/hamcrest-php (v2.0.1)
  - Downloading mockery/mockery (1.6.2)
  - Downloading filp/whoops (2.15.2)
  - Downloading nunomaduro/collision (v7.7.0)
  - Downloading sebastian/version (4.0.1)
  - Downloading sebastian/type (4.0.0)
  - Downloading sebastian/recursion-context (5.0.0)
  - Downloading sebastian/object-reflector (3.0.0)
  - Downloading sebastian/object-enumerator (5.0.0)
  - Downloading sebastian/global-state (6.0.0)
  - Downloading sebastian/exporter (5.0.0)
  - Downloading sebastian/environment (6.0.1)
  - Downloading sebastian/diff (5.0.3)
  - Downloading sebastian/comparator (5.0.0)
  - Downloading sebastian/code-unit (2.0.0)
  - Downloading sebastian/cli-parser (2.0.0)
  - Downloading phpunit/php-timer (6.0.0)
  - Downloading phpunit/php-text-template (3.0.0)
  - Downloading phpunit/php-invoker (4.0.0)
  - Downloading phpunit/php-file-iterator (4.0.2)
  - Downloading theseer/tokenizer (1.2.1)
  - Downloading sebastian/lines-of-code (2.0.0)
  - Downloading sebastian/complexity (3.0.0)
  - Downloading sebastian/code-unit-reverse-lookup (3.0.0)
  - Downloading phpunit/php-code-coverage (10.1.2)
  - Downloading phar-io/version (3.2.1)
  - Downloading phar-io/manifest (2.0.3)
  - Downloading myclabs/deep-copy (1.11.1)
  - Downloading phpunit/phpunit (10.2.3)
  - Downloading spatie/backtrace (1.5.3)
  - Downloading spatie/flare-client-php (1.4.0)
  - Downloading spatie/ignition (1.9.0)
  - Downloading spatie/laravel-ignition (2.2.0)
  0/98 [>---------------------------]   0%
  9/98 [==>-------------------------]   9%
 10/98 [==>-------------------------]  10%
 20/98 [=====>----------------------]  20%
 22/98 [======>---------------------]  22%
 30/98 [========>-------------------]  30%
 40/98 [===========>----------------]  40%
 53/98 [===============>------------]  54%
 60/98 [=================>----------]  61%
 70/98 [====================>-------]  71%
 79/98 [======================>-----]  80%
 89/98 [=========================>--]  90%
 98/98 [============================] 100%
  - Installing doctrine/inflector (2.0.8): Extracting archive
  - Installing doctrine/lexer (3.0.0): Extracting archive
  - Installing symfony/polyfill-ctype (v1.27.0): Extracting archive
      - Installing webmozart/assert (1.11.0): Extracting archive
  - Installing dragonmantank/cron-expression (v3.3.2): Extracting archive
  - Installing symfony/deprecation-contracts (v3.3.0): Extracting archive
  - Installing psr/container (2.0.2): Extracting archive
  - Installing fakerphp/faker (v1.23.0): Extracting archive
      - Installing symfony/polyfill-php80 (v1.27.0): Extracting archive
  - Installing symfony/polyfill-php83 (v1.27.0): Extracting archive
      - Installing symfony/polyfill-mbstring (v1.27.0): Extracting archive
  - Installing symfony/http-foundation (v6.3.1): Extracting archive
  - Installing fruitcake/php-cors (v1.2.0): Extracting archive
  - Installing psr/http-message (2.0): Extracting archive
      - Installing psr/http-client (1.0.2): Extracting archive
  - Installing ralouphie/getallheaders (3.0.3): Extracting archive
  - Installing psr/http-factory (1.0.2): Extracting archive
  - Installing guzzlehttp/psr7 (2.5.0): Extracting archive
  - Installing guzzlehttp/promises (2.0.0): Extracting archive
  - Installing guzzlehttp/guzzle (7.7.0): Extracting archive
  - Installing guzzlehttp/uri-template (v1.0.1): Extracting archive
  - Installing laravel/pint (v1.10.3): Extracting archive
      - Installing symfony/yaml (v6.3.0): Extracting archive
  - Installing voku/portable-ascii (2.0.1): Extracting archive
      - Installing phpoption/phpoption (1.9.1): Extracting archive
  - Installing graham-campbell/result-type (v1.1.1): Extracting archive
  - Installing vlucas/phpdotenv (v5.5.0): Extracting archive
      - Installing symfony/css-selector (v6.3.0): Extracting archive
      - Installing tijsverkoyen/css-to-inline-styles (2.2.6): Extracting archive
  - Installing symfony/var-dumper (v6.3.1): Extracting archive
      - Installing symfony/polyfill-uuid (v1.27.0): Extracting archive
  - Installing symfony/uid (v6.3.0): Extracting archive
  - Installing symfony/routing (v6.3.1): Extracting archive
      - Installing symfony/process (v6.3.0): Extracting archive
  - Installing symfony/polyfill-php72 (v1.27.0): Extracting archive
      - Installing symfony/polyfill-intl-normalizer (v1.27.0): Extracting archive
  - Installing symfony/polyfill-intl-idn (v1.27.0): Extracting archive
  - Installing symfony/mime (v6.3.0): Extracting archive
      - Installing symfony/service-contracts (v3.3.0): Extracting archive
  - Installing psr/event-dispatcher (1.0.0): Extracting archive
  - Installing symfony/event-dispatcher-contracts (v3.3.0): Extracting archive
  - Installing symfony/event-dispatcher (v6.3.0): Extracting archive
  - Installing psr/log (3.0.0): Extracting archive
  - Installing egulias/email-validator (4.0.1): Extracting archive
      - Installing symfony/mailer (v6.3.0): Extracting archive
      - Installing symfony/error-handler (v6.3.0): Extracting archive
      - Installing symfony/http-kernel (v6.3.1): Extracting archive
      - Installing symfony/finder (v6.3.0): Extracting archive
  - Installing symfony/polyfill-intl-grapheme (v1.27.0): Extracting archive
  - Installing symfony/string (v6.3.0): Extracting archive
      - Installing symfony/console (v6.3.0): Extracting archive
      - Installing ramsey/collection (2.0.0): Extracting archive
  - Installing brick/math (0.11.0): Extracting archive
      - Installing ramsey/uuid (4.7.4): Extracting archive
      - Installing psr/simple-cache (3.0.0): Extracting archive
      - Installing nunomaduro/termwind (v1.15.1): Extracting archive
      - Installing symfony/translation-contracts (v3.3.0): Extracting archive
  - Installing symfony/translation (v6.3.0): Extracting archive
      - Installing nesbot/carbon (2.67.0): Extracting archive
      - Installing monolog/monolog (3.4.0): Extracting archive
      - Installing league/mime-type-detection (1.11.0): Extracting archive
  - Installing league/flysystem (3.15.1): Extracting archive
  - Installing league/flysystem-local (3.15.0): Extracting archive
  - Installing nette/utils (v4.0.0): Extracting archive
      - Installing nette/schema (v1.2.3): Extracting archive
  - Installing dflydev/dot-access-data (v3.0.2): Extracting archive
  - Installing league/config (v1.2.0): Extracting archive
  - Installing league/commonmark (2.4.0): Extracting archive
      - Installing laravel/serializable-closure (v1.3.0): Extracting archive
  - Installing laravel/framework (v10.14.1): Extracting archive
      - Installing laravel/sail (v1.23.0): Extracting archive
      - Installing laravel/sanctum (v3.2.5): Extracting archive
  - Installing nikic/php-parser (v4.16.0): Extracting archive
      - Installing psy/psysh (v0.11.18): Extracting archive
      - Installing laravel/tinker (v2.8.1): Extracting archive
  - Installing hamcrest/hamcrest-php (v2.0.1): Extracting archive
      - Installing mockery/mockery (1.6.2): Extracting archive
      - Installing filp/whoops (2.15.2): Extracting archive
      - Installing nunomaduro/collision (v7.7.0): Extracting archive
  - Installing sebastian/version (4.0.1): Extracting archive
  - Installing sebastian/type (4.0.0): Extracting archive
      - Installing sebastian/recursion-context (5.0.0): Extracting archive
  - Installing sebastian/object-reflector (3.0.0): Extracting archive
  - Installing sebastian/object-enumerator (5.0.0): Extracting archive
  - Installing sebastian/global-state (6.0.0): Extracting archive
  - Installing sebastian/exporter (5.0.0): Extracting archive
  - Installing sebastian/environment (6.0.1): Extracting archive
  - Installing sebastian/diff (5.0.3): Extracting archive
      - Installing sebastian/comparator (5.0.0): Extracting archive
  - Installing sebastian/code-unit (2.0.0): Extracting archive
  - Installing sebastian/cli-parser (2.0.0): Extracting archive
      - Installing phpunit/php-timer (6.0.0): Extracting archive
  - Installing phpunit/php-text-template (3.0.0): Extracting archive
  - Installing phpunit/php-invoker (4.0.0): Extracting archive
  - Installing phpunit/php-file-iterator (4.0.2): Extracting archive
  - Installing theseer/tokenizer (1.2.1): Extracting archive
      - Installing sebastian/lines-of-code (2.0.0): Extracting archive
  - Installing sebastian/complexity (3.0.0): Extracting archive
  - Installing sebastian/code-unit-reverse-lookup (3.0.0): Extracting archive
  - Installing phpunit/php-code-coverage (10.1.2): Extracting archive
      - Installing phar-io/version (3.2.1): Extracting archive
  - Installing phar-io/manifest (2.0.3): Extracting archive
      - Installing myclabs/deep-copy (1.11.1): Extracting archive
      - Installing phpunit/phpunit (10.2.3): Extracting archive
      - Installing spatie/backtrace (1.5.3): Extracting archive
  - Installing spatie/flare-client-php (1.4.0): Extracting archive
  - Installing spatie/ignition (1.9.0): Extracting archive
      - Installing spatie/laravel-ignition (2.2.0): Extracting archive
      0/98 [>---------------------------]   0%
 10/98 [==>-------------------------]  10%
 20/98 [=====>----------------------]  20%
 30/98 [========>-------------------]  30%
 40/98 [===========>----------------]  40%
 50/98 [==============>-------------]  51%
 60/98 [=================>----------]  61%
 70/98 [====================>-------]  71%
 80/98 [======================>-----]  81%
 90/98 [=========================>--]  91%
 98/98 [============================] 100%
    61 package suggestions were added by new dependencies, use `composer suggest` to see details.
Generating optimized autoload files
    > Illuminate\Foundation\ComposerScripts::postAutoloadDump
> @php artisan package:discover --ansi

   INFO  Discovering packages.

  laravel/sail ................................................................................................................................ DONE
  laravel/sanctum ............................................................................................................................. DONE
  laravel/tinker .............................................................................................................................. DONE
  nesbot/carbon ............................................................................................................................... DONE
  nunomaduro/collision ........................................................................................................................ DONE
  nunomaduro/termwind ......................................................................................................................... DONE
  spatie/laravel-ignition ..................................................................................................................... DONE

    82 packages you are using are looking for funding.
Use the `composer fund` command to find out more!
    > @php artisan vendor:publish --tag=laravel-assets --ansi --force

   INFO  No publishable resources for tag [laravel-assets].

    No security vulnerability advisories found
    > @php artisan key:generate --ansi

   INFO  Application key set successfully.

   INFO  Application ready! Build something amazing.

PS C:\> cd techunitbook
PS C:\techunitbook> php artisan serve

   INFO  Server running on [http://127.0.0.1:8000].

  Press Ctrl+C to stop the server

  2023-07-02 18:35:19 .................................................................................................................................................................................... ~ 0s
  2023-07-02 18:35:19 /favicon.ico ....................................................................................................................................................................... ~ 0s
  2023-07-02 18:35:35 /favicon.ico ....................................................................................................................................................................... ~ 0s
  2023-07-02 18:35:35 .................................................................................................................................................................................... ~ 2s
PS C:\techunitbook>
</pre>
