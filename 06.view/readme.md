# laravel URL Class

> curent url : {{URL::current()}}

> full url : {{URL::full()}}

> Current url : {{URL::current()}}

> Previous url : {{URL::previous()}}

## Anchor Tag In Laravel

```
<a href="{{URL::to('/page/')}}">Page</a>
<a href="{{URL::to('/page/sub-page')}}">Sub Page</a>
```







## Image CSS and Javascript In Laravel

**Store external data in public folder**



```
<img src="{{ asset('images/logo.png') }}" alt="Logo">
```

```
<img src="{{ URL('image/banner.png') }}" alt="My Image">
```
