Stock Tracker 
======================

A Symfony project created on July 19th, 2016.

This project is an implementation of a customizable stock tracking interface using Symfony and Angular

##	Steps to install:

```bash
# Create parameters.yml file and setup database parameters
composer install
bower install

# For almost all OS other than Windows
php app/console assets:install --symlink web
# For Windows, use
php app/console assets:install web

php app/console doctrine:database:create
php app/console doctrine:schema:update --force
```
