# controler

<pre>
public function update(Request $request, todo $todo)
    {

        $res=todo::find($request->id);
        $res->name=$request->input('name');
        $res->save();
        return redirect('todo_show');  
    }
</pre>

# routing

> Route::get('todo_edit/{id}',[TodoController::class,'edit']);

> Route::post('todo_update/{id}',[TodoController::class,'update']);
