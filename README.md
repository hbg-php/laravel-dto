[![Latest Version on Packagist](https://img.shields.io/packagist/v/hbg-php/laravel-dto.svg?style=flat-square)](https://packagist.org/packages/hbg-php/laravel-dto)
[![Total Downloads](https://img.shields.io/packagist/dt/hbg-php/laravel-dto.svg?style=flat-square)](https://packagist.org/packages/hbg-php/laravel-dto)
[![PHP Version](https://img.shields.io/packagist/php-v/hbg-php/laravel-dto.svg?style=flat-square)](https://www.php.net)
[![License](https://img.shields.io/github/license/hbg-php/laravel-dto.svg?style=flat-square)](LICENSE)
[![Tests](https://img.shields.io/github/actions/workflow/status/hbg-php/laravel-dto/run-tests.yml?label=tests&style=flat-square)](https://github.com/hbg-php/laravel-dto/actions)

# Laravel DTO

A simple and extensible package for creating and handling **Data Transfer Objects (DTOs)** in Laravel applications.

## Features

- Create DTOs from arrays or Laravel Requests
- Optional validation with rules defined inside the DTO class
- Convert DTOs to array or JSON
- Support for typed and immutable properties (PHP 8.1+)

## Installation

In a Laravel project:

```bash
composer require hugomatheuss/laravel-dto