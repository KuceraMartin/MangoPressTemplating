# MangoPressTemplating
Prepared templating workflow with filters and macros.

```php
MangoPressTemplating::init();
```

## Using flash messages
In PHP:
```php
$param = flashSuccess('Something just went great!');
wp_redirect(add_query_arg(FLASH_KEY, $param));
```
and then in latte much like in regular Nette templates.
