# This is a boilerplate project used as a starter for quick jobs.

It contains a basic configuration for composer with applying PSR-4 coding standard into src directory.
It provides front controller `app.php` that can be used to tie it up together.

This boilerplate is only for starter, when it grows use Silex microframework or Symfony2 instead.
Remember to install composer from https://getcomposer.org/download/ and then run `composer.phar install`.

Ideas:

- use phpspec for generating skeletons and testing
- use behat for BDD
- use phpcs for testing all against coding standard


## Usage

`php composer.phar create-project tworzenieweb/boilerplate path dev-master`

where `path` is the place where you want to init project.
