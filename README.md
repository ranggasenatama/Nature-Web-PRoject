# Nature-Web-PRoject
# Backpack\Settings

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.md)
[![Build Status][ico-travis]][link-travis]
[![Coverage Status][ico-scrutinizer]][link-scrutinizer]
[![Quality Score][ico-code-quality]][link-code-quality]
[![Style CI](https://styleci.io/repos/53683729/shield)](https://styleci.io/repos/53683729)
[![Total Downloads][ico-downloads]][link-downloads]

An interface for the administrator to easily change application settings. Uses Laravel Backpack. On Laravel 5.2.

> ### Security updates and breaking changes
> Please **[subscribe to the Backpack Newsletter](http://eepurl.com/bUEGjf)** so you can find out about any security updates, breaking changes or major features. We send an email every 1-2 months.

## Screenshots

See http://laravelbackpack.com

- List view:
![List / table view in Backpack/Settings](https://backpackforlaravel.com/uploads/screenshots/settings_list.png)
- Editing a setting with the email field type:

## Change log

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Testing

``` bash
$ composer test
```

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Overwriting Functionality

If you need to modify how this works in a project: 
- create a ```routes/backpack/settings.php``` file; the package will see that, and load _your_ routes file, instead of the one in the package; 
- create controllers/models that extend the ones in the package, and use those in your new routes file;
- modify anything you'd like in the new controllers/models;

## Security

If you discover any security related issues, please email hello@tabacitu.ro instead of using the issue tracker.

Please **[subscribe to the Backpack Newsletter](http://eepurl.com/bUEGjf)** so you can find out about any security updates, breaking changes or major features. We send an email every 1-2 months.

## Credits

- [Cristian Tabacitu][link-author]
- [All Contributors][link-contributors]

## License

Backpack is free for non-commercial use and 39 EUR/project for commercial use. Please see [License File](LICENSE.md) and [backpackforlaravel.com](https://backpackforlaravel.com/#pricing) for more information.

[ico-version]: https://img.shields.io/packagist/v/backpack/settings.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-travis]: https://img.shields.io/travis/laravel-backpack/settings/master.svg?style=flat-square
[ico-scrutinizer]: https://img.shields.io/scrutinizer/coverage/g/laravel-backpack/settings.svg?style=flat-square
[ico-code-quality]: https://img.shields.io/scrutinizer/g/laravel-backpack/settings.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/backpack/settings.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/backpack/settings
[link-travis]: https://travis-ci.org/laravel-backpack/settings
[link-scrutinizer]: https://scrutinizer-ci.com/g/laravel-backpack/settings/code-structure
[link-code-quality]: https://scrutinizer-ci.com/g/laravel-backpack/settings
[link-downloads]: https://packagist.org/packages/backpack/settings
[link-author]: http://tabacitu.ro
[link-contributors]: ../../contributors