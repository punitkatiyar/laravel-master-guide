# Session Flash

<pre>
$r->session()->flash('err','Please Enter Valied Detail');
return redirect('login');
</pre>

## show flash message to view

> {{ session('err') }}
