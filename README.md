# example-config-file
Just an example for a better way to write config files in Vanilla PHP.

# Security
_To prevent access to config.php file, add into the .htaccess file:_
```
<Files config.php>
    order allow,deny
    deny from all
</Files>
```
