# Step 1 Database Configuration

> go to app and open env file.

> setup database connection : database name , user name , password

## Step 2 Create A Modeal

<pre>
PS C:\xampp\htdocs\template> php artisan make:model todo -mcr

   INFO  Model [C:\xampp\htdocs\template\app/Models/todo.php] created successfully.

   INFO  Migration [C:\xampp\htdocs\template\database\migrations/2023_04_08_090146_create_todos_table.php] created successfully.

   INFO  Controller [C:\xampp\htdocs\template\app/Http/Controllers/TodoController.php] created successfully.

PS C:\xampp\htdocs\template>
</pre>

## Step 3 Migrate The database

<pre>
PS C:\xampp\htdocs\template> php artisan migrate

   INFO  Preparing database.

  Creating migration table ................................................................................. 16ms DONE

   INFO  Running migrations.

  2019_12_14_000001_create_personal_access_tokens_table .................................................... 36ms DONE
  2023_04_08_090146_create_todos_table ..................................................................... 10ms DONE
PS C:\xampp\htdocs\template>
</pre>
