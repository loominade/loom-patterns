# LOOM patterns

Demo site for the [UI Patterns](https://www.drupal.org/project/ui_patterns) module based on
[Composer template for Drupal projects](https://github.com/drupal-composer/drupal-project).

## Usage

First you need to [install composer](https://getcomposer.org/doc/00-intro.md#installation-linux-unix-osx), after that
clone the project and run:

```
composer install
cd web
../vendor/bin/drush si config_installer --db-url=mysql://user:pass@localhost/db
```
