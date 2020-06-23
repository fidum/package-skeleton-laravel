# :package_description

[![Latest Version on Packagist](https://img.shields.io/packagist/v/fidum/:package_name.svg?style=for-the-badge)](https://packagist.org/packages/fidum/:package_name)
[![GitHub Tests Action Status](https://img.shields.io/github/workflow/status/fidum/:package_name/Tests?label=tests&style=for-the-badge)](https://github.com/fidum/:package_name/actions?query=workflow%3Arun-tests+branch%3Amaster)
[![Codecov](https://img.shields.io/codecov/c/github/fidum/:package_name?logo=codecov&logoColor=white&style=for-the-badge)](https://codecov.io/gh/fidum/:package_name)
[![Twitter Follow](https://img.shields.io/twitter/follow/danmasonmp?label=Follow&logo=twitter&style=for-the-badge)](https://twitter.com/danmasonmp)

**Note:** Replace ```:author_name``` ```:author_username``` ```:package_name``` ```:package_description``` with their correct values in [README.md](README.md), [CHANGELOG.md](CHANGELOG.md), [CONTRIBUTING.md](CONTRIBUTING.md), [LICENSE.md](LICENSE.md) and [composer.json](composer.json) files, then delete this line. You can also run `configure-skeleton.sh` to do this automatically.

This is where your description should go. Limit it to a paragraph or two. Consider adding a small example.

## Installation

You can install the package via composer:

```bash
composer require fidum/:package_name
```

You can publish and run the migrations with:

```bash
php artisan vendor:publish --provider="Fidum\Skeleton\SkeletonServiceProvider" --tag="migrations"
php artisan migrate
```

You can publish the config file with:
```bash
php artisan vendor:publish --provider="Fidum\Skeleton\SkeletonServiceProvider" --tag="config"
```

This is the contents of the published config file:

```php
return [
];
```

## Usage

``` php
$skeleton = new Fidum\Skeleton();
echo $skeleton->echoPhrase('Hello, Fidum!');
```

## Testing

``` bash
composer test
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Security

If you discover any security related issues, please email fidum.dev@gmail.com instead of using the issue tracker.

## Credits

- [:author_name](https://github.com/:author_username)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
