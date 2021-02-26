<div align="center">
    <a href="https://php.net">
        <img
            alt="PHP"
            src="https://www.php.net/images/logos/new-php-logo.svg"
            width="150">
    </a>
</div>

# The PHP Interpreter

PHP is a popular general-purpose scripting language that is especially suited to
web development. Fast, flexible and pragmatic, PHP powers everything from your
blog to the most popular websites in the world. PHP is distributed under the
[PHP License v3.01](LICENSE).

## Documentation

The PHP manual is available at [php.net/docs](https://php.net/docs).

## Installation

For Windows, the PHP binaries can be obtained from
[windows.php.net](https://windows.php.net). After extracting the archive the
`*.exe` files are ready to use.

For Mac, see [Homebrew](https://formulae.brew.sh/formula/php)

For other systems, see the [installation chapter](https://php.net/install).

## Start the local php server
* Command
    ```
    php -S localhost:8000
    ```
* Output
    ```
    PHP 7.3.11 Development Server started at Fri Feb 26 17:39:24 2021
    Listening on http://localhost:8000
    Document root is /PHP_tutorial
    Press Ctrl-C to quit.
    ```

* You can access through browser `http://localhost:8000`

## Information about PHP's configuration
* See [pinfo.php](pinfo.php)
* See result in `http://localhost:8000/pinfo.php`

## How to connect a PostgreSQL database
* See [pgdemo](pgdemo/)

## Guidelines
* [PHP coding standards](https://github.com/php/php-src/blob/master/CODING_STANDARDS.md)
