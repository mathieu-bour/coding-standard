# mathieu-bour/coding-standard
![version](https://img.shields.io/packagist/v/mathieu-bour/coding-standard?style=flat-square)
![license](https://img.shields.io/packagist/l/mathieu-bour/coding-standard?style=flat-square)
![php-version](https://img.shields.io/packagist/php-v/mathieu-bour/coding-standard?style=flat-square)

My personal PHP_CodeSniffer standard, derived from [mathrix-education/coding-standard](https://github.com/mathrix-education/coding-standard).
Uses the sniffs from [PHP_CodeSniffer][1] and
[Slevomat Coding Standard][2].

[1]: https://github.com/squizlabs/PHP_CodeSniffer 
[2]: https://github.com/slevomat/coding-standard

## Installation

```shell
composer require mathieu-bour/coding-standard
```

In your phpcs.xml(.dist) file, refer to the standard with:

```xml
<rule ref="Windy"/>
```
