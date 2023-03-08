# Weeyn Catalog Category Module
Weeyn catalog brand module

![Packagist PHP Version](https://img.shields.io/packagist/dependency-v/weeynsoft/catalog-brand/php)
![Packagist Version](https://img.shields.io/packagist/v/weeynsoft/catalog-brand)
![Packagist Downloads](https://img.shields.io/packagist/dt/weeynsoft/catalog-brand?label=download)
![GitHub](https://img.shields.io/github/license/weeynsoft/catalog-brand)


This is the standalone catalog brand module of the [Weeyn](https://weeyn.com).

## Installation

(As Standalone Component)

1. `composer require weeynsoft/catalog-brand`
2. `php artisan vendor:publish --provider="Konekt\Concord\ConcordServiceProvider"`
3. Add `Weeyn\CatalogCategory\Providers\ModuleServiceProvider::class` to modules in `config/concord.php`
4. `php artisan migrate`

## Usage

See the [Weeyn Category Module Documentation](https://weeyn.com/docs/master/catalog-brand) for more details. 

## About Us

Weeyn development is led by the core team.