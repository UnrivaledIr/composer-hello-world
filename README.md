# My PHP Package

A simple PHP package to demonstrate how to create and publish a Composer package.

## Installation

```bash
composer require unrivaledir/composer-hello-world
```

## How to run?

- First run :

`composer dump-autoload`

- then create `index.php` file. insert this code and run it:

```
<?php

use App\ComposerHelloWorldClass as MyClass;

require_once __DIR__ . '/vendor/autoload.php';

$myClass = new MyClass();
echo $myClass->sayHello();
```

- Finally

`php -S localhost:8000`

# License

This code published under GPL-3.0-or-later license.
