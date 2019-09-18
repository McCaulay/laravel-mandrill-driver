# Laravel Mandrill Driver

[![TravisCI](https://img.shields.io/travis/intonate/laravel-mandrill-driver/master.svg?style=flat-square)](https://travis-ci.org/intonate/laravel-mandrill-driver)
[![StyleCI](https://github.styleci.io/repos/209204562/shield?branch=master)](https://github.styleci.io/repos/209204562)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/intonate/laravel-mandrill-driver/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/intonate/laravel-mandrill-driver/?branch=master)
[![License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](https://github.com/intonate/laravel-mandrill-driver/blob/master/LICENSE)

## Introduction

**This is a community project and not an "official" one**

## Installation

To get started simply run:

```sh
composer require intonate/laravel-mandrill-driver
```

Update your `config/services.php` and `.env` files:

```php
'mandrill' => [
    'secret' => env('MANDRILL_SECRET'),
],
```

## Credits

- [Jorge González](https://github.com/scrubmx)
- [All Contributors](../../contributors)

## License

Tinker Zero is open-sourced software licensed under the [MIT license](LICENSE).