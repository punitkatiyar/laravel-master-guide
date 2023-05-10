# Laravel Hosting On Shared Server


# Craete .htaccess File in 

```
<IfModule mod_rewrite.c>
RewriteEngine On
RewriteRule ^(.*)$ public/$1 [L]
</IfModule>
```
