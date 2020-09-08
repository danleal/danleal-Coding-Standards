# WooDelivery Coding Standards

The goal of this repo is to provide the necessary sniffs for our custom coding standards, making sure that all WooDelivery products maintain a consistent codebase.

## Installation

Our coding standards rely on PHPCS and WordPress Coding Standards. The easiest way to get everything up and running is installing this package globally via Composer:
```
composer global require "danleal/woodeliverycs:dev-master"
```

This command will install PHP_CodeSniffer, WPCS, our coding standard, and PHP_CodeSniffer Standards Composer Installer, a composer package that automatically sets the PHPCS `installed_paths` config.

### Making `phpcs` available

By default, `phpcs` binary will be available at `~/.config/composer/vendor/bin` (on Linux machines). To make it available anywhere in the command line, it is necessary to add that folder to the env `$PATH` variable.

On linux machines it is possible adding this line in the end of the `~/.bashrc` file:
```
export PATH="$HOME/.config/composer/vendor/bin/:$PATH"
```

# Changelog

### Version 1.0.0
* Added: Initial version of the Coding Standards;
