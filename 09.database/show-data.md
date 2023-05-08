# Routing path

> use App\Http\Controllers\TodoController;

> Route::get('todo_show',[TodoController::class, 'show']);

# Controler Function

```
public function show(todo $todo)
    {
        return view('todo_show')->with('todoArr',todo::all());
    }
```


# Blade File

```
<table border="1" width="50%" cellpadding="10px">
    <tr>
        <td>Id</td>
        <td>name</td>
        <td>Action</td>
    </tr>
    @foreach($todoArr as $todo)
    <tr>
        <td>{{$todo->id}}</td>
        <td>{{$todo->name}}</td>
        <td><a href="todo_delete/{{$todo->id}}">Delete</td>
    </tr>

    @endforeach
</table>
```
