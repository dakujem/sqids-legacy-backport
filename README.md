# Sqids (backport for legacy PHP)

[![Test suite](https://github.com/dakujem/sqids-legacy-backport/actions/workflows/phpunit.yml/badge.svg)](https://github.com/dakujem/sqids-legacy-backport/actions/workflows/phpunit.yml)

>
> 💿 `composer require dakujem/sqids-legacy-backport`
>

This is a backport of the original package [sqids/sqids](https://github.com/sqids/sqids-php)
for **PHP 7.4** and **PHP 8.0** only.


## Documentation

Please refer to the documentation of the original package:
👉 [sqids/sqids](https://github.com/sqids/sqids-php) 👈


## Migration to supported PHP version

After updating your project to a supported PHP version, change your project requirement from `dakujem/sqids-legacy-backport` to `sqids/sqids`.
Chances are, you need not do anything else.

This backport is based on [a stable release](https://github.com/sqids/sqids-php/releases) of `sqids/sqids`
current at the time of update.
PHP 8 features (most notably constructor property promotion) have been removed or replaced.
