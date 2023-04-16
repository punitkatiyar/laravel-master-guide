# laravel Session

## set the session
<pre>
function session_set(Request,$r)
{
  $r->session()->put('name',"admin");
}
</pre>

## get the session

<pre>
function session_get(Request,$r)
{
  $r->session()->get('name');
}
</pre>

## remove the session

<pre>
function session_remove(Request,$r)
{
  $r->session()->forget('name');
}
</pre>

## check the session

<pre>
function session_check(Request,$r)
{
  if($r->session()->has('name'))
  {
  echo "yes";
  }
  else{
  echo "No";
  }
}
</pre>
