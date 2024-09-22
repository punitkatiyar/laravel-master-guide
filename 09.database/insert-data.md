# controler

```
public function create(Request $request)
    {
        //step 1
        echo "<h1>Hello</h1>";
        echo '<hr>';
        echo "<h2><pre>";
        print_r($_POST);
        echo "</pre></h2>";
        
        // step 2
        echo '<hr>';
        echo $_POST['name'];

        //  step 3
        echo '<hr>';
        $name=$request->input('name');
        echo $name;


        
}
```

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

**In Laravel, CSRF (Cross-Site Request Forgery) protection is a security feature that helps to prevent malicious websites or scripts from performing actions on behalf of authenticated users without their consent. Laravel includes built-in CSRF protection for all forms submitted through the web interface.**

```
< form method="post" action="todo_submit" >
    @csrf
< input type="text" name="name" required >
< input type="submit" name="insert" >
< /form >
```

# routes

> Route::get('todo_insert',[TodoController::class, 'create']);
