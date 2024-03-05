**Lightweight mock [PSR-15 HTTP Server Request Handler](https://www.php-fig.org/psr/psr-15/) implementation tailored to help you write cleaner test suites and less code.**

[![codecov](https://img.shields.io/codecov/c/github/psr-mock/http-request-handler-implementation)](https://codecov.io/gh/psr-mock/http-request-handler-implementation) [![packagist](https://img.shields.io/packagist/dt/psr-mock/http-request-handler-implementation)](https://packagist.org/packages/psr-mock/http-request-handler-implementation) ![status](https://img.shields.io/github/checks-status/psr-mock/http-request-handler-implementation/1.x) ![license](https://img.shields.io/github/license/psr-mock/http-request-handler-implementation)

This library is for developers implementing PSR-15 interfaces in their applications. The library mocks a "real" implementation and enables you to write cleaner test suites that are easier to write, read, and maintain. It has no hard dependencies, does not require any configuration, and provides a robust developer API for troubleshooting issues in your application.

This package is part of the [PSR Mock](https://github.com/psr-mock) utility suite, which provide mock implimentations of nearly every PSR interface available.

## Requirements

-   PHP 8.1+
-   Composer 2.0+

## Installation

```bash
composer require --dev psr-mock/http-request-handler-implementation
```

Only install this library as a development dependency (`--dev`).
It's not built for use in production environments.

---

This library is not produced or endorsed by, or otherwise affiliated with, the PHP-FIG.
