# PHP Chrome HTML to PDF

A PHP library for converting HTML to PDF using Google Chrome.

[![Build Status](https://travis-ci.org/spiritix/php-chrome-html2pdf.svg?branch=master)](https://travis-ci.org/spiritix/php-chrome-html2pdf)
[![Code Climate](https://codeclimate.com/github/spiritix/php-chrome-html2pdf/badges/gpa.svg)](https://codeclimate.com/github/spiritix/php-chrome-html2pdf)
[![Total Downloads](https://poser.pugx.org/spiritix/php-chrome-html2pdf/d/total.svg)](https://packagist.org/packages/spiritix/php-chrome-html2pdf)
[![Latest Stable Version](https://poser.pugx.org/spiritix/php-chrome-html2pdf/v/stable.svg)](https://packagist.org/packages/spiritix/php-chrome-html2pdf)
[![Latest Unstable Version](https://poser.pugx.org/spiritix/php-chrome-html2pdf/v/unstable.svg)](https://packagist.org/packages/spiritix/php-chrome-html2pdf)
[![License](https://poser.pugx.org/spiritix/php-chrome-html2pdf/license.svg)](https://packagist.org/packages/spiritix/php-chrome-html2pdf)

## How it works

This library is based on [puppeteer](https://github.com/GoogleChrome/puppeteer), a headless Chrome Node API which is 
maintained by the Chrome DevTools team.

It provides a simple PHP wrapper around the Node API, focused on generating beautiful PDF files.

In contrast to other HTML to PDF converters like [wkhtmltopdf](https://wkhtmltopdf.org/), the corresponding 
[PHP wrapper](https://github.com/spiritix/html-to-pdf) or similar libraries, it is based on a current Chrome version 
instead of outdated and unmaintained WebKit builds. This library therefore fully supports CSS3, HTML5, SVGs, SPAs, 
and all the other fancy stuff people use these days.

## Requirements

- PHP 7.0+ with enabled program execution functions (proc_open) and 'fopen wrappers'
- Node.js 7.6+
- A few [OS specific dependencies](https://github.com/GoogleChrome/puppeteer/blob/master/docs/troubleshooting.md)

## Installation

PHP Chrome HTML to PDF can be installed via [Composer](http://getcomposer.org) by requiring the
`spiritix/php-chrome-html2pdf` package in your project's `composer.json`.
Or simply run this command:

```sh
composer require spiritix/php-chrome-html2pdf
```

The required JS packages are installed automatically in the background.

## Contributing

Contributions in any form are welcome.
Please consider the following guidelines before submitting pull requests:

- **Coding standard** - It's mostly PSR. 
- **Add tests!** - Your PR won't be accepted if it doesn't have tests.

## License

PHP Chrome HTML to PDF is free software distributed under the terms of the MIT license.