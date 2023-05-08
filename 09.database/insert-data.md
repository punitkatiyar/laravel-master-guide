# controler

```
public function store(Request $request)
    {
        //
        $res=new todo;
        $res->name=$request->input('name');
        $res->save();
        $request->session()->flash('mag','Data Submit');
        return redirect('todo_show');
    }
```

# View 

```
< form method="post" action="todo_submit" >
    @csrf
< input type="text" name="name" required >
< input type="submit" name="insert" >
< /form >
```

# routes

> Route::get('todo_insert',[TodoController::class, 'create']);
