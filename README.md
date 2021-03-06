# Doctrine 2 for Laravel on PHP 5.3

A Doctrine 2 implementation that melts with Laravel 4 on PHP 5.3.

## Documentation

This is a fork of package v0.5.0 made by [Mitchell van Wijngaarden](https://github.com/mitchellvanw/laravel-doctrine) for an implementation with PHP versions 5.3 or 5.4. Consider this an ugly downgrade only.

- If you work with Laravel 4 on PHP 7, use: https://github.com/mitchellvanw/laravel-doctrine
- If you work with Laravel 5 on PHP 7, use: https://github.com/laravel-doctrine/orm

Things done:

1. Array declarations in square brackets are replaced by function "array()"
2. The calls to static method "class" for getting fully qualified class names are replaced by literal strings
3. One anonymous function which called $this now calls $that which is bound to $this earlier. Method mapLaravelToDoctrineConfig() is made public for this purpose only.
4. Traits are removed

