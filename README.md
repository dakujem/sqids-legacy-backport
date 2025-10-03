# Sqids (backport for legacy PHP)

[![Test suite](https://github.com/dakujem/sqids-legacy-backport/actions/workflows/phpunit.yml/badge.svg)](https://github.com/dakujem/sqids-legacy-backport/actions/workflows/phpunit.yml)

>
> 💿 `composer require dakujem/sqids-legacy-backport`
>

This is a trivial backport of the original package [sqids/sqids](https://github.com/sqids/sqids-php)
for **PHP 7.4** and **PHP 8.0** only.


## Documentation

Please refer to the documentation of the original package:
👉 [sqids/sqids](https://github.com/sqids/sqids-php) 👈


## Migration to PHP 8.1+

After updating your project to a version supported by the original `sqids/sqids`,
change your project requirement from `dakujem/sqids-legacy-backport` to `sqids/sqids`.  
That should be it.


## Compatibility

This backport is based on [the same tag](https://github.com/sqids/sqids-php/tags) of `sqids/sqids`
it is released under.  
PHP 8 features (most notably constructor property promotion) have been removed or replaced.
