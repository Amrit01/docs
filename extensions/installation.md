# Installation in Laravel 5+

Install this package with composer:

```
composer require laravel-doctrine/extensions
```

This package wraps extensions from [Gedmo](https://github.com/Atlantic18/DoctrineExtensions) and [Berberlei](https://github.com/beberlei/DoctrineExtensions).

To include Gedmo extensions install them:

```

composer require "gedmo/doctrine-extensions=^2.4"
```

And then add the Gedmo (Behavioral) extensions service provider in `config/app.php`:

```php
LaravelDoctrine\Extensions\GedmoExtensionsServiceProvider::class,
```

To include Beberlei (Query/Type) extensions install them:

```

composer require "beberlei/DoctrineExtensions=^1.0"
```

And then add the Berberlei extensions service provider in `config/app.php`:


```php
LaravelDoctrine\Extensions\BeberleiExtensionsServiceProvider::class,
```
