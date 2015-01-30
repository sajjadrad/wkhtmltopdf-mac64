wkhtmltopdf
================

This Repo contains the Mac OS (Yosemite) Binarys from the [wkhtmltopdf project](http://wkhtmltopdf.org/).
More about the functionality of wkhtmltopdf and wkthmltoimage can be found there.
This package is cloned from [h4cc packages](https://packagist.org/packages/h4cc/) and replaced with mac Binarys.
## Installation

_Hint_:
The version of the binary is equal to the git tag.
To install the latest version, use '0.12.2.1'.

In case this package does _not_ work on your system, try installing the matching system packages from here: [http://wkhtmltopdf.org/downloads.html](http://wkhtmltopdf.org/downloads.html).

### Packagist

This package can be found on [Packagist](http://packagist.org) and installed with [Composer](http://getcomposer.com/).

Require the package for _i386_ with:

    php composer.phar require h4cc/wkhtmltopdf-i386 "0.12.2.1"

And for _amd64_ with:

    php composer.phar require h4cc/wkhtmltopdf-amd64 "0.12.2.1"

And for _mac64_ with:

    php composer.phar require sajjadrad/wkhtmltopdf-mac64 "0.12.2.1"

The binary will then be located at:

    vendor/sajjadrad/wkhtmltopdf-mac64/bin/wkhtmltopdf-mac64

Also a symlink will be created in your configured bin/ folder, for example:

    vendor/bin/wkhtmltopdf-mac64

