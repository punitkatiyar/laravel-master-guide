# laravel Session

## set the session
<pre>
function session_set(Request,$r)
{
  $r->session()->put('name',"admin");
}

</pre>
