# Pandoc filter for drupal 7

This module allows you to use the [pandoc-php][https://github.com/ryakad/pandoc-php] module as a filter for drupal 7 text formats. The module provides a small number of settings and will produce either html or html5 output to be used in the display of drupal fields. 

The module is currently very experimental and has only been tested with the mediawiki format under very controlled conditions and could potentially represent a security risk so it **should not** be used in production in its current form.

# Dependencies and installation

It is recommended that this module be enabled via drush through:

`drush en pandoc_filter`

This will prompt you for the installation of the composer_manager module from drupal.org. This module will automatically make use of the included composer.json file to install the pandoc-php module that it depends on. However, the module will also accept a local composer installation in the module directory if you wish to install and enable it manually.

